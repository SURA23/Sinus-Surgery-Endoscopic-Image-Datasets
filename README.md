# UW Sinus Surgery Cadaver/Live (UW-Sinus-Surgery-C/L) Dataset
Novel image segmentation datasets collected from endoscopic videos of sinus surgery processes

**Introduction**

This dataset was developed at the University of Washington's BioRobotics Lab (http://brl.ee.washington.edu). It has endoscopic sinus surgery images with manual annotations for surgical instrument segmentation task. The images were extracted from 10 cadaveric surgery videos and 3 live surgery videos. The challenging conditions of this dataset include specular reflections, blur from motion, blood, smoke and tools in shadow.

Examples of cadaveric surgery image:
![](https://github.com/SURA23/Sinus-Surgery-Endoscopic-Image-Datasets/blob/master/cadaver-example1.jpg)![](https://github.com/SURA23/Sinus-Surgery-Endoscopic-Image-Datasets/blob/master/cadaver-example2.jpg)

Examples of live surgery images:
![](https://github.com/SURA23/Sinus-Surgery-Endoscopic-Image-Datasets/blob/master/live-example1.jpg)![](https://github.com/SURA23/Sinus-Surgery-Endoscopic-Image-Datasets/blob/master/live-example2.jpg)

**Download** The dataset could be downloaded from http://hdl.handle.net/1773/45396.

**How to use the dataset?**

The dataset is arranged as follows:
|--- readme.txt
|--- cadaver
|     |---images
|     |---labels
|     
|—— live
      |---images
      |---labels
UW-Sinus-Surgery-C/L consists of two datasets: cadaver dataset (UW-Sinus-Surgery-C) and live dataset (UW-Sinus-Surgery-L). In each dataset, folder "images" has surgery images and folder "labels" has segmentation masks of the corresponding surgery images. The segmentation ground truths are given by images whose pixel values indicate the class index. Here 0 stands for background and 1 for surgical instrument.

**Contact** Shan Lin (shanl3@uw.edu), Fangbo Qin (fbqin@uw.edu)

If you find this dataset helpful in your research, please cite our papers [1] and [2]. For any suggestions or corrections, please contact us at shanl3@uw.edu or fbqin@uw.edu. 

Note: This dataset is slightly different from the one used in papers [1] and [2] as further refinements on the annotations were made.

**References**
[1] S. Lin, F. Qin, Y. Li, et al., “LC-GAN: Image-to-image translation based on generative adversarial network for endoscopic images,” arXiv preprint arXiv:2003.04949, 2020.
[2] F. Qin, S. Lin, Y. Li, et al., “Towards better surgical instrument segmentation in endoscopic vision: multi-angle feature aggregation and contour supervision,” arXiv preprint arXiv:2002.10675, 2020.

BibTeX:
[1]
@article{lin2020lc,
  title={LC-GAN: Image-to-image Translation Based on Generative Adversarial Network for Endoscopic Images},
  author={Lin, Shan and Qin, Fangbo and Li, Yangming and Bly, Randall A and Moe, Kris S and Hannaford, Blake},
  journal={arXiv preprint arXiv:2003.04949},
  year={2020}
}
[2] 
@article{qin2020towards,
  title={Towards Better Surgical Instrument Segmentation in Endoscopic Vision: Multi-Angle Feature Aggregation and Contour Supervision},
  author={Qin, Fangbo and Lin, Shan and Li, Yangming and Bly, Randall A and Moe, Kris S and Hannaford, Blake},
  journal={arXiv preprint arXiv:2002.10675},
  year={2020}
}

**Acknowledgement**
