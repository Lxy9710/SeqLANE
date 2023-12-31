# Seq_LANE
This open access dataset is publicly available [here](https://drive.google.com/file/d/1b9LX9nDxuBloGgJruVAqEoGDccvBi_aZ/view?usp=drive_link) for ASVs free space segmentation, along with our paper work "Visual Temporal Fusion Based Free Space Segmentation
for Autonomous Surface Vessels". 

## Introduction
The data was collected by our ASV ”Xi”, which is equipped with cameras with a resolution of 640 × 480. The dataset was collected in varying weather and lighting conditions, including mirrors, dynamic surface textures, cluttered backgrounds, and motion quiver interference. This VOC style dataset contains 10 sequences, which consist of 5530 frames, illustrating sunny daytime, midnight, dusk of inland rivers and lakes are involved. 

This dataset contains 10 sequencens. For each sequences, the detail goes as follows, the R means Rivers and L means Lakes:

| Items| Seq1 | Seq2 | Seq3 | Seq4 | Seq5 | Seq6 | Seq7 | Seq8 | Seq9 | Seq10 |
|----- | ---- |----- | ---- |---- | ---- |----- | ---- |---- | ---- |----- |
| Scenes| L | R | R | R | R | L | L | L | L | L |
| Time | dusk | morning | noon | evening | noon | mignight | afternoon | afternoon | dusk | dusk |
| Weather | cloudy | cloudy | sunny | night | sunny | foggy | sunny | cloudy | sunny | sunny |
| Duration/s | 33 | 72 | 197 | 38 | 40 | 151 | 79 | 33 | 39 | 09 |
| Frames | 266 | 579 | 1578 | 309 | 323 | 1211 | 633 | 271 | 313 | 47 |

## How to use

The dataset is made into VOC style, and is clustered to training, validation and test by 6:2:2. If you need to utilize the data with temporal sequence, the annotation is made so. You can also shuffle the data for single frame or image learning.

- SEQ1
  - ImageSets
    - Segmentation
      - seq1_test.txt
      - seq1_val.txt
      - seq1_train.txt

  - JPEGImages
    - seq1_0000.jpg
    - seq1_0001.jpg
...

  - SegmentationClass
    - seq1_0000.png
    - seq1_0001.png

 - SEQ2
   - ImageSets
   - JPEGImages
   - SegmentationClass

...

 - SEQ10
...

## Datasample
The sample of our dataset is as illustrated, aside of different static conditions, the dataset also involved special occasions such as encountering with other boats, floatings.

<img src="https://github.com/Lxy9710/Seq_LANE/blob/main/gif1.gif" width="200"/><img src="https://github.com/Lxy9710/Seq_LANE/blob/main/gif2.gif" width="200"/><img src="https://github.com/Lxy9710/Seq_LANE/blob/main/gif3.gif" width="200"/>
</figure>


## Acknowledgement 
I you think this work helpful, please cite by:

```

hopefully we can make it :)

```
