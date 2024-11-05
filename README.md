# Underwater-Image-Enhancement-and-Object-Detection
Understanding the Influence of Image Enhancement on Underwater Object Detection: A Quantitative and Qualitative Study

Abstract: Underwater image enhancement is often perceived as a disadvantageous process to object 1
detection. We propose a novel analysis of the interactions between enhancement and detection 2
elaborating on the potential of enhancement to improve detection. In particular, we evaluate object 3
detection performance for each individual image, rather than across the entire set to allow a direct 4
performance comparison of each image before and after enhancement. This approach enables the 5
generation of unique queries to identify the outperforming and underperforming enhanced images 6
compared to the original images. To accomplish this, we first produce enhanced image sets of the 7
original images using recent image enhancement models. Each enhanced set is then divided into 8
two groups: 1) images that outperform or match the performance of the original images, and 2) 9
images that underperform. Subsequently, we create mixed original-enhanced sets by replacing 10
underperforming enhanced images with their corresponding original images. Next, we conduct a 11
detailed analysis by evaluating all generated groups for quality and detection performance attributes. 12
Finally, we perform an overlap analysis between the generated enhanced sets to identify cases where 13
the enhanced images of different enhancement algorithms unanimously outperform, equally perform, 14
or underperform the original images. Our analysis reveals that, when evaluated individually, most 15
enhanced images achieve equal or superior performance compared to their original counterparts. The 16
proposed method uncovers variations in detection performance that are not apparent in a whole-set 17
evaluation, as the overall analysis indicates a negative impact of enhancement on object detection. 18
We also find that over-enhancement may lead to a deteriorated object detection performance. Lastly, 19
we note that enhanced images reveal hidden objects that were not annotated due to the low visibility 20
of the original images. 
