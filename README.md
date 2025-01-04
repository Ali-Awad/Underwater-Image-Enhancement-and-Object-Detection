# Underwater-Image-Enhancement-and-Object-Detection
Understanding the Influence of Image Enhancement on Underwater Object Detection: A Quantitative and Qualitative Study

**Abstract:** Underwater image enhancement is often perceived as a disadvantageous process to object detection. We propose a novel analysis of the interactions between enhancement and detection elaborating on the potential of enhancement to improve detection. In particular, we evaluate object detection performance for each individual image, rather than across the entire set to allow a direct performance comparison of each image before and after enhancement. This approach enables the generation of unique queries to identify the outperforming and underperforming enhanced images compared to the original images. To accomplish this, we first produce enhanced image sets of the original images using recent image enhancement models. Each enhanced set is then divided into two groups: 1) images that outperform or match the performance of the original images, and 2) images that underperform. Subsequently, we create mixed original-enhanced sets by replacing underperforming enhanced images with their corresponding original images. Next, we conduct a detailed analysis by evaluating all generated groups for quality and detection performance attributes. Finally, we perform an overlap analysis between the generated enhanced sets to identify cases where the enhanced images of different enhancement algorithms unanimously outperform, equally perform, or underperform the original images. Our analysis reveals that, when evaluated individually, most enhanced images achieve equal or superior performance compared to their original counterparts. The proposed method uncovers variations in detection performance that are not apparent in a whole-set evaluation, as the overall analysis indicates a negative impact of enhancement on object detection. We also find that over-enhancement may lead to a deteriorated object detection performance. Lastly, we note that enhanced images reveal hidden objects that were not annotated due to the low visibility of the original images.

The Google Drive link below contains the following:\\
1- The images from the two groups used in Table 1 in the paper.
2- The images from the three groups used in the unanimous study in Table 4.

https://drive.google.com/open?id=1-w-HB9AdblaEbr_1cP1sz59EFBgG6QM5&usp=drive_fs

Notes:
- ALL images contain the inferred bounding boxes using the respective trained detection models and the ground truth annotations (dotted lines)
- For the first study, the original images are copied to each enhancement directory for easier comparison.

The YOLO-NAS object detection trained models can be found in the following link:
https://drive.google.com/file/d/1-wE2tpK9-Hx-L0aFYTjasN01bXKBm-ig/view?usp=drive_link
