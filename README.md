# TF_motif

[1] Using all sequences.  
[Fly](https://htmlpreview.github.io/?https://github.com/Jiahao-Gao/TF_motif/blob/main/FlySTREME_allPeak.html) or [Worm](https://htmlpreview.github.io/?https://github.com/Jiahao-Gao/TF_motif/blob/main/WormSTREME_allPeak.html)

[2] Using Top250 sequences.  
[Fly](https://htmlpreview.github.io/?https://github.com/Jiahao-Gao/TF_motif/blob/main/FlySTREME_top250.html) or [Worm](https://htmlpreview.github.io/?https://github.com/Jiahao-Gao/TF_motif/blob/main/WormSTREME_top250.html)

[3] Removing HOT sites. Peaks that fall in a cluster with size larger than 277 (fly) or 85 (worm) were removed.  
[Fly](https://htmlpreview.github.io/?https://github.com/Jiahao-Gao/TF_motif/blob/main/FlySTREME_removeHOT_277.html) or [Worm](https://htmlpreview.github.io/?https://github.com/Jiahao-Gao/TF_motif/blob/main/WormSTREME_removeHOT_85.html)

[4] Removing HOT sites (stringent). Similar to [3], but with more stringent threshold (53 for fly and 31 for worm).  
[Fly](https://htmlpreview.github.io/?https://github.com/Jiahao-Gao/TF_motif/blob/main/FlySTREME_removeHOT_53.html) or [Worm](https://htmlpreview.github.io/?https://github.com/Jiahao-Gao/TF_motif/blob/main/WormSTREME_removeHOT_31.html)

[5] Removing HOT sites and singletons. Similar to [3], but further remove peaks that fall in a cluster with size 1 (singletons).  
[Fly](https://htmlpreview.github.io/?https://github.com/Jiahao-Gao/TF_motif/blob/main/FlySTREME_removeHOT_singleton_277.html) or [Worm](https://htmlpreview.github.io/?https://github.com/Jiahao-Gao/TF_motif/blob/main/WormSTREME_removeHOT_singleton_85.html)

[6] Removing HOT sites and singletons (stringent). Similar to [4], but remove singletons as in [5].  
[Fly](https://htmlpreview.github.io/?https://github.com/Jiahao-Gao/TF_motif/blob/main/FlySTREME_removeHOT_singleton_53.html) or [Worm](https://htmlpreview.github.io/?https://github.com/Jiahao-Gao/TF_motif/blob/main/WormSTREME_removeHOT_singleton_31.html)
