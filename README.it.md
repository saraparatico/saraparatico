# Sara Paratico

**Biomedical Data Scientist presso IRCCS Policlinico San Donato**

[English version](README.md) · [LinkedIn](https://www.linkedin.com/in/sara-paratico-2a5b44184/)

Sviluppo software e flussi di dati per la ricerca clinica. Lavoro con clinici, genetisti e collaboratori informatici per definire variabili di ricerca, costruire strumenti e verificare che i risultati rispecchino le informazioni cliniche originali. Ho conseguito la laurea magistrale in Ingegneria Biomedica al Politecnico di Milano.

## Ricerca clinica e sviluppo software

Il mio lavoro al Policlinico San Donato si svolge nell'ambito di **PAMP-FA**, uno studio che mira a sviluppare uno score multiparametrico per predire la progressione della fibrillazione atriale. Ho coordinato le attività operative, definendo i protocolli con i clinici e seguendo l'arruolamento dei pazienti e la raccolta dei dati. Lo studio combina anamnesi clinica, biomarcatori, dati genetici, ecocardiografia, registrazioni ECG/Holter e mappaggi elettroanatomici.

Per rendere questi dati utilizzabili nelle analisi statistiche e nel machine learning ho lavorato su diversi aspetti:

- **Piattaforma di ricerca.** Contribuisco a Omics Portal e Chirone, affiancando il collaboratore che ha progettato l'architettura ETL. Sviluppo funzionalità Django/PostgreSQL, documento i dati sorgente e creo datamart e dashboard, comprese visualizzazioni che collegano i quesiti diagnostici ai risultati genetici. Ho anche sviluppato una pagina di monitoraggio della sala operatoria alimentata dai dati del gestionale ospedaliero.
- **Analisi del testo clinico.** Ho sviluppato un sistema di NLP bilingue basato su regole, applicato a oltre 58.000 lettere di dimissione e ai referti delle procedure. Predispongo test e analizzo gli errori di classificazione con i clinici.
- **Mappaggio elettroanatomico.** Ho sviluppato la quantificazione automatica delle aree a basso voltaggio dell'atrio sinistro da mappe CARTO3 e Opal attraverso l'elaborazione di mesh 3D. Ho anche studiato le associazioni con variabili cliniche tramite analisi di regressione esplorative. Da questo lavoro è nato il mio contributo come prima autrice a Computing in Cardiology 2026.

In queste attività uso Python, SQL e Git, insieme alla documentazione tecnica e al confronto con i dati sorgente. Ho inoltre sviluppato workflow Selenium a supporto dello studio e distribuito localmente su GPU modelli linguistici medici con MedGemma e Ollama. I repository clinici sono privati.

## Progetti accademici selezionati

| Progetto | Attività e metodi |
| --- | --- |
| [Simulazione del flusso ematico e data assimilation](https://github.com/saraparatico/proceedingsCodes) | Ricerca magistrale sulla stima delle condizioni di ingresso negli aneurismi dell'aorta addominale, con FEniCS e dolfin-adjoint. Ho configurato e monitorato simulazioni parallele con MPI su workstation e risorse HPC remote. |
| [Mano robotica SAPIENS](https://github.com/saraparatico/SAPIENS-project) | Analisi EEG/EMG in un progetto di gruppo studentesco. Il mio lavoro comprende PCA, Random Forest/SVM e classificatori TensorFlow, con cross-validation e ricerca degli iperparametri. I notebook usano anche Plotly per visualizzare la PCA in 3D. |
| [Segmentazione di rene e tumore](https://github.com/saraparatico/KidneyTumourSegmentation) | Progetto del corso di visione biomedica con una U-Net in TensorFlow/Keras, comprendente addestramento, validazione e predizione. |
| [Classificazione multiclasse di serie temporali](https://github.com/saraparatico/MultiClassTimeSeriesClassification) | Progetto di gruppo universitario con reti convoluzionali 1D in TensorFlow/Keras per classificare serie temporali. |

Al NECSTLab ho anche lavorato al deep learning per il recupero di immagini istopatologiche.

## Pubblicazioni

- **Paratico, S.**, Munafò, R., Trenti, C., Dyverfeldt, P., Saitta, S., Votta, E. (2026). *Estimation of Optimal Inlet Boundary Conditions for Blood Flow Assessment in Abdominal Aortic Aneurysm Using Variational Data Assimilation.* The FEniCS Project, Springer, pp. 77–88. DOI: [10.1007/978-3-032-17396-6_7](https://doi.org/10.1007/978-3-032-17396-6_7).
- Gjika, M., Sbrollini, A., Caputo, V. L., **Paratico, S.**, Locati, E. T., Burattini, L. (2026). *Freely available genomic datasets for atrial fibrillation research: current resources and analytical pipeline.* Frontiers in Genetics, 17, 1816698. DOI: [10.3389/fgene.2026.1816698](https://doi.org/10.3389/fgene.2026.1816698).

## Contributo a conferenza

**Paratico, S.**, et al. (2026). *Cross-System Comparison of Left Atrial Low-Voltage Area by Electroanatomical Mapping in Atrial Fibrillation: An Automated Catheter-to-Triangle Approach.* Computing in Cardiology (CinC) 2026, Madrid. Prima autrice. Contributo non ancora pubblicato negli atti.
