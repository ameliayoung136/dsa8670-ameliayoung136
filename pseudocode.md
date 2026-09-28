# Pseudocode: Analyzing a Property Funding Dataset

Descriptive steps for analyzing daily funding activity across properties.
This is an outline of the approach, not working code.

## Step 1: Load the dataset
- Read in the funding records, one row per loan funded, with columns for funding
  date, property ID, market, loan amount, property type, and investor.
- Confirm the row count matches what the source system reports for the same date
  range, so I know nothing was dropped on the way in.
- Check the data types, especially that funding date is read as a date and not text.

## Step 2: Clean the data
- Check for missing values in the fields the analysis depends on. Drop rows missing
  a funding date or loan amount, and note how many were removed and why.
- Look for duplicate records, since the same loan can appear twice if a report was
  pulled more than once. Remove exact duplicates on property ID and funding date.
- Standardize the text fields. Market and property type often come through with
  inconsistent spelling or casing, which splits one category into several.
- Check loan amounts for values that are impossible or clearly wrong, such as
  negatives or zeros, and decide whether to exclude or flag them.
- Write down the definition being used for anything ambiguous. For example, whether
  "funded" means the date the money moved or the date the deal was approved.

## Step 3: Calculate summary statistics
- Total and average loan amount, overall and by market.
- Count of loans funded per day, and the distribution across the period.
- Median alongside the mean, since a few large loans can pull the average up and
  make a typical deal look bigger than it is.
- Compare the current period against the prior one to see whether volume is moving.

## Step 4: Create a visualization
- A line chart of daily funded volume over time, to show the trend and make any
  unusual spikes or gaps obvious.
- A bar chart of total volume by market, sorted, so the largest contributors are
  easy to read.
- Label the axes in plain terms and state the date range on the chart itself, so it
  can be understood without the surrounding explanation.

## Step 5: Interpret results
- Say what the numbers suggest about where volume is concentrated and whether it is
  growing or slowing.
- Note the limits honestly, including what was excluded during cleaning and any
  definition that could reasonably have been set differently.
- Tie the finding back to a decision someone actually makes, since an analysis that
  does not change a decision has not done anything.
