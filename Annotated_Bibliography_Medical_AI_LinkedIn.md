# Annotated Bibliography

**Medical AI Paper & Dataset Publications — LinkedIn Sample**

Scope: Medical AI / deep learning for medical imaging & diagnostics, sourced from LinkedIn content search (same field as the reference post on skin cancer classification, *Diagnostics* MDPI). Window: **January 2025 – September 16, 2026**.

- **Total entries:** 21

> **Note:** This is a sample compiled from LinkedIn content search, not an exhaustive census — LinkedIn's search interface does not expose a countable total of matching posts. Results below are what a structured set of targeted searches (under an authenticated LinkedIn session) surfaced and manually screened for recency and relevance, not every qualifying post that exists.

---

## 1. Benchmarking Class Imbalance Mitigation Strategies Across Deep CNN Architectures for Skin Cancer Classification

- **Authors & Journal Name:** Dr. Irshad Ahmad, Muhammad Khubaib, Saleh Altowaijri; Journal: Diagnostics (MDPI); (Peer-reviewed, Open Access)
- **Country and Dataset:** Country: Pakistan / Saudi Arabia (Smart Technologies Lab, Islamia College Peshawar); Dataset: ISIC 2019 (skin lesion image dataset)
- **Methodologies:** Benchmarked 16 class-imbalance mitigation techniques (incl. Balanced MixUp) across 6 pretrained deep CNN architectures: EfficientNet-B0, EfficientNet-B3, ResNet50, DenseNet121, InceptionV3, and MobileNetV2, for skin lesion classification.
- **Summary Findings:** Balanced MixUp combined with EfficientNet-B3 achieved the best result: 92.39% accuracy and 92.33% F1-score, showing that the choice of imbalance-mitigation strategy matters as much as the choice of architecture. Reference post the user originally linked to for this exercise.
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; Skin lesion class (multi-class skin cancer diagnosis); Independent variables:; Dermoscopic image (ISIC 2019); CNN architecture used; Class-imbalance mitigation technique applied

## 2. Attention-Guided EfficientNet-B3 with Grad-CAM Visualization for 22-Class Bone Fracture and Anatomical-Region Classification on the MultiBoneX Dataset

- **Authors & Journal Name:** Mian Hafeez, Dr. Irshad Ahmad, Saleh Altowaijri; Journal: Diagnostics (MDPI), Vol. 16, Issue 17, Article 2841; DOI: 10.3390/diagnostics16172841
- **Country and Dataset:** Country: Pakistan / Saudi Arabia; Dataset: MultiBoneX Dataset (22-class bone fracture/anatomical-region imaging)
- **Methodologies:** Attention-guided EfficientNet-B3 with CBAM (Convolutional Block Attention Module), combined with Grad-CAM for visual interpretability, applied to 22-class bone fracture and anatomical-region classification.
- **Summary Findings:** Achieved 75.03% test accuracy on the 22-class task. Grad-CAM visualizations were used to support interpretability of model predictions for clinical trust.
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; Bone fracture / anatomical-region class (22 classes); Independent variables:; X-ray/CT image (MultiBoneX); CBAM attention weights; EfficientNet-B3 feature representations

## 3. A Preliminary Comparison of EfficientNet-B3 and ResNet-50 for Detection and Subtype Classification of Intracranial Hemorrhage on Head Computed Tomography

- **Authors & Journal Name:** Awais Jan, Maryam Sajjad, Muhammad Hammad Hassan Mallick, Leena Faraz, Muhammad Mohsin, Bushra Ashar; Journal: Journal of Saidu Medical College (JSMC)
- **Country and Dataset:** Country: Pakistan (Frontier Medical College Abbottabad; GIKI Sawabi; NUST Islamabad; UET Mardan; Swat Medical College; Dow University of Health Sciences Karachi); Dataset: Head CT scan images (not further specified)
- **Methodologies:** Compared EfficientNet-B3 and ResNet-50 deep learning architectures for detecting and classifying subtypes of intracranial hemorrhage (ICH) from head CT scans.
- **Summary Findings:** Reported high patient-level sensitivity and ROC-AUC scores, supporting the feasibility of deep learning-assisted ICH subtype detection in medical imaging diagnostics.
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; ICH subtype presence/class; Independent variables:; Head CT scan image; Model architecture (EfficientNet-B3 vs. ResNet-50)

## 4. Lung Cancer Detection Using Medical Image Processing

- **Authors & Journal Name:** Paarth Kapur, Alekhya Gorugantu, Rujuta Ashtekar (mentored by Dr. Nandana Prabhu, Dr. Renuka Ashtekar); Journal: Springer, Proceedings of ICAIN 2025 (Lecture Notes in Networks and Systems, Vol. 5), book chapter; DOI: 10.1007/978-3-032-23314-1_12
- **Country and Dataset:** Country: Not specified; Dataset: CT scan lung cancer imaging dataset (4 classes: Adenocarcinoma, Large Cell Carcinoma, Squamous Cell Carcinoma, Normal)
- **Methodologies:** Compared DenseNet201, ResNet50, a hybrid DenseNet201-ResNet50 architecture, and EfficientNet-B3 (via transfer learning) for 4-class lung cancer classification from CT scans.
- **Summary Findings:** The EfficientNet-B3 transfer-learning model achieved the best result: 94.29% test accuracy across the four lung cancer classes.
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; Lung cancer class (4 categories); Independent variables:; CT scan image; Model architecture used

## 5. Multi-approach technique implementation for segmentation of left ventricular myocardial infarction and quantification

- **Authors & Journal Name:** Dr. Kavitha K.S. (Dept. of CSE, Dayananda Sagar College of Engineering); Journal: Scientific Reports
- **Country and Dataset:** Country: India (Bangalore); Dataset: Cardiac imaging data (not further specified)
- **Methodologies:** Combines image preprocessing, deep learning, and optimisation-based approaches for segmentation of left ventricular myocardial infarction.
- **Summary Findings:** Demonstrates improved identification and measurement (quantification) of myocardial infarction from cardiac medical images, illustrating computational intelligence's potential in advanced medical image analysis.
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; Segmented myocardial infarction region / quantification metric; Independent variables:; Cardiac image; Preprocessing method; Optimisation-based segmentation parameters

## 6. Artificial Intelligence in Healthcare Practice: Validation, Fairness, and Regulatory Challenges

- **Authors & Journal Name:** Ghulam Hussain Noori, Shaista Bibi, Seung Won Lee; Journal: INQUIRY: The Journal of Health Care Organization, Provision, and Financing (Sage)
- **Country and Dataset:** Country: Not specified; Dataset: N/A (systematic review of 20 clinical AI studies, 2020-2025)
- **Methodologies:** Systematic review of 20 clinical AI studies (2020-2025) assessing validation practices, fairness, and regulatory readiness of clinical AI, with a focus on diagnostic imaging applications.
- **Summary Findings:** Deep learning (especially CNNs) dominates medical imaging diagnostics, with a median AUC of 0.91. Top clinical domains are Radiology (30%), Oncology (20%), Cardiology (15%). Main adoption barriers: regulatory compliance (55%), limited algorithmic transparency (40%), data quality limitations (35%), clinical workflow integration (30%).
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; Clinical AI adoption / validation outcome (qualitative, review-level); Independent variables (review dimensions):; Clinical domain; Validation practice type; Fairness assessment presence; Regulatory compliance status

## 7. An Intelligent Gene Biomarker Identification Framework for Pan-Cancer Classification using Genetic Algorithms and Deep Learning

- **Authors & Journal Name:** Aruja Tiwary (1st author), Lubhana Mutha, Daksh Patil, Dr. Hima Deepthi Vankayalapati, Prof. Prateeksha Shanoj; Journal: IEEE, Proceedings of the International Conference on Bioinformatics and Computational Biology (ICBCB 2026); DOI: 10.1109/ICBCB69424.2026.11621848
- **Country and Dataset:** Country: India (IIT Kanpur); Dataset: TCGA (The Cancer Genome Atlas) - 10,459 patient samples, 33 cancer types
- **Methodologies:** Used a Genetic Algorithm to select an informative gene subset from TCGA gene-expression data (avoiding the full transcriptome), then trained two attention-based models, TabNet and SAINT, on that subset.
- **Summary Findings:** SAINT reached 98.76% accuracy on cancer detection and 95.60% across all 33 tumor types. Gradient attribution analysis showed the model relied on biologically meaningful genes (e.g. EGFR/KRAS for lung cancer, BRCA1/ESR1 for breast cancer, APC/TP53 for colorectal cancer), confirming genuine oncology signal rather than noise. Shared separately by two co-authors on LinkedIn; counted once.
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; Cancer type (33-class) / cancer vs. non-cancer; Independent variables:; Gene expression profile (TCGA); Genetic-Algorithm-selected gene subset; Model type (TabNet vs. SAINT)

## 8. Cross-Domain Transfer Learning and Self-Supervised Representation Learning for Automated Histopathological Image Classification in Colorectal Cancer Grading System

- **Authors & Journal Name:** Jeya Sherlyne P; Journal: IEEE
- **Country and Dataset:** Country: Not specified; Dataset: Histopathological image dataset (not further specified)
- **Methodologies:** Combines cross-domain transfer learning, self-supervised representation learning, patch-level analysis, domain adaptation, synthetic data generation, a Swin Transformer backbone, multimodal learning, and Grad-CAM explainability for colorectal cancer grading.
- **Summary Findings:** Framework is intended to improve accuracy, generalization, and interpretability of automated histopathological cancer grading. Author's second IEEE publication; her first (ConvNeXtV2 for skin lesion classification) is referenced but not separately dated/counted here.
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; Colorectal cancer grade (from histopathological image); Independent variables:; Histopathological image patch; Domain-adaptation/self-supervised features; Swin Transformer representations

## 9. A Comparative Experimental Study of DenseNet121, EfficientNetB7, MobileNetV2, and ConvNeXTV2 for Breast Cancer Classification

- **Authors & Journal Name:** HirenKumar Kukadiya & Divyakant Meva (highlighted by International Journal of Advanced Trends in Computer Applications, IJATCA); Journal: IJATCA
- **Country and Dataset:** Country: Not specified; Dataset: Mammographic imaging dataset (not further specified)
- **Methodologies:** Comparative experimental study of four deep learning architectures (DenseNet121, EfficientNetB7, MobileNetV2, ConvNeXTV2) for breast cancer classification from mammographic images.
- **Summary Findings:** Presents a head-to-head comparison of the four architectures' performance for breast cancer classification (specific accuracy figures not disclosed in the LinkedIn summary).
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; Breast cancer class (malignant/benign or subtype); Independent variables:; Mammographic image; Model architecture used

## 10. AI-Driven Multimodal Deep Learning Framework for Automated Lung and Skin Cancer Detection and Classification from Medical Images

- **Authors & Journal Name:** Palagummi Syam Kumar, Namadi Jeevana Dheepa, Thummalapalli N S S Siddhardha, Bokka Ganapathi, Bogabattina Venkata Manikanta; Journal: International Journal for Research Trends and Innovation (IJRTI), Vol. 11, Issue 8; Paper ID: IJRTI2608060
- **Country and Dataset:** Country: Not specified; Dataset: Medical imaging data (lung and skin cancer; not further specified)
- **Methodologies:** Multimodal deep learning framework combining medical image analysis, feature learning, and classification for automated detection of both lung and skin cancer from medical images.
- **Summary Findings:** Positioned as supporting faster, more consistent, technology-driven healthcare decision-making for lung and skin cancer diagnosis; specific performance metrics not disclosed in the LinkedIn summary.
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; Cancer type/class (lung or skin); Independent variables:; Medical image (multimodal input); Deep learning architecture used

## 11. Skin Cancer Classification Using Deep Learning Techniques

- **Authors & Journal Name:** Vandana H, Arpitha V G, Anvitha GH, Neha Khanum (guided by Dr Uma Mahesh R N); Journal: IEEE Xplore, Annual International Conference on Data Science, Machine Learning and Blockchain Technology (AICDMB-2025)
- **Country and Dataset:** Country: India (ATME College of Engineering); Dataset: Not specified
- **Methodologies:** Mini-project applying deep learning techniques for skin cancer classification, presented at AICDMB-2025.
- **Summary Findings:** Demonstrates feasibility of a student-led deep learning pipeline for skin cancer classification (specific accuracy figures not disclosed in the LinkedIn summary).
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; Skin cancer class; Independent variables:; Skin lesion image; Deep learning model used

## 12. Skin Cancer Classification using Machine Learning

- **Authors & Journal Name:** Kavya S., Himanshu Chauhan, Krishna Kumar (mentored by Dr Dhyanendra Jain); Journal: IEEE Xplore, International Conference on Innovative Practices in Technology and Management (2026)
- **Country and Dataset:** Country: Not specified; Dataset: Dermoscopic image dataset (not further specified)
- **Methodologies:** Web-based deep learning system for skin cancer classification from dermoscopic images, using a CNN, deployed with TensorFlow.js and a React web application for real-time, in-browser predictions.
- **Summary Findings:** Achieved ~94.28% accuracy classifying 7 types of skin lesions; designed to make early detection faster, more accessible, and privacy-friendly by running predictions directly in the browser.
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; Skin lesion type (7 classes); Independent variables:; Dermoscopic image; CNN model (TensorFlow.js)

## 13. Multi-Class Classification of Cervical Cancer Cells Using Deep Learning Techniques

- **Authors & Journal Name:** E. Anisha Patra; Journal: TANZ Research Journal
- **Country and Dataset:** Country: India (NIST University, Brahmapur, Odisha); Dataset: Cervical cancer cell imaging dataset (not further specified)
- **Methodologies:** Applies deep learning techniques to multi-class classification of cervical cancer cells to improve accuracy and efficiency of early detection.
- **Summary Findings:** Contributes to improved cervical cancer cell classification accuracy for early detection and better healthcare outcomes (specific performance metrics not disclosed in the LinkedIn summary).
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; Cervical cancer cell class; Independent variables:; Cell imaging data; Deep learning model used

## 14. An Optimized Framework for Accurate Skin Cancer Classification

- **Authors & Journal Name:** Parthasarathy M and co-authors; Journal: IEEE Xplore, 2025 IConSCEPT conference
- **Country and Dataset:** Country: Not specified; Dataset: Not specified
- **Methodologies:** Hybrid deep learning approach integrating a DenseNet201 backbone with a custom CNN architecture to improve detection of malignant skin conditions.
- **Summary Findings:** Framework designed to overcome challenges of traditional models in enhancing detection of malignant skin conditions (specific accuracy figures not disclosed in the LinkedIn summary).
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; Skin condition class (malignant vs. benign); Independent variables:; Skin image; DenseNet201 + custom CNN features

## 15. HistAdvNet: A Robust Deep Learning Framework for Histopathology Classification Under Adversarial Conditions

- **Authors & Journal Name:** Sazzad Hossain and co-authors; Journal: Biomedical Signal Processing and Control (Elsevier, Q1 journal)
- **Country and Dataset:** Country: Not specified; Dataset: Lung and colon cancer histopathology image datasets
- **Methodologies:** Introduces HistAdvNet, a novel lightweight deep learning framework for lung and colon cancer histopathology image classification, designed and tested for robustness against adversarial attacks.
- **Summary Findings:** Demonstrates that HistAdvNet maintains strong classification accuracy while showing improved robustness against adversarial perturbations, compared to standard architectures.
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; Lung/colon cancer histopathology class; Independent variables:; Histopathology image (incl. adversarially perturbed versions); HistAdvNet architecture

## 16. Convolutional Neural Network for Lung Cancer Prediction and Classification

- **Authors & Journal Name:** JAMI Jaswanth, Palameti Reddy Lakshmi Manoj (guided by Mrs. Sakthi U); Journal: IEEE Xplore Digital Library
- **Country and Dataset:** Country: India (SRM University, KTR campus); Dataset: CT scan imaging dataset (not further specified)
- **Methodologies:** Uses a Convolutional Neural Network (CNN) for prediction and classification of lung cancer from CT scan images.
- **Summary Findings:** Aims to support faster and more accurate medical diagnosis of lung cancer using CNN-based image classification (specific accuracy figures not disclosed in the LinkedIn summary).
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; Lung cancer presence/class; Independent variables:; CT scan image; CNN model

## 17. Colon Cancer Classification from Histopathological Images Using Convolutional Neural Networks

- **Authors & Journal Name:** Yuvashree M; Journal: International Research Journal on Advanced Engineering and Management (IRJAEM), Vol. 04, Issue 03
- **Country and Dataset:** Country: Not specified; Dataset: Histopathological image dataset (not further specified)
- **Methodologies:** Applies CNN-based deep learning techniques to classify colon cancer from histopathological medical images.
- **Summary Findings:** Reports improved accuracy in colon cancer detection from histopathological images using CNN methods (specific figures not disclosed in the LinkedIn summary).
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; Colon cancer class; Independent variables:; Histopathological image; CNN model

## 18. NeuroTrustNet: A Cost-Effective Multimodal Ensemble Framework for Brain Tumor Classification Under Cross-Dataset Variability

- **Authors & Journal Name:** Ferdaus Ibne Aziz (1st author), Tumennast E. (supervisor/co-author) and team; Journal: Frontiers in Artificial Intelligence (Impact Factor 6.7)
- **Country and Dataset:** Country: South Korea (University of Ulsan); Dataset: Multiple external MRI datasets (cross-dataset evaluation)
- **Methodologies:** Proposes NeuroTrustNet, a multimodal AI framework combining CNNs, Vision Transformers (ViTs), and radiomic features through Adaptive Attention Stacking (AAS), to balance performance, computational efficiency, and interpretability.
- **Summary Findings:** Achieved 94% accuracy on a completely unseen external MRI dataset, demonstrating strong cross-dataset generalization with improved computational efficiency compared to single-model baselines.
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; Brain tumor class; Independent variables:; MRI image (cross-dataset); Radiomic features; CNN/ViT ensemble outputs (AAS)

## 19. An explainable deep learning approach for automated detection and grading of diabetic retinopathy from fundus images

- **Authors & Journal Name:** Marisa Oishy and co-authors (incl. Muradul Islam; supervised by Ferdaus Anam Jibon, Gahangir Hossain); Journal: Microvascular Research (Elsevier)
- **Country and Dataset:** Country: Not specified; Dataset: Fundus image dataset (not further specified)
- **Methodologies:** Hybrid and explainable deep learning approach for automated detection and grading of diabetic retinopathy severity from retinal fundus images; originated as an undergraduate thesis.
- **Summary Findings:** Contributes an explainable (interpretable) deep learning pipeline for diabetic retinopathy grading, intended to support clinical trust in automated grading decisions (specific accuracy figures not disclosed in the LinkedIn summary).
- **Variables (inputs and output(s) identified, with description as necessary):** Dependent variable:; Diabetic retinopathy grade/severity; Independent variables:; Fundus (retinal) image; Explainability (XAI) feature maps

## 20. RACLETTE: Realistic Synthetic Aortic 4D/5D Flow MRI with Computational Enhancement for Training and Testing Algorithms

- **Authors & Journal Name:** Pietro Dirix, Stefano Buoso, Sebastian Kozerke (ETH Zurich Cardiovascular Magnetic Resonance Group); Open dataset release
- **Country and Dataset:** Country: Switzerland (ETH Zurich); Dataset: RACLETTE itself is the new dataset - CFD-enhanced synthetic MRI: 189 virtual subjects (Aortic 4D Flow MRI) + 25 virtual subjects (Aortic 5D Flow MRI)
- **Methodologies:** Combines Computational Fluid Dynamics (CFD) simulations with MRI signal modeling to generate realistic synthetic cardiovascular MRI datasets with known ground truth.
- **Summary Findings:** Public release of a new open dataset (RACLETTE) enabling controlled, reproducible benchmarking of image reconstruction, segmentation, and hemodynamic quantification algorithms for cardiovascular MRI research.
- **Variables (inputs and output(s) identified, with description as necessary):** Output (dataset content):; Synthetic 4D/5D Flow MRI volumes with known ground truth; Input factors (dataset generation):; CFD simulation parameters; MRI encoding variant (standard, super-resolution, icosahedral)

## 21. COBRA2026: A large-scale pelvic cone-beam CT projection dataset

- **Authors & Journal Name:** Adrian Thummerer and co-authors (incl. Lukas Zimmermann, Simon Rit, Florian Kamp, Matteo Maspero, Guillaume Landry, and others; 6 European radiotherapy centers); Associated with the COBRA2026 Deep Learning Challenge (MIDL 2027)
- **Country and Dataset:** Country: Multi-country (Europe) - 6 radiotherapy centers using Elekta and Varian systems; Dataset: COBRA2026 itself is the new dataset - 867 pelvic CBCT acquisitions, ~950GB
- **Methodologies:** Collected raw clinical CBCT projection data, acquisition geometry/calibration/correction information, clinically reconstructed CBCT images, planning CT images, deformably aligned CT references, and simulated projections across 6 European radiotherapy centers.
- **Summary Findings:** Provides a large-scale, openly released benchmark dataset (COBRA2026) to support development and reproducible benchmarking of conventional and deep learning-based cone-beam CT reconstruction and image correction methods in radiotherapy; forms the basis of the COBRA2026 Deep Learning Challenge at MIDL 2027.
- **Variables (inputs and output(s) identified, with description as necessary):** Output (dataset content):; CBCT projection data, reconstructed images, planning CTs, simulated projections; Input factors (dataset generation):; Imaging system (Elekta vs. Varian); Acquisition geometry/calibration

---

*Compiled via LinkedIn content search under an authenticated LinkedIn session (Sunanda Biswas). See the companion Excel workbook (`Medical_AI_Paper_Dataset_Publications_LinkedIn.xlsx`) and `Recent Publications.md` / `Recent Publications.pdf` for the same data in spreadsheet and summary-entry formats.*
