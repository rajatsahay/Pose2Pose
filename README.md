# Pose2Pose
Full Body Deepfakes <br>
Everybody Dance Now: https://arxiv.org/pdf/1808.07371.pdf <br>
If you find this implementation useful, please consider citing the original paper:
```
@article{DBLP:journals/corr/abs-1808-07371,
  author    = {Caroline Chan and
               Shiry Ginosar and
               Tinghui Zhou and
               Alexei A. Efros},
  title     = {Everybody Dance Now},
  journal   = {CoRR},
  volume    = {abs/1808.07371},
  year      = {2018},
  url       = {http://arxiv.org/abs/1808.07371},
  archivePrefix = {arXiv},
  eprint    = {1808.07371},
  timestamp = {Sun, 02 Sep 2018 15:01:55 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1808-07371.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```
This is an implementation of _Chan et al's_ paper, which uses a pix2pix-based method to transfer poses from a source to a generated image.<br>
Here are some preleminary results of the paper that I was able to replicate
![Pose Transfer](https://github.com/rajatsahay/Pose2Pose/blob/master/assets/PoseGraph.PNG)
<br><br>
I was also able to achieve a viable loss for the generator and the discriminator networks sampled here:
![Pose Transfer](https://github.com/rajatsahay/Pose2Pose/blob/master/assets/GenDisLoss.PNG)
