# Şule Özdamar

Computer Engineering student at İstanbul Arel University. I work on **convolutional neural networks for computer vision** (aerial and thermal imagery, radar target recognition, semantic segmentation and medical imaging for cancer and dementia) and on **data quality and large language models**. My goal is to build AI systems that hold up from data to deployment, with evaluations that measure what they claim to measure. Every project is a tested Python package with continuous integration.

## Projects

| Project | Topic | Tools |
|---|---|---|
| [SAR Target Recognition with CNNs](https://github.com/mahdildarr/sar-target-recognition) | Radar target recognition on MSTAR; A-ConvNet vs ResNet; a shortcut-learning test for background bias | PyTorch · CNN · Grad-CAM |
| [Safe Landing-Zone Detection for UAVs](https://github.com/mahdildarr/uav-safe-landing-segmentation) | U-Net semantic segmentation of drone imagery and a rule-based landing-zone search; ONNX / INT8 deployment | PyTorch · U-Net · ONNX Runtime |
| [Breast-Cancer Metastasis Detection Across Hospitals](https://github.com/mahdildarr/pathology-domain-shift) | Histopathology on Camelyon17-WILDS: unseen-hospital generalisation, stain normalisation vs augmentation, calibration | PyTorch · DenseNet · ResNet |
| [Does the Melanoma Classifier Look at the Lesion?](https://github.com/mahdildarr/melanoma-shortcut-analysis) | HAM10000: lesion-level evaluation, lesion-masking shortcut tests, acquisition bias | PyTorch · ResNet · Grad-CAM |
| [Small Object Detection and Tracking in UAV Imagery](https://github.com/mahdildarr/uav-small-object-detection) | Small object detection on VisDrone: sliced vs standard inference with COCO AP by object size and bootstrap intervals; ByteTrack scored with the VisDrone-MOT protocol | PyTorch · YOLO · SAHI · ByteTrack |
| [Person and Vehicle Detection in Thermal UAV Imagery](https://github.com/mahdildarr/thermal-detection-hituav) | Detection on HIT-UAV thermal data: the visible-to-thermal domain gap and errors by altitude, camera angle and time of day | PyTorch · YOLO · OpenCV |
| [Subject-Level Evaluation for Alzheimer's MRI](https://github.com/mahdildarr/alzheimer-mri) | Measuring data leakage: slice- vs subject-level splits, subject-level cross-validation, a permuted-label leakage probe; Grad-CAM | PyTorch · ResNet · Grad-CAM |
| [Label Quality Analysis for Object Detection](https://github.com/mahdildarr/label-quality-analysis) | Finding label errors, measured against injected errors on a leakage-free VOC benchmark: why default cleanlab is blind to YOLO's confidence scale, and box-level evaluation | cleanlab · PyTorch · YOLO |
| [Bilge · Turkish AI Assistant](https://github.com/mahdildarr/bilge) | Fine-tuning an open LLM on Turkish instructions with QLoRA: data cleaning and decontamination, answer-language and knowledge-retention evaluation; chat interface | Transformers · PEFT · Gradio |

## Other work

- **Alzheimer's MRI research**: within a TÜBİTAK 1005 project proposal, together with Assoc. Prof. Pınar Karadayı Ataş
- **MİL-SYNTH**: AI and synthetic data for the defense industry · TÜBİTAK BiGG DeepCube program
- **AVD Teknoloji**: AI training work on large language models
- **Merkütech Rocket Team**: avionics and AI

## Tech stack

Python · PyTorch · TensorFlow · Hugging Face · Ultralytics YOLO · OpenCV · ONNX Runtime · ROS 2 · PX4 · Docker · Linux · Git

## Contact

suleozdamar32@gmail.com
