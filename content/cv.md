## Education

**Sichuan University**, PhD in Artificial Intelligence (Direct PhD Program), *Sep 2022 - Present*
- College of Computer Science, Artificial Intelligence Applications
- Advisors: Prof. Zhang Yi (IEEE Fellow)

**Sichuan University**, B.Eng. in Computer Science and Technology, *Sep 2018 - Jun 2022*
- College of Computer Science

## Research Projects

**Multimodal Report Generation System for 3D Radiological Imaging**
Algorithm Lead | Intelligent Medical Center, Sichuan University
*Sep 2025 - Present*
- **Background:** Built on the heterogeneous computing platform provided by the NSFC Major Program "Deep Learning Frameworks for Heterogeneous Computing Architectures and Large-Model Demonstration Applications," this work operationalizes the Sichuan Provincial Imaging Medicine Clinical Research Center open project "Multimodal-LLM-based DR Report Template Retrieval." Addressing radiologists' heavy daily reading workload and time-consuming report writing, it delivers an end-to-end system from 3D CT input to structured radiology report output.
- **Outcomes:** In collaboration with Dazhou Central Hospital, curated CT/MRI/X-ray scans and original reports from 28,752 patients, and designed a three-stage quality-control pipeline (physician entity-level correction + cross-physician consistency review + rule-engine anomaly detection) to build a high-quality multimodal dataset. The model was deployed at Dazhou Central Hospital with strong clinical results.
- **Technical Highlights:** Designed a vision-language alignment engine on SAT-Pro, M3D-CLIP, LLaMA3-8B and PPO, performing evidence grounding with 32 organ-entity queries and 48 lesion-entity queries, trained via LoRA (rank=64) + 8-bit quantization on 4×RTX 4090, and packaged as a PACS-integrable inference service.

**Deep Radiomics for Lung Metastasis Prediction**
Algorithm Lead | Intelligent Medical Center, Sichuan University
*Jun 2024 - Jun 2025*
- **Background:** For the Sichuan Provincial Department of Science and Technology Key R&D Project "Clinical Application of Lung Metastasis Prediction Based on Deep Radiomics," built a full-pipeline deep radiomics workflow spanning lesion segmentation, feature modeling, and metastasis risk prediction.
- **Outcomes:** Conducted multi-center validation with clinicians and developed interpretability modules and a decision-support interface to advance integration into clinical workflows.
- **Technical Highlights:** Applied a foreground-consistency semi-supervised 3D segmentation framework to pulmonary lesion modeling and optimized the imaging-feature backbone with graph-Mamba-style linear-complexity modeling, reducing annotation dependence under limited-label settings while maintaining inference efficiency.

## Skills

- **Programming:** Python, PyTorch, C/C++, LaTeX
- **Research:** Medical Image Analysis, Deep Learning, Computer Vision
- **Languages:** Chinese (Native), English (Proficient)

## Awards & Honors

- **First Prize, Sichuan Province "Challenge Cup" Competition** (*2026*)
- **Sichuan Province Young Doer** (*2025*)
- **Bronze Medal, National Postdoctoral Innovation and Entrepreneurship Competition** (*2023*)
- **First-Class Doctoral Fellowship**, Sichuan University (*2022*)
