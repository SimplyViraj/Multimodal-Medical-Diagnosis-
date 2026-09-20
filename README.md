# Multimodal-Medical-Diagnosis


Identifying thoracic illnesses using chest x-rays can
only occur through utilizing both visible and written clinical
information which is how radiologists employ their workflows. A
new methodology, the multi-modality mixture-of-experts (MoME)
model, sees use with multi-label thorax disease diagnosis for
the purpose of using chest x-ray images and clinical documentation
in combination. The methodology incorporates anteriorposterior
(AP), posterior-anterior (PA), and lateral chest x-ray
views, paired with results and impressions in reports in order
to increase diagnostic accuracy. DenseNet-121 separate expert
encoders are developed by view type,–as represented by the
three aforementioned views–, while the inadequacy of clinical
text representation is addressed by PubMedBERT. Each expert
encoder is connected to an evaluate-to-gate (E2G) network which
produces a unique set of modality-specific weights that allow for
adaptive multi-modality fusion based on sample identification.
Experiments utilize the MIMIC-CXRS dataset for diagnosis of
14 thoracic diseases using two performance metrics: the macro
area under the receiver operating characteristic curve (AUROC)
and the macro F1 score. The proposed schema’s macro F1 score
equals or exceeds the base maximum by approximately 8% and
produces interpretable sample-by-sample modality attribution
via the evaluate to gate network. Class imbalance is mitigated
using class weighted binary cross-entropy loss during training.
The proposed schema establishes a validated reproducible framework for multimodal thoracic diseased classification within vision
to language healthcare AI systems.
for multimodal thoracic diseased classification within vision
to language healthcare AI systems.
Index Terms—multimodal learning;
<img width="1536" height="1024" alt="Architechture" src="https://github.com/user-attachments/assets/35c692a3-b8ce-4426-a9af-072eeb27f2fc" />


