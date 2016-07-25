Intro
-----

This folder contains the annotations for the **query-specific video summarization** experiments performed in Sec 4.1 of [the video co-summaerization paper](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Chu_Video_Co-Summarization_Video_2015_CVPR_paper.pdf).

Description
-----------

Each video is annotated with three judges.  Each judge was given the query term (eg, Surfing), and asked to select at least 10%, but no more than 50%, of shots that they feel relevant to the query string for each video.  The ground truth annotations were constructed by collecting the shots that are selected by at least two judges.

Each file contains a matrix of two columns.  The first column indicates the shot indices that are selected by different judges.  The second column indicates user's annotations, which are all ones in this version.  Please refer to the `../shot/` directory for the mapping between shots and frame indices.
