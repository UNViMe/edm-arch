# Advanced Data Mining Solution for Educational Decision Making

In this repository you can find the *information about the proposed model* revised in the paper "***Advanced Data Mining Solution for Educational Decision Making***".
This work is part of the joint effort made by the *National University of Villa Mercedes*, the *National University of San Luis* and the *School of Computing and Information Technology* from the *Eastern International University of Vietnam*.
The team is conformed by the Professors:
- Debnath, N. C.
- Novillo-Rangone, G. A
- Montejano, G. A.
- Molina, W. R.
- Riesco, D.
- Garis, A. G.

# What is included in this repository?
- 📒 [Dropout_of_student_programmers.ipynb](https://github.com/UNViMe/edm-arch/blob/main/Dropout_of_student_programmers.ipynb): Jupiter Notebook ready for Google Colab.
- 📑 [programmers2023.csv](https://github.com/UNViMe/edm-arch/blob/main/programmers2023.csv): source data for the algorithm presented in the Jupyter Notebook.

# Introduction
Educational Data Mining (EDM) is a discipline concerned with developing methods for exploring the specific and large amounts of data from educational environments and using those methods to better understand students and the institutions in which they learn. 

In recent years, there has been a great deal of research showing how EDM techniques have been used to improve academic performance, adaptive systems, educational quality, dropout rates, procrastination and institutional management at all educational levels (from pre-school to university) and for all modalities (face-to-face, online, hybrid). Some of the most important references are the “International Conference on Educational Data Mining” that has been held since 2008, and the “Journal of Educational Data Mining” that has been published since 2009. The achievements obtained in EDM have been possible thanks to the progress of determining components such as Computational Power, Big Data, Artificial Intelligence (AI), and the support of Researchers and International Organizations that promote these tools for a better educational quality.

In 2019, the United Nations Educational, Scientific and Cultural Organization (UNESCO) produced a document known as the “Beijing Consensus on Artificial Intelligence and Education”, in which it proposes advice and recommendations on how to take greater advantage of AI technologies with a view to achieving the 2030 Agenda for Education. Among the guidelines, they recommend using AI to serve learning and the evaluation of results, ensuring an ethical, transparent and verifiable use of data and algorithms. In addition, the International Institute for Higher Education in Latin America and the Caribbean (IESALC) states as one of its priorities in Innovation:

> “Contribute to the pedagogical renewal of higher education through analyses that contribute to a better understanding of the impact of emerging technologies: Elaboration of a series of reports that present the challenges derived from emerging technologies and how different higher education institutions in the region and internationally, face them, showing their practices in the areas of AI, blockchain, and learning metrics”.
> 

In the same sense as the IESALC and the Beijing Consensus, the proposal of Romero et al. is shown, where it is specified that the design of processes should facilitate educators or non-expert users in the area of Data Mining (DM) the implementation of knowledge extraction techniques.

Computational Power (CP) followed Gordon Moore in 1965 when he predicted what is known as “Moore's Law”. In it he stated that the CP would increase every two years, i.e. the number of transistors on a chip would double in that period. For almost five decades, this relationship was fulfilled quite accurately, but in the last decade the appearance of processors like GPU (Graphics Processing Unit) from NVIDIA, TPU (Tensor Processing Unit) from Google, IPU2 from Graphcore, and WS1 from Cerebras, among others, increased the computational power as never seen before. One of the most outstanding cases is seen in the GPUs provided by NVIDIA that are used for AI, where the number of operations per second that these chips are capable of processing increased 317 times between 2012 and 2020; or the case of Open AI's GPT which in 2018 trained Natural Language Processing models with hundreds of millions of parameters and in 2020 GPT-3 used 175,000 million parameters.

These almost exponential advances of the CP are also allowing the rise of the so-called “Edge Computing”: while before these complex calculations were performed on a server in the cloud that then sent us the data, modern processors with cores dedicated to these tasks are already able to process these data themselves and give the answer on our end without the need for us to be connected to the cloud.

Artificial Intelligence (AI) is a branch of Computer Science that designs and creates entities with the ability to perceive data from their environment, analyze it, assimilate it and use it to achieve a goal in a manner similar to human cognition and reasoning capabilities. It also makes use of fundamentals from areas such as Logic, Mathematics and Philosophy. AI involves several technologies and disciplines, such as Natural Language Processing, Expert Systems, Robotics, Machine Learning (ML) and Deep Learning (DL).

Big Data is a set of technologies that have been created to collect, analyze and manage the data generated by users on the Internet or in specific applications or software. Its idea is to collect the massive data that is generated in “raw” form, and process it to identify patterns or other types of behavior that can help specific sectors.

Big Data in Education (BDE) is fed day by day, with data from classrooms, educational institutions, ministries, curricula, pedagogical models, adaptive systems, virtual campuses, massive online courses and learning analytics, which together with AI techniques such as ML and DL, allow scientists to obtain positive results for a large number of educational problems.

There are already two major waves of innovation in BDE, those focused on continuous assessment and academic monitoring, and those designed to extract much more intimate data from students' bodies, faces and even brains, such as facial recognition systems for school safety or aspects of learning such as psychological states or even neural activity, which are becoming visible with advances in affective computing, biometrics and neurotechnology.

Machine Learning (ML) is a discipline belonging to AI that seeks to enable machines to “learn” or generalize knowledge from a set of experiences, without the need to be explicitly or traditionally programmed. Different machine learning systems can be observed, such as supervised, unsupervised and reinforcement learning systems to perform classification, regression, clustering, association rules and dimensionality reduction tasks, among others.

A large majority of educational problems can be solved by applying supervised ML systems for classification and regression tasks, this can be verified by analyzing the reviews on educational data mining by Morales Carrillo et al. where 76% of the educational problems studied are addressed with these techniques or the review by Panizzi where he states that the usual problems are academic performance, profile detection, educational quality and school dropout; problems that 70% or even more can be solved with supervised ML techniques.

The recent progress in ML and the competitive advantages that the discovery of knowledge in data allows generate a boom in the development of applications that automate the tasks of this workflow. That is why there is a growing community generated around the creation of tools that automate these tasks, whose success today depends mainly on ML experts (Data Scientists), who preprocess the data, build the models by choosing the appropriate algorithms and configure their hyperparameters. Several techniques are used to automate these activities, which in the case of human experts are carried out with knowledge, intuition, judgment and reasoning.

Data Scientists are a scarce human resource due to the multiplicity of skills and roles that must be fulfilled in an ML or Pipeline workflow, and this scarcity is felt in the field of educational institutions.

AutoML (Automated Machine Learning) has as its main objective the progressive automation of ML, providing methods and processes to make it available to non-expert users, improve ML efficiency and accelerate ML research. Although the use of AutoML allows good predictions to be made, the models generated are often complex and difficult to interpret.

In AutoML, accuracy is measured by comparing the output of a model to the known true values of the input data set. A model can achieve high accuracy by memoizing features or patterns that are not important in your data set. If there is a bias in your input data set, this can also affect your model. In addition, the data in the training environment may not be a good representation of the data in the production environment in which the model is implemented, which can lead to drawbacks such as racial discrimination. Therefore, the prediction accuracy achieved for a specific data set is not enough, transparency and interpretability need to be improved for these models to be reliable.

Interpretability means providing explanation to users for a particular decision or process. It includes understanding the main tasks that affect the results, and knowing the patterns, rules and features that are learned by an algorithm. It has great relevance for different stakeholders according to their needs:

- Data Scientists. They need to build models with high accuracy, understand the details to select the best one and obtain information to be able to communicate their findings to their target audience.
- End-users. They need to know why a model makes a certain prediction, how they will be affected by such predictions, whether they are getting a fair deal, and whether they should object to any decisions.
- Legal entities. They need the system to be transparent, without bias. With the inevitable rise of ML algorithms, the task of auditing the decisions that models make becomes increasingly complex.

Interpretable Machine Learning (IML) is an area of data science that develops methods for interpreting ML models. There are some methods for intrinsically interpretable models and others for post hoc (model agnostic) interpretation. Another classification groups methods for interpreting local or global models; that is, it explains an individual or general prediction of model behavior.

Following the lines of research promoted by the *International Organizations in Education* (UNESCO, IESALC), the European Commission in AI, and considering the scarcity of data scientists in ML, **a new EDM model is proposed for educational problems that can be executed without data scientists or with a minimal presence of data scientists**. For this purpose, state-of-the-art techniques and tools such as Data Preprocessing, Feature Preprocessing, AutoML, and IML are articulated.
