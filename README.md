# MambaRGS
This repository provides supplementary materials for our IEEE RA-L submission:

**MambaRGS: Efficient Referring Grasp Synthesis via Text-Image Cross-State Modulation and Rotation-Aware Decoding**

MambaRGS is a Mamba-based framework for **referring grasp synthesis**, which jointly performs language-guided object grounding and planar grasp prediction in cluttered robotic scenes. The proposed framework introduces a **Text-Image Cross-State Modulation (TICM)** module for fine-grained multi-modal interaction and a **Rotation-Aware Decoder (RAD)** for orientation-sensitive grasp prediction.

![MambaRGS Framework](./frame.png)

## Supplementary Materials

Due to the strict 8-page limit of IEEE RA-L, additional details that could not be included in the revised manuscript are provided in the supplementary appendix.

* [Supplementary Appendix](./Appendix.pdf)


## GraspNet-VLG

We construct **GraspNet-VLG**, a real-world referring grasp synthesis benchmark built upon GraspNet-1Billion. It associates cluttered RGB-D scenes with:

* natural language referring expressions;
* pixel-wise target object masks;
* planar grasp annotations for referred objects.

The corrected GraspNet-VLG benchmark contains:

* 2,500 RGB-D images;
* 17,813 image-target-mask samples;
* 106K referring expressions;
* 87 valid object categories;
* 163,466 valid grasp rectangles.

The dataset split follows an image-disjoint 70/10/20 train/validation/test protocol to avoid image-level leakage.

Dataset release information will be updated in this repository.


## License

This repository is released under the Apache-2.0 License.
