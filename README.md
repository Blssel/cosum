#Preview

The 10 categories collected in this dataset:

![](teaser/im_dataset.png)

#Descrptions

This Co-Sum dataset serves as a benchmark to validate *video co-summarization* techniques, where the goal is to create video summaries given a video collection of the same topic. The dataset is collected from YouTube using 10 queries, in total 51 videos of 147m40s. We release the video URLs, proprocessed shot indices and annotations for reproducibility of our results. 

This dataset has been evaluated on two tasks:
- **Adaptive video summarization:** Create summaries for each video adaptive to a query string
- **Concept visualization:** Generate visual (video) concepts from a query string (eg, "*surf*" and "*bike polo*")
![](teaser/surf.gif)
![](teaser/bike.gif)

More info:
- **Links:** [project page](http://ochoa.pc.cs.cmu.edu/wschu/project_cosum.html) | 
[evaluation page](http://ochoa.pc.cs.cmu.edu/wschu/cosum/) | 
[paper](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Chu_Video_Co-Summarization_Video_2015_CVPR_paper.pdf) (2.3M) | 
[poster](http://ochoa.pc.cs.cmu.edu/wschu/papers/doc/cvpr15_cosum_poster_low.pdf) (14M) | 
[slides](http://ochoa.pc.cs.cmu.edu/wschu/papers/doc/cvpr15_cosum_slides_low.pdf) (5.6M) | 
[supp](http://ochoa.pc.cs.cmu.edu/wschu/papers/doc/cvpr15-cosum-supp.pdf) (12M)
- **Contact:** Please send comments to Wen-Sheng Chu (wschu@cmu.edu)
- **Citation:** Please cite the following paper if you use this dataset in a publication:
```
@inproceedings{chu2015video,
    title={Video co-summarization: Video summarization by visual co-occurrence},
    author={Chu, Wen-Sheng and Song, Yale and Jaimes, Alejandro},
    booktitle={CVPR},
    year={2015}
}
```

#Shot Indices

The shot indices used in the paper can be found in the `shots/` directory.
Note that the indices can be post-processed into smaller shots to avoid too lengthy shots (see Sec 3.1 in paper).


#Video URLs

**01: Base jump**

[![base1](http://img.youtube.com/vi/iD4qsWnjsNU/0.jpg)](http://www.youtube.com/watch?v=iD4qsWnjsNU)
[![base2](http://img.youtube.com/vi/iMCcnA9ifqg/0.jpg)](http://www.youtube.com/watch?v=iMCcnA9ifqg)
[![base3](http://img.youtube.com/vi/hdGi6Bt5r6g/0.jpg)](http://www.youtube.com/watch?v=hdGi6Bt5r6g)
[![base4](http://img.youtube.com/vi/iqZUoZpRv3A/0.jpg)](http://www.youtube.com/watch?v=iqZUoZpRv3A)
[![base4](http://img.youtube.com/vi/uAfYbzL90Mo/0.jpg)](http://www.youtube.com/watch?v=uAfYbzL90Mo)

-----------------------------
**02: Bike polo**

[![bike1](http://img.youtube.com/vi/MxdoepwKttY/0.jpg)](http://www.youtube.com/watch?v=MxdoepwKttY)
[![bike2](http://img.youtube.com/vi/Gc8-RMWZ99o/0.jpg)](http://www.youtube.com/watch?v=Gc8-RMWZ99o)
[![bike3](http://img.youtube.com/vi/sUji156WbuM/0.jpg)](http://www.youtube.com/watch?v=sUji156WbuM)
[![bike4](http://img.youtube.com/vi/VV18GUOcTps/0.jpg)](http://www.youtube.com/watch?v=VV18GUOcTps)
[![bike5](http://img.youtube.com/vi/7axu6Ndocfo/0.jpg)](http://www.youtube.com/watch?v=7axu6Ndocfo)

-----------------------------
**03: Eiffel tower**

[![eiffel1](http://img.youtube.com/vi/dRjHJCbKWQA/0.jpg)](http://www.youtube.com/watch?v=dRjHJCbKWQA)
[![eiffel2](http://img.youtube.com/vi/Xvrzfkb6AD8/0.jpg)](http://tune.pk/video/4434726/eiffel-tower-paris-france)
[![eiffel3](http://img.youtube.com/vi/cB9ZOaPKPCw/0.jpg)](http://www.youtube.com/watch?v=cB9ZOaPKPCw)
[![eiffel4](http://img.youtube.com/vi/S1bkBxR-I5A/0.jpg)](http://www.youtube.com/watch?v=S1bkBxR-I5A)
[![eiffel5](http://img.youtube.com/vi/9W8qkf96Hp8/0.jpg)](http://www.youtube.com/watch?v=9W8qkf96Hp8)
[![eiffel6](http://img.youtube.com/vi/zAZHQUOgnFE/0.jpg)](http://www.youtube.com/watch?v=zAZHQUOgnFE)
[![eiffel7](http://img.youtube.com/vi/tv5fKAFdykM/0.jpg)](http://www.youtube.com/watch?v=tv5fKAFdykM)

-----------------------------
**04: Excavators river cross**

[![exc1](http://img.youtube.com/vi/V6zayRd0Vw/0.jpg)](http://www.youtube.com/watch?v=V6zayRd0Vw)
[![exc2](http://img.youtube.com/vi/zJM8KS4B3EU/0.jpg)](http://www.youtube.com/watch?v=zJM8KS4B3EU)
[![exc3](http://img.youtube.com/vi/G4NqTH6xDTg/0.jpg)](http://www.youtube.com/watch?v=G4NqTH6xDTg)

-----------------------------
**05: Kids play in leaves**

[![kid1](http://img.youtube.com/vi/jaXcwfsfAhk/0.jpg)](http://www.youtube.com/watch?v=jaXcwfsfAhk)
[![kid2](http://img.youtube.com/vi/2PaYyXwUN40/0.jpg)](http://www.youtube.com/watch?v=2PaYyXwUN40)
[![kid3](http://img.youtube.com/vi/uBYAhZtRFj0/0.jpg)](http://www.youtube.com/watch?v=uBYAhZtRFj0)
[![kid4](http://img.youtube.com/vi/jaXcwfsfAhk/0.jpg)](http://www.youtube.com/watch?v=jaXcwfsfAhk)
[![kid5](http://img.youtube.com/vi/_4PxXDglJYI/0.jpg)](http://www.youtube.com/watch?v=_4PxXDglJYI)
[![kid6](http://img.youtube.com/vi/Zw2CxfFaiRI/0.jpg)](http://www.youtube.com/watch?v=Zw2CxfFaiRI)

-----------------------------
**06: MLB**

[![mlb1](http://img.youtube.com/vi/ghtNQgSdSjU/0.jpg)](http://www.youtube.com/watch?v=ghtNQgSdSjU)
[![mlb2](http://img.youtube.com/vi/40v3Wxla_YQ/0.jpg)](http://www.youtube.com/watch?v=40v3Wxla_YQ)
[![mlb3](http://img.youtube.com/vi/a3lUwwZH1-s/0.jpg)](http://www.youtube.com/watch?v=a3lUwwZH1-s)
[![mlb4](http://img.youtube.com/vi/40ZbleWCCC8/0.jpg)](http://www.youtube.com/watch?v=40ZbleWCCC8)
[![mlb5](http://img.youtube.com/vi/T3mWQF7CHpY/0.jpg)](http://www.youtube.com/watch?v=T3mWQF7CHpY)
[![mlb6](http://img.youtube.com/vi/u-IcI51WxTA/0.jpg)](http://www.youtube.com/watch?v=u-IcI51WxTA)

-----------------------------
**07: NFL**

[![nfl1](http://img.youtube.com/vi/mBEb4LOAJ1s/0.jpg)](http://www.youtube.com/watch?v=mBEb4LOAJ1s)
[![nfl2](http://img.youtube.com/vi/8OeNn4Zu6rI/0.jpg)](http://www.youtube.com/watch?v=8OeNn4Zu6rI)
[![nfl3](http://img.youtube.com/vi/sdmu-WVZe70/0.jpg)](http://www.youtube.com/watch?v=sdmu-WVZe70)

-----------------------------
**08: Notre dame cathedral**

[![notre1](http://img.youtube.com/vi/1Wfs2Pi2_tA/0.jpg)](http://www.youtube.com/watch?v=1Wfs2Pi2_tA)
[![notre2](http://img.youtube.com/vi/3JrzPSNmT8E/0.jpg)](http://www.youtube.com/watch?v=3JrzPSNmT8E)
[![notre3](http://img.youtube.com/vi/Dzqyip0pbw0/0.jpg)](http://www.youtube.com/watch?v=Dzqyip0pbw0)
[![notre4](http://img.youtube.com/vi/fpWwESIbgqA/0.jpg)](http://www.youtube.com/watch?v=fpWwESIbgqA)
[![notre5](http://img.youtube.com/vi/wU6TfFTxQDE/0.jpg)](http://www.youtube.com/watch?v=wU6TfFTxQDE)

-----------------------------
**09: Statue of liberty**

[![statue1](http://img.youtube.com/vi/1Wfs2Pi2_tA/0.jpg)](http://www.youtube.com/watch?v=1Wfs2Pi2_tA)
[![statue2](http://img.youtube.com/vi/muP0gvylsRM/0.jpg)](http://www.youtube.com/watch?v=muP0gvylsRM)
[![statue3](http://img.youtube.com/vi/4g8T07365oQ/0.jpg)](http://www.youtube.com/watch?v=4g8T07365oQ)
[![statue4](http://img.youtube.com/vi/onY6D1YsGcg/0.jpg)](http://www.youtube.com/watch?v=onY6D1YsGcg)
[![statue5](http://img.youtube.com/vi/5CRXa52cPjA/0.jpg)](http://www.youtube.com/watch?v=5CRXa52cPjA)

-----------------------------
**10: Surf**

[![surf1](http://img.youtube.com/vi/5KtMiLDd7Wo/0.jpg)](http://www.youtube.com/watch?v=5KtMiLDd7Wo)
[![surf2](http://img.youtube.com/vi/Z32qL2MRkJM/0.jpg)](http://www.youtube.com/watch?v=Z32qL2MRkJM)
[![surf3](http://img.youtube.com/vi/7RYzCWWZpBA/0.jpg)](http://www.youtube.com/watch?v=7RYzCWWZpBA)
[![surf4](http://img.youtube.com/vi/HGjky5U64LM/0.jpg)](http://www.youtube.com/watch?v=HGjky5U64LM)
[![surf5](http://img.youtube.com/vi/WF1GZVlQ0t8/0.jpg)](http://www.youtube.com/watch?v=WF1GZVlQ0t8)
[![surf6](http://img.youtube.com/vi/a3T3KdTWTwU/0.jpg)](http://www.youtube.com/watch?v=a3T3KdTWTwU)
