date:: 12/2020
publisher:: IEEE
place:: "Taipei, Taiwan"
conference-name:: 2020 International Conference on Pervasive Artificial Intelligence (ICPAI)
proceedings-title:: 2020 International Conference on Pervasive Artificial Intelligence (ICPAI)
isbn:: 978-1-66540-483-9
doi:: 10.1109/ICPAI51961.2020.00023
title:: @TrackNetV2: Efficient Shuttlecock Tracking Network
pages:: 86-91
item-type:: [[conferencePaper]]
access-date:: 2023-11-01T06:32:52Z
original-title:: TrackNetV2: Efficient Shuttlecock Tracking Network
language:: en
url:: https://ieeexplore.ieee.org/document/9302757/
short-title:: TrackNetV2
authors:: [[Nien-En Sun]], [[Yu-Ching Lin]], [[Shao-Ping Chuang]], [[Tzu-Han Hsu]], [[Dung-Ru Yu]], [[Ho-Yi Chung]], [[Tsi-Ui Ik]]
library-catalog:: DOI.org (Crossref)
links:: [Local library](zotero://select/library/items/ARPRCS5I), [Web library](https://www.zotero.org/users/12886909/items/ARPRCS5I)

- [[Abstract]]
	- TrackNet, a deep learning network, was proposed to track high-speed and tiny objects such as tennis balls and shuttlecocks from videos. To conquer low image quality issues such as blur, afterimage, and short-term occlusion, some number of consecutive images are input together to detect an ﬂying object. In this work, TrackNetV2 is proposed to improve the performance of TrackNet from various aspects, especially processing speed, prediction accuracy, and GPU memory usage. First of all, the processing speed is improved from 2.6 FPS to 31.8 FPS. The performance boost is achieved by reducing the input image size and re-engineering the network from a Multiple-In Single-Out (MISO) design to a Multiple-In MultipleOut (MIMO) design. Then, to improve the prediction accuracy, a comprehensive dataset from diverse badminton match videos is collected and labeled for training and testing. The dataset consists of 55563 frames from 18 badminton match videos. In addition, the network mechanisms are composed of not only VGG16 and upsampling layers but also U-net. Last, to reduce GPU memory usage, the data structure of the heatmap layer is remodeled from a pixel-wise one-hot encoding 3D array to a real-valued 2D array. To reﬂect the change of the heatmap representation, the loss function is redesigned from a RMSE-based function to a weighted cross-entropy based function. An overall validation shows that the accuracy, precision and recall of TrackNetV2 respectively reach 96.3%, 97.0% and 98.7% in the training phase and 85.2%, 97.2% and 85.4% in a test on a brand new match. The processing speed of the 3-in and 3-out version TrackNetV2 can reach 31.84 FPS. The dataset and source code of this work are available at https://nol.cs.nctu.edu.tw:234/open-source/TrackNetv2/.
- [[Attachments]]
	- [Sun 等 - 2020 - TrackNetV2 Efficient Shuttlecock Tracking Network.pdf](zotero://select/library/items/P42FYMTV) {{zotero-imported-file P42FYMTV, "Sun 等 - 2020 - TrackNetV2 Efficient Shuttlecock Tracking Network.pdf"}}