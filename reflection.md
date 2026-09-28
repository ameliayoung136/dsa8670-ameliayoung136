# Week 5 Reflection

The thing that stuck with me from the readings is the difference between Git and
GitHub, which I had mixed together before. Git is the version control system and it
runs locally on my own machine, which is why I can commit without being online.
GitHub is the hosting and collaboration layer on top of it, and things like pull
requests and Issues are GitHub features, not Git ones. That also explained why some
of this work happens in GitHub Desktop and some of it only happens on the website.

My challenge this week was with pull requests. I published my `update-bio` branch
from GitHub Desktop and used the Preview Pull Request option, and I assumed that had
created the PR. It hadn't. Preview only shows you the diff before you propose
anything. So when I switched back to `main` and tried to pull, the button just said
Fetch origin and nothing came down, because the branch was never merged and `main`
had not actually changed. Once I went to the Pull requests tab on GitHub.com,
created the PR properly, and merged it, the button switched to Pull origin and my
local `main` caught up. The lesson was that pushing a branch and merging a branch
are two separate things, and my local copy does not know about anything until I pull.

For team projects, the part I can see mattering most is that branches let several
people work at the same time without overwriting each other. Everyone works on their
own branch and `main` stays in a working state until changes are reviewed. The pull
request is where that review happens, and because the discussion stays attached to
the code, you can go back later and see why a change was made instead of guessing.
For analytics work specifically, that matters when someone questions a number months
after the fact.