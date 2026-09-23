# Sara Paratico

**Biomedical Data Scientist at IRCCS Policlinico San Donato**

[Versione italiana](README.it.md) · [LinkedIn](https://www.linkedin.com/in/sara-paratico-2a5b44184/)

I develop software and data workflows for clinical research. I work with clinicians, geneticists and software collaborators to define research variables, build tools and check that the results reflect the original clinical information. I hold an M.Sc. in Biomedical Engineering from Politecnico di Milano.

## Clinical research and software

My work at Policlinico San Donato is part of **PAMP-FA**, a study aiming to develop a multiparametric score to predict atrial fibrillation progression. I have coordinated study operations, defining protocols with clinicians and overseeing patient recruitment and data collection. The study combines clinical history, biomarkers, genetic data, echocardiography, ECG/Holter recordings and electroanatomical maps.

Making these data usable for statistical analysis and machine learning has involved several kinds of work:

- **Research platform.** I contribute to Omics Portal and Chirone, working with the collaborator who designed the ETL architecture. I develop Django/PostgreSQL features, document source data and build data marts and dashboards, including views that connect diagnostic questions with genetic findings. I also developed an operating-room tracking page fed by hospital records.
- **Clinical text analysis.** I developed bilingual, rule-based NLP applied to more than 58,000 discharge letters and to procedure reports. I prepare tests and investigate classification errors with clinicians.
- **Electroanatomical mapping.** I developed automated quantification of left atrial low-voltage area from CARTO3 and Opal maps using 3D mesh processing. I also explored associations with clinical variables through regression analyses. This work led to my first-author contribution at Computing in Cardiology 2026.

I use Python, SQL and Git in this work, alongside technical documentation and checks against source records. Other tools I have developed include Selenium workflows for study operations. I have also deployed medical language models locally on GPUs with MedGemma and Ollama. The clinical repositories are private.

## Selected academic projects

| Project | Work and methods |
| --- | --- |
| [Blood-flow simulation and data assimilation](https://github.com/saraparatico/proceedingsCodes) | My master's research on inlet-condition estimation in abdominal aortic aneurysms, using FEniCS and dolfin-adjoint. I configured and monitored parallel MPI simulations on workstation and remote HPC resources. |
| [SAPIENS robotic hand](https://github.com/saraparatico/SAPIENS-project) | EEG/EMG analysis in a student team project. My work included PCA, Random Forest/SVM and TensorFlow classifiers, with cross-validation and hyperparameter search. The notebooks also use Plotly for 3D PCA visualisation. |
| [Kidney and tumour segmentation](https://github.com/saraparatico/KidneyTumourSegmentation) | Biomedical computer vision coursework using a U-Net built with TensorFlow/Keras, including training, validation and prediction. |
| [Multiclass time-series classification](https://github.com/saraparatico/MultiClassTimeSeriesClassification) | Team coursework using 1D convolutional networks in TensorFlow/Keras for time-series classification. |

At NECSTLab, I also worked on deep learning for histopathological image retrieval.

## Publications

- **Paratico, S.**, Munafò, R., Trenti, C., Dyverfeldt, P., Saitta, S., Votta, E. (2026). *Estimation of Optimal Inlet Boundary Conditions for Blood Flow Assessment in Abdominal Aortic Aneurysm Using Variational Data Assimilation.* The FEniCS Project, Springer, pp. 77–88. DOI: [10.1007/978-3-032-17396-6_7](https://doi.org/10.1007/978-3-032-17396-6_7).
- Gjika, M., Sbrollini, A., Caputo, V. L., **Paratico, S.**, Locati, E. T., Burattini, L. (2026). *Freely available genomic datasets for atrial fibrillation research: current resources and analytical pipeline.* Frontiers in Genetics, 17, 1816698. DOI: [10.3389/fgene.2026.1816698](https://doi.org/10.3389/fgene.2026.1816698).

## Conference contribution

**Paratico, S.**, et al. (2026). *Cross-System Comparison of Left Atrial Low-Voltage Area by Electroanatomical Mapping in Atrial Fibrillation: An Automated Catheter-to-Triangle Approach.* Computing in Cardiology (CinC) 2026, Madrid. First author; proceedings publication pending.
