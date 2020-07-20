# Sinus-Surgery-Endoscopic-Image-Datasets
Novel image segmentation datasets collected from endoscopic videos of sinus surgery processes

**Examples**

![](https://github.com/SURA23/Sinus-Surgery-Endoscopic-Image-Datasets/blob/master/live-example1.jpg)![](https://github.com/SURA23/Sinus-Surgery-Endoscopic-Image-Datasets/blob/master/live-example2.jpg)


![](https://github.com/SURA23/Sinus-Surgery-Endoscopic-Image-Datasets/blob/master/cadaver-example1.jpg)![](https://github.com/SURA23/Sinus-Surgery-Endoscopic-Image-Datasets/blob/master/cadaver-example2.jpg)



**UW Sinus Surgery Cadaver/Live (UW-Sinus-Surgery-C/L) Dataset:**

Link: https://digital.lib.washington.edu/researchworks/handle/1773/45396

This dataset was developed at the University of Washington's BioRobotics Lab (http://brl.ee.washington.edu). It has endoscopic sinus surgery images with manual annotations for surgical instrument segmentation task. **The dataset was collected from endoscopic sinus surgeries performed by surgeons, which are featured by dexterous tip motion, narrow operation space and close lens-object distance.** More details can be found in the references [1,2].


UW-Sinus-Surgery-C/L consists of two sub-datasets: cadaver surgery dataset (UW-Sinus-Surgery-C) and live surgery dataset (UW-Sinus-Surgery-L). In each dataset, the folder "images" has endoscopic images and the folder "labels" has the segmentation ground truths (0 stands for background and 1 for surgical instrument)

The dataset folder is arranged as follows:

|--- readme.txt

|--- cadaver

      |---images

      |---labels

|    

|—— live

      |---images

      |---labels

Image naming:

i) Sinus-Surgery-C dataset: S[video_ID]_[frame_index]

ii) Sinus-Surgery-L dataset: L[video_ID]_[frame_index]

[video_ID] shows from which video the image was extracted, [frame_index] is the frame's index in the corresponding video.


**3-fold cross-validation experimental setup:**

In [2], the image segmentation performances were evaluated based on K-fold cross-validation method, to avoid the bias caused by dataset split. The 3-fold crossvalidation is conducted with the setup below: 

i) Sinus-Surgery-C dataset: fold 1: 1st~4th videos; fold 2: 5th-7th videos; fold 3: 8th-10th videos

ii) Sinus-Surgery-L dataset: fold 1: 1st video; fold 2: 2nd video; fold 3: 3rd video

If you are trying to follow the experiments in [2], please contact {fbqin '_at_' uw.edu} or {qinfangbo2013 '_at_' ia.ac.cn} to request the datasets which had already been organized to 3-fold.

**Contact**

Emails via {shanl3 '_at_'uw.edu; fbqin '_at_' uw.edu; qinfangbo2013 '_at_' ia.ac.cn}

For any suggestions or corrections, please contact us. 
If you find this dataset helpful in your research, please cite our papers [1] and [2]. 

**References**

[1] S. Lin, F. Qin, et al., “LC-GAN: Image-to-image translation based on generative adversarial network for endoscopic images,” arXiv preprint arXiv:2003.04949, 2020. (accepted by IROS 2020)

[2] F. Qin, S. Lin, et al., “Towards better surgical instrument segmentation in endoscopic vision: multi-angle feature aggregation and contour supervision,”  IEEE Robotics and Automation Letters, 2020 (IROS2020 presentation), https://ieeexplore.ieee.org/document/9140341

[3] S. Lin, F. Qin, R. A. Bly, et al., "Automatic Sinus Surgery Skill Assessment Based on Instrument Segmentation and Tracking in Endoscopic Video," in Proc. Int. Workshop Multiscale Multimodal Med. Imag., pp.93-100, 2019.

[4] S. Lin, X. Gu, R. A. Bly, et al., "Video-based automatic and objective endoscopic sinus surgery skill assessment," in Medical Imaging 2020: Image-Guided Procedures, Robotic Interventions, and Modeling., vol. 11315, p. 113152L, 2020. 


