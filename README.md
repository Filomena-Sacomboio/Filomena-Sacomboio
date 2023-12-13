data center that will be useful for our research
============================================

My doctoral project addresses the theme of "Explainable Artificial Intelligence in Predicting Risk Factors Associated with Complications and Outcomes of Malaria". It is essential to explore the state of the art by reviewing related articles, understanding the approaches adopted by other researchers, learning about the models used, and understanding the types of data used, among other aspects.

Therefore, this repository was created to combine datasets used in malaria-related research, providing a valuable reference for future investigations. The focus will be exclusively on work utilizing machine learning on malaria-related biomedical datasets. Maintaining a data repository is a best practice and a fundamental component of data science and project development. This practice can boost transparency, foster collaboration, and increase efficiency, thus forming a solid foundation for future investigations and developments.

<br><br> git config format. column.width <50>


| abstract                                                                               |        Models used                    | Language | Year |Reference & Dataset | 
|----------------------------------------------------------------------------------------|:----------------------------------:| :-------:|------|------|
| The data center used was to store and process the large dataset of microscopic images used to train the deep learning model. The dataset includes more than 1,780 high-resolution images of P. falciparum-infected thick swabs.                                                   | YOLOv4-S,YOLOv4-L| English|2023|  https://bmcmedimaging.biomedcentral.com/articles/10.1186/s12880-023-00993-9. The datasets used linkhttps://data.lhncbc.nlm.nih.gov/public/Malaria/Thick_Smears_150/index.html, is available here http://air.ug/downloads/plasmodium-phonecamera.zip, https://drive.google.com/drive/folders/1p45Dt-BJy8hhoI-rYnhcaL6IMl5FsFL-?usp=sharing (last accessed: 03/10/2022).  https://data.lhncbc.nlm.nih.gov/public/Malaria/NIH-NLM-ThickBloodSmearsU/NIH-NLM-ThickBloodSmearsU.zip.|   
| The dataset features used in this article are based on microscopic 21368 object images of different living microforms of life. This dataset was used to predict microbial organisms in our research study. S1 Dataset.|Decision Tree Classifier (DTC), Extra Tree Classifier (ETC), i.e. the article uses the hybrid microbe classifier (HMC): Combines the predictions of DTC and ETC.| English | 2023 | [Predicting microbe organisms using data of living micro forms of life and hybrid microbes classifier] dataset[ (https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0284522) https://doi.org/10.1371/journal.pone.0284522.s001 (ZIP)] |
|The data sets were used in the study "To Understand the Relationship with Work and the Occurrence of Malaria in Thailand Using Maximum Entropy Geospatial Modeling" to store and process the large amount of data collected for the study. The data included information on malaria cases, work locations, travel routes, and environmental factors. The data centers were also used to run the MaxEnt model, a machine-learning algorithm used to predict the distribution of malaria cases in Thailand.|  Logistic Regression, Random Forest, Support Vector Machine (SVM), Gradient Boosting Machine (GBM), eXtreme Gradient Boosting (XGBoost), Artificial Neural Network (ANN)| English |  2023 |[(https://malariajournal.biomedcentral.com/articles/10.1186/s12936-023-04478-6)](https://malariajournal.biomedcentral.com/articles/10.1186/s12936-023-04478-6)  dataset (http://servir-rlcms.appspot.com/static/html/home.html), http://malaria.ddc.moph.go.th/malariar10/index_newversion.php|
| The study involved a large dataset of malaria cell images, which were collected from patients in malaria-endemic regions. The data center provided a secure and reliable environment to store and manage these images. The data center provided the ability to train and evaluate this CNN on a large dataset of malaria cell images. |Convolutional Neural Network (CNN), Support Vector Machine (SVM) | English | 2023 | [[Image analysis and machine learning-based malaria assessment system](https://journals.plos.org/globalpublichealth/article?id=10.1371/journal.pgph.0001950)]](https://link.springer.com/article/10.1007/s12553-021-00620-z) dataset [(https://lhncbc.nlm.nih.gov/LHC-downloads/downloads.html#malariadatasets) |
| A data center was used to train the machine learning algorithm to identify malaria parasites. And Evaluate the performance of the machine learning algorithm. The data center provided the ability to evaluate the performance of the machine learning algorithm. This involved testing the algorithm on a set of retained blood smear images to see how well it could identify malaria parasites. | ResNet50  |English  |2023|https://www.sciencedirect.com/science/article/pii/S2352864821000523. Data not available / Data will be made available on request|
| The data center in this study was used for efficient storage, management, preprocessing, analysis, and visualization of large and complex data sets, which ultimately contributed to the development of predictive models for Plasmodium knowlesi transmission. risk in Peninsular Malaysia.|  Maximum Entropy (MaxEnt), Random Forest (RF)| English | 2023 | https://www.frontiersin.org/articles/10.3389/fmicb.2023.1126418/full.  Requests to access these datasets should be directed to chtingwu@tmu.edu.tw. The data analyzed in this study is subject to the following licenses/restrictions: The data for this study is available from the Ministry of Health Malaysia. Restrictions apply to the availability of this data. Data is available with permission from the Malaysian Ministry of Health. Data generated in the study are available from the corresponding author upon reasonable request. |
|The use of this data set was essential for the researchers to achieve their objectives in this study. The dataset allowed us to compare different algorithms, identify possible biases, and develop more robust models. The Article provides valuable insights into the use of deep learning for malaria diagnosis and may pave the way for the development of more accurate and reliable diagnostic tools.] | ResNet50, DenseNet121, InceptionV3 | English |  2023| [Performance Analysis of Deep Learning Algorithms in Diagnosis of Malaria Disease (https://media.malariaworld.org/Performance_Analysis_of_Deep_Learning_Algorithms_in_Diagnosis_of_Malaria_Disease_758ec67bb1.pdf). This dataset was taken from the National Institutes of Health (NIH) website (https://www.nih.gov/, accessed on 11 August 2022). |
| The dataset included information on malaria cases in Thailand from 2019 to 2020. It was used to develop a geospatial malaria transmission model that was able to predict malaria transmission risk with high accuracy. |Maximum Entropy (MaxEnt)  | English | 2023 | [Understanding work-related travel and its relation to malaria occurrence in Thailand using geospatial maximum entropy modeling](https://malariajournal.biomedcentral.com/articles/10.1186/s12936-023-04478-6) Landcover data is publicly available through http://servir-rlcms.appspot.com/static/html/home.html. Malaria cases data from MOPH is available through: http://malaria.ddc.moph.go.th/malariar10/index_newversion.php|
|The researchers in this paper used this dataset to train the XAI models, evaluate their performance, and generate explanations for their predictions.| Random Forest, Support Vector Machine (SVM) | Portuguese | 2023 |[Predicting Plasmodium knowlesi transmission risk across Peninsular Malaysia using machine learning-based ecological niche modeling approaches](https://www.frontiersin.org/articles/10.3389/fmicb.2023.1126418/full)  dataset https://lhncbc.nlm.nih.gov/LHC-downloads/downloads.html#malariadatasets|
| This dataset was used to train and evaluate the performance of machine learning models. | Logistic Regression, Support Vector Machine (SVM), Random Forest | English | 2022 |[ [Malaria cell image classification by explainable artificial intelligence](https://link.springer.com/article/10.1007/s12553-021-00620-z) ](https://www.tandfonline.com/doi/full/10.1080/08839514.2022.2031826)|
| he dataset used in this article was collected as secondary data from the Federal Polytechnic Ilaro Medical Center, Ilaro Ogun State, Nigeria, and contains information on 337 patients who presented for consultation regarding malaria-related infections. The symptoms reported by patients were.were recorded and information was collected on the same patients after they were tested for malaria.The recorded symptoms as reported by the patients were all compared with the malaria test results, and the malaria test results were used to target variables | Logistic Regression, Naive Bayes, SVM (Support Vector Machine), Decision Tree, Random Forest, K-nearest Neighbors Neural Network, AdaBoost.|  | English | 2022 | Diagnosing malaria from some symptoms: a machine learning approach and public health implications](https://link.springer.com/article/10.1007/s12553-020-00488-5)  dataset [[aimed.tar.gz](datasets/aimed.tar.gz)](https://www.sciencedirect.com/science/article/pii/S2352340919313526)| |
<br><br>

| Dataset                           | Nr. Classes   | Language | Year | Cite | 
