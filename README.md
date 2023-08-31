# Seq_LANE
This open access dataset is for ASVs free space segmentation, along with our paper work "Temporal Fusion Based Free Space Segmentation
for ASVs".

## Introduction
The data was collected by our unmanned cruise boat ”Xi”, which is equipped with cameras with a resolution of 1920 × 1080. The dataset was collected in varying weather and lighting conditions, including mirrors, dynamic surface textures, cluttered backgrounds, and motion quiver interference. This VOC style dataset contains 10 sequences, which consist of 5530 frames, illustrating sunny daytime, midnight, dusk of Moat River in Xi’an and Yangzhou Slender West Lake are involved. 

This dataset contains 10 sequencens. For each sequences, the detail goes as follows, the MR means Moat River and SWL means Yangzhou Slender West Lake:

| Items| Seq1 | Seq2 | Seq3 | Seq4 | Seq5 | Seq6 | Seq7 | Seq8 | Seq9 | Seq10 |
|----- | ---- |----- | ---- |---- | ---- |----- | ---- |---- | ---- |----- |
| Scenes| SWL | MR | MR | MR | MR | SWL | SWL | SWL | SWL | SWL |
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
The sample of our dataset is as illustrated, aside of different static conditions, the dataset also involved special occasions such as encountering with other boats and floatings.

![]![]![]

## Acknowledgement 
I you think this work helpful, please cite by:

'''
hopefully we can make it :)
'''
