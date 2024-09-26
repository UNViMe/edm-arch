# Advanced Data Mining Solution for Educational Decision Making

In this repository you can find the *information about the proposed model* revised in the paper "***Advanced Data Mining Solution for Educational Decision Making***".

This work is part of the joint effort made by the *National University of Villa Mercedes*, the *National University of San Luis* and the *School of Computing and Information Technology* from the *Eastern International University of Vietnam*.

The team is conformed by the Professors: Debnath, N. C., Novillo-Rangone, G. A, Montejano, G. A., Molina, W. R., Riesco, D. Garis, A. G.

# Index
- [Whats included in this repository?](#whats-included-in-this-repository)
- [About this work](#about-this-work)
  - [Proposed Model](#proposed-model)
  - [Web Tool](#web-tool)

# What is included in this repository?
- 📒 [Dropout_of_student_programmers.ipynb](https://github.com/UNViMe/edm-arch/blob/main/Dropout_of_student_programmers.ipynb): Jupiter Notebook ready for Google Colab.
- 📑 [programmers2023.csv](https://github.com/UNViMe/edm-arch/blob/main/programmers2023.csv): source data for the algorithm presented in the Jupyter Notebook.
- 📝 [ProposedModel.md](https://github.com/UNViMe/edm-arch/blob/main/ProposedModel.md): docs about the Proposed Model, core of this investigation.
- 📎 [EDM-Model-FullProcess-Vertical-enUS.svg](https://github.com/UNViMe/edm-arch/blob/main/EDM-Model-FullProcess-Vertical-enUS.svg): diagram presenting the workflow of the Proposed model

# About this work
Educational Data Mining (EDM) is a discipline concerned with developing methods for exploring the specific and large amounts of data from educational environments and using those methods to better understand students and the institutions in which they learn. Following the lines of research promoted by the *International Organizations in Education* (UNESCO, IESALC), the European Commission in AI, and considering the scarcity of data scientists in ML, **a new EDM model is proposed for educational problems that can be executed without data scientists or with a minimal presence of data scientists**. For this purpose, state-of-the-art techniques and tools such as Data Preprocessing, Feature Preprocessing, AutoML, and IML are articulated.

## Proposed Model

The proposed model will allow educational institutions to obtain complex knowledge by applying Machine Learning with a minimal presence of data scientists or with human resources that have only some of the skills that a data scientist would possess.

![Fig. 1: Proposed Model](https://github.com/UNViMe/edm-arch/raw/main/EDM-Model-FullProcess-Vertical-enUS.svg)



## Web tool
To facilitate the process of using the proposed model, it is accompanied by a tool that provides web-based access to people with minimal training. The proposed tool, which is currently under active development can be used in preview, was designed and evaluated in the context of an Argentine public university. 

![Web Tool Architecture](https://github.com/UNViMe/edm-arch/raw/main/ToolArchitecture.svg)

The tool is composed of 3 applications that are integrated in a traditional 3-tier web architecture. The source code can be found in three private repositories available to selected users:
- End User Web Interface (https://github.com/waltermolina/edm-react-app)
- Business Logic Rest API (https://github.com/waltermolina/edm-rest-api)
- EDM Core API (https://github.com/waltermolina/edm-py-api)

---
This is a ⚖️ GNU GPLv3 work, made with ❤️ in 🇦🇷. Need help? Get in contact 👉 {wmolina,gnovillo}@unvime.edu.ar.
