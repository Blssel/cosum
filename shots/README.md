Intro
-----

This folder contains the shot indices for the videos complied in [the video co-summaerization paper](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Chu_Video_Co-Summarization_Video_2015_CVPR_paper.pdf).

Description
-----------

Each video is pre-segmented using the approach described in **Sec 3.1** of the paper.  Suppose we have `N` shots for a particular video.  The shot indices are listed in a txt-file that contains `(N+1)` lines.  That is, the `n`-th shot spans between the frame numbers of the `n`-th line and the `(n+1)`-th line.
