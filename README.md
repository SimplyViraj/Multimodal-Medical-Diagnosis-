# Multimodal-Medical-Diagnosis

This project presents a multimodal approach to medical diagnosis
by combining Chest X-ray images with their corresponding radiology
report text. Many real-world clinical decisions rely on both visual findings
and written descriptions from physicians. Traditional AI models process
these inputs independently, limiting diagnostic performance. Our work
uses a late-fusion multimodal deep-learning architecture to jointly
analyze both sources of information.
We use the Open Access Indiana University Chest X-ray
Collection, which contains thousands of paired X-ray images and text
reports. Images were preprocessed from DICOM format into standardized
PNGs. For modeling, Chest X-ray images are encoded using
DenseNet-121, while clinical reports are encoded using BioClinicalBERT.
The extracted feature vectors are then fused and passed through a
classification head to predict disease class labels.
This multimodal architecture improves diagnostic accuracy by
leveraging complementary information from both modalities. The project
demonstrates the potential of fusion-based approaches for real-world
clinical decision support systems.
