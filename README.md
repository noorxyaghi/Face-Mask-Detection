# Real-Time Face-Mask Detector (YOLOv8)

Trains and deploys a YOLOv8-nano model (Ultralytics) to detect
`with_mask`, `without_mask`, `mask_weared_incorrect` in real time.

* **Dataset** – [andrewmvd/Face-Mask-Detection](https://www.kaggle.com/datasets/andrewmvd/face-mask-detection)  
* **Training** – 30 epochs on Kaggle GPU (loss + mAP curves in `docs/results.png`)  
* **mAP@0.5** – 0.78 on held-out test split  
