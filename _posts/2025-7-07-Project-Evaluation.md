---
layout: post
title: OpenSSF Project Evaluation
---

During our lab, we spent time exploring both large and small open-source projects to get a feel for how different communities work. One of the smaller projects I looked into was OpenSSF Scorecard. This tool is part of the Open Source Security Foundation and its main goal is to help users quickly figure out whether an open-source project is secure. It does that by running automated checks and giving the project a security “score.” That score is based on how well the project follows best practices, like keeping dependencies up to date or protecting important branches.

There are about 170 contributors listed on the GitHub page, but only a handful have been active in the past month. In the last 30 days, there were just four contributors and 15 commits. That told me the project is still being maintained, but not as actively as larger ones like p5.js. Some issues have gone unanswered for a while and are even marked “stale,” which can be discouraging if you are trying to contribute something new.

If I were to get involved, I’d start on the project’s GitHub page and read through the README file. There’s a helpful “Contribute” section that explains how to set up the tool, how to make changes, and how to submit them. There’s also solid documentation on how to install the tool and run the checks. I found that especially helpful as it walks you through how the Scorecard works and how to get the most out of it.
Bugs and feature requests are tracked through the Issues tab on GitHub. Right now, there are around 355 open issues, and I noticed a good number of them are being discussed by both contributors and maintainers. It seems like the project team is active in reviewing issues, even if not all of them get resolved quickly.

As for installation, the whole process should take less than 10 minutes. The download size is small (about 20 MB) and as long as Go is installed, setup is straightforward.

Developer communication mostly happens through Slack, specifically in the #scorecard channel. I also came across Zoom meeting links and developer forums where updates and discussions take place

The most interesting part of this whole exercise was realizing how tools like Scorecard can automate checking if a project is following secure practices. I did not expect something so technical to be so clearly organized and easy to understand. It really helped me see how security can be built into the development process from the start.

