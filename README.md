Single-frame InfraRed Small Target (SIRST) Benchmark
==============

A dataset proposed in "Asymmetric Contextual Modulation for Infrared Small Target Detection" <https://arxiv.org/abs/2009.14530>

**Update**:

- The improved version, SIRST v2, has been released. Please visit <https://github.com/YimianDai/open-sirst-v2> to check the new dataset.
- The name of this dataset series is 'SIRST' and 'SIRST v2'. Please don't call it as 'NUAA-SIRST'.

## Dataset Description

SIRST is a dataset specially constructed for **single-frame** infrared small target detection, in which the images are selected from hundreds of infrared sequences for different scenarios. 

![image](./gallery.png)

![annotation](./annotation.png)

The bounding box and semantic segmentation annotations are available now. The rest annotation forms will come soon.

<div>
<img src=https://raw.githubusercontent.com/YimianDai/imgbed/master/github/sirst/BMFPN_DENTIST_Target_Number.png width=33%>
<img src=https://raw.githubusercontent.com/YimianDai/imgbed/master/github/sirst/BMFPN_DENTIST_Size_Ratios.png width=33%>
<img src=https://raw.githubusercontent.com/YimianDai/imgbed/master/github/sirst/BMFPN_DENTIST_Brightness_Ratios.png width=33%>
</div>

## Learderboard

The full learderboard will come soon. 
A comparison of 19 methods can be found at <https://github.com/YimianDai/open-acm>.

## Toolkit

The full toolkit will come soon. 
Some implementations of our proposed methods can be found at [DENTIST](https://github.com/YimianDai/DENTIST), [ACM](https://github.com/YimianDai/open-acm), and [ALCNet](https://github.com/YimianDai/open-alcnet).

## Citation

Please cite our paper in your publications if our work helps your research. BibTeX reference is as follows.

```
@article{TGRS23OSCAR,
  author    = {{Dai}, Yimian and {Li}, Xiang and {Zhou}, Fei and {Qian}, Yulei and {Chen}, Yaohong and {Yang}, Jian },
  title   = {{One-Stage Cascade Refinement Networks for Infrared Small Target Detection}},
  journal = {IEEE Transactions on Geoscience and Remote Sensing},
  pages   = {1--17},
  year    = {2023},
}

Y Dai, X Li, F Zhou, Y Qian, Y Chen, J Yang
IEEE Transactions on Geoscience and Remote Sensing 61, 1-17

@article{TGRS21ALCNet,
  author    = {{Dai}, Yimian and {Wu}, Yiquan and {Zhou}, Fei and {Barnard}, Kobus},
  title   = {{Attentional Local Contrast Networks for Infrared Small Target Detection}},
  journal = {IEEE Transactions on Geoscience and Remote Sensing},
  pages   = {1--12},
  year    = {2021},
}

@inproceedings{dai21acm,
  title   =  {Asymmetric Contextual Modulation for Infrared Small Target Detection},
  author  =  {Yimian Dai and Yiquan Wu and Fei Zhou and Kobus Barnard},
  booktitle =  {{IEEE} Winter Conference on Applications of Computer Vision, {WACV} 2021}
  year    =  {2021}
}
```

