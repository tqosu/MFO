# A Dataset for Semantic and Instance Segmentation of Modern Fruit Orchards ([CVPRW'25 V4A](https://www.agriculture-vision.com/))

[Tieqiao Wang](https://web.engr.oregonstate.edu/~wangtie), [Abhinav Jain](https://web.engr.oregonstate.edu/~jainab/), [Liqiang He](https://helq2612.github.io/), [Cindy Grimm](https://web.engr.oregonstate.edu/~grimmc/), [Sinisa Todorovic](https://web.engr.oregonstate.edu/~sinisa/)

This repository contains the code, models, and dataset for the paper. All resources will be made available soon—stay tuned for updates!


## 🌳 Dataset

### 🌲 Real-World Data
#### [**UFO Cherries**](https://oregonstate.box.com/s/krarnn9v3exzqg2f7w1gj6xhnfycww1r) -- 132 videos collected in 4 settings.
- **Cherry\_UFO\_1 (December 2021)** :  Recorded with a handheld cellphone (no depth sensing) at 1080×1920 resolution under overcast conditions. The camera moved in a rectangular pattern close to the tree. This subset comprises 3 videos, totaling 50 seconds or 1500 frames.
- **Cherry_UFO_2 (January 2022)**: Recorded with a handheld Intel RealSense D435 (depth sensing) at 1920×1080 under mixed sunny/cloudy conditions. Camera moved vertically close to the tree. 95 videos, 348 seconds, 10,440 frames.
- **Cherry_UFO_3 (March 2022)**: Recorded with a handheld Intel RealSense D415 (depth sensing) at 1280×720 under sunny conditions. Camera moved randomly close to the tree. 20 videos, 107 seconds, 3210 frames.
- **Cherry_UFO_4 (January 2023)**: Recorded with a handheld Azure Kinect DK (depth sensing) at 1920×1080 under overcast conditions. Camera moved horizontally farther from the tree. 14 videos, 1787 seconds, 53,610 frames.

#### [**Envy Apples**](https://oregonstate.box.com/s/0ulhgjkpk6y6yxsdbfmyeod9kfqafyd6)  -- 91 videos collected in 3 settings.
- **Envy_V_Trellis_1 (January 2022)**: Recorded with a handheld Intel RealSense D435 (depth sensing) at 480×640 under overcast conditions. Camera moved randomly close to the tree. 12 videos, 55 seconds, 1,650 frames.

- **Envy_V_Trellis_2 (January 2023)**: Recorded with a robot-mounted Azure Kinect DK (depth sensing) at 1920×1080 under cloudy/overcast conditions. Camera moved horizontally and vertically at a far distance from the tree. 71 videos, 2,511 seconds, 75,330 frames.

- **Envy_V_Trellis_3 (January 2024)**: Recorded with a robot-mounted Intel RealSense D435 (depth sensing) at 424×240 under cloudy/overcast conditions. Camera moved in an S-shaped pattern, both close to and far from the tree. 8 videos, 483 seconds, 14,490 frames.

<div align="center">
  <img src="https://github.com/tqosu/MFO/blob/main/image/real_data.png" width="100%" height="100%"/>
</div><br/>

### 🎄 Synthetic Data

-  [**Datasets**](https://oregonstate.box.com/s/gbl135jvw8gched92ygx2rhzdvz0hgur): Created UFO-synthetic and Envy-synthetic datasets, each containing 5,000 independent RGB images with corresponding labels and depth images. These datasets can be expanded indefinitely due to their synthetic nature.
-  [**Tree Meshes**](https://oregonstate.box.com/s/mcpzd0eamskyg06q1fnky8dncswycpq6): Released the 3D tree mesh models used to generate these synthetic datasets.

<div align="center">
  <img src="https://github.com/tqosu/MFO/blob/main/image/synth_data1.png" width="100%" height="100%"/>
</div><br/>