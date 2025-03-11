Video-based Person Re-Identification (Re-ID) is the task of matching individuals across multiple non-overlapping camera views in video surveillance. Unlike image-based Re-ID, which relies on single-frame person images, video-based Re-ID leverages temporal information from sequences of frames, making it more robust to occlusions, pose variations, and background clutter.

Dataset Used-
1. iLIDS-VID
2. KENSINGTON_HIGH_STREET

Model Used in this Project-
In this project, you have utilized Swin Transformer and ResNet-50 models for feature extraction in video-based person Re-ID.

1. Swin Transformer:
 A hierarchical vision transformer that efficiently captures global and local features using shifted window attention.
 Provides better contextual understanding and robustness to occlusions and pose variations.
 Well-suited for handling long-term dependencies in video sequences.


Output-

iLIDS-VID Dataset-
![image alt](https://github.com/Gauravsingh564/Video_Based_Person_Re-ID/blob/main/ILIDS_Dataset.png?raw=true)

KENSINGTON_HIGH_STREET Dataset-

![image alt](https://github.com/Gauravsingh564/Video_Based_Person_Re-ID/blob/main/KENSINGTON_HIGH_STREET.png?raw=true)

2. ResNet-50:
A deep convolutional neural network (CNN) with residual connections, enabling efficient gradient flow and improved training stability.
Extracts low-level textures and high-level semantic features for person representation.
Works well for frame-wise feature extraction in video-based Re-ID.


Output-

iLIDS-VID Dataset-
![image alt](https://github.com/Gauravsingh564/Video_Based_Person_Re-ID/blob/main/ILIDS_Dataset.png?raw=true)

KENSINGTON_HIGH_STREET Dataset-

![image alt](https://github.com/Gauravsingh564/Video_Based_Person_Re-ID/blob/main/KENSINGTON_HIGH_STREET.png?raw=true)

By combining Swin Transformer’s global feature modeling and ResNet-50’s strong CNN-based representations, your approach enhances discriminative feature learning, improving robustness to challenges like background clutter and occlusions.




