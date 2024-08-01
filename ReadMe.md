## **VU Chatbot System👋🛒**
<p align="center">
<img src="https://github.com/hussain0048/Machine-Learning/blob/master/Machine%20Leanring.png"></a>
</p>

Welcome to the VU Chatbot System repository! 🚀

<a href="https://app.commanddash.io/agent?github=https://github.com/hussain0048/VU-Chatbot-System"><img src="https://img.shields.io/badge/AI-Code%20Gen-EB9FDA"></a>

## **Overview👋🛒**

The VU Chatbot System is an advanced AI-powered virtual assistant designed to enhance user interaction and streamline information retrieval. Whether you're a student, educator, or developer, our chatbot provides intuitive and efficient solutions tailored to your needs.

## **Features👋🛒**

**1- Natural Language Processing:** Engage in smooth, human-like conversations with our state-of-the-art NLP capabilities.

**2- Personalized Assistance**: Receive personalized responses based on user profiles and interaction history.

**3- Multi-Platform Support:**: Integrate seamlessly with various platforms including web, mobile, and social media.

**4- Extensible Architecture:**: Easily add new features and functionalities with our modular design.

**5- Real-Time Analytics:**: Monitor and analyze user interactions to continually improve the chatbot experience..

## **Contributing🙌**

We welcome contributions from the community! Whether it's fixing a bug, adding a new algorithm implementation, or improving documentation, your contributions are valuable. Please contact on my **skype ID: themushtaq48** for guidelines on how to contribute.

## **📬 Support**
   If you encounter any issues or have questions, feel free to open an issue on GitHub or contact us at mushtaqmsit@gmail.com.

## **📬 Stay Connected**

Website: vu-chatbot.com
Twitter: @vu_chatbot
Facebook: VU Chatbot
LinkedIn: VU Chatbot

Thank you for choosing VU Chatbot System! Together, let's make conversations smarter and more engaging. 🌟

🙏 Special thanks 🙏 to our Virtual University of Pakistan students, reviewers, and content contributors, notably Dr Said Nabi

Star this repo if you find it useful ⭐

<details> 
<summary> <h2>📚Chapter: 1  -Literature Review</h2> </summary>

## 📚Section: 1  - **Samman Arooj**
 
|Title| Published Date| Research Questions| Model performance metrics|Research Gap|Taking Notes|Input/Target Features|Journal name/ Category|Limitations|Future Directions| 
|---|---|---|---|---|---|---|---|---|---|
|**🌐1- The development of a chatbot using Convolutional Neural Networks**| 2022 |1.How do different CNN architectures impact chatbot performance?|1.Accuracy      2.Training Speed|Did author compared  CNN chatbot to simpler models or rule-based systems? How well does it handle complex or open ended questions?| |
|**🌐2- Machine learning algorithms for teaching AI chat bots** | 2021 |1. Which machine learning algorithms are most successful in training AI chatbots for various tasks?|N/A|The paper does not cover various methods for evaluating the effectiveness of chatbot training algorithms. How can we measure a chatbot's ability to hold natural conversations, understand user intent, and generate appropriate responses?|Microservice architecture is used and the speed of message processing and preparation of responses by the chatbot will not change depending on the load on the server and the number of incoming messages. |
|**🌐3- Personified Robotic Chatbot Based On Compositional Dialogues** | 2022 |Research likely doesn't focus on specific questions but rather explores how compositional dialogues (where conversations are built from smaller elements) can be used to create a personified robotic chatbot.|N/A|1. How effectively can the level of personality be measured in these chatbots?          2.Is user perception the only metric, or can objective measures be developed?| |
| **🌐4- Boosting the Accuracy of Optimization Chatbot by Random Forest with Halving Grid Search Hyperparameter Tuning**| 2023 |1.Can hyperparameter tuning with a Halving Grid Search method improve the accuracy of an optimization chatbot built using a Random Forest algorithm?|1.Accuracy    2.Precision    3.Recall  |The paper proposes three chatbot models: 1.One without hyperparameter tuning 2.One with hyperparameter tuning using Halving Grid Search 3.One with hyperparameter tuning and the best performing settings| |   
|**🌐5- Developing a Chatbot using Machine Learning**| 2019|1.Can machine learning algorithms improve the ability of a chatbot to understand natural language queries?  2. How does the choice of machine learning model (e.g., recurrent neural networks, decision trees) impact the performance of a chatbot?|1. BLEU Score (BiLingual Evaluation Understudy)  2.Turing Test|This paper does not Investigate the impact of different visual design elements on user attention and engagement with the chatbot.| |
|**🌐6- Designing a Chatbot for Contemporary Education: A Systematic Literature Review**| 2023|What are the steps for designing an educational chatbot for contemporary education?|N/A|It focuses on the development of chatbots for education, not the impact on learners or educators.| |
|**🌐7- Research on the Design of Intelligent Chatbot Based on Deep Learning** | 2021 |It  is likely centered around improving the response generation of chatbots built with deep learning techniques.|N/A|Research gaps could exist in areas like sentiment analysis and generation of emotionally responsive dialogue.|Paper proposes an improved two-way GRU + Attention model based on the idea of mutual information, and examines the quality of the model from the final response effect. |
|**🌐8- Question Answering Model Based Conversational Chatbot using BERT Model and Google Dialogflow** | 2021 |N/A|N/A|The focus might be on question answering. Future research could explore integrating functionalities like sentiment analysis to tailor responses to user emotions or incorporating functionalities for completing tasks beyond just answering questions.|The focus of the paper seems to be on building and demonstrating the feasibility of a question-answering chatbot using BERT and Dialogflow. It describes the architecture and functionalities of the chatbot|
|**🌐9- Chatbot : A Question Answering System for Student** | 2021|It suggests the research question that  revolves around developing a chatbot system that effectively functions as a question answering system for students.|N/A|N/A|Paper discusses the design and development of such a chatbot, including the challenges of creating a system that can understand and answer student queries effectively.|
|**🌐10-QAM: Question Answering System Based on Knowledge Graph in the Military** | 2020|How can a knowledge graph-based Question Answering System (QAM) be effectively designed to be used in the military domain?|N/A|Slice of words not included in the JIEBA will be divide, which cause that the following steps can’t accuracy judged. And some unclear words often led to the system failed to judge the right answer and return a wrong answer to the user.|Research used the tool of NEO4J to build the military KG as well python to construct QA system|

##  📚Chapter: 3  **Model metrics benchmarks**

|   | f1  | precision  |  recall |  accuracy | training_time  |  inference_time |
|---|---|---|---|---|---|---|
| NB	| 0.830188679245283	| 0.8461538461538461| 0.8148148148148148| 0.8085106382978723	| 0.0032272338867187	| 0.0007801055908203|
| LR	| 0.8518518518518519	| 0.8846153846153846	| 0.8214285714285714| 0.8297872340425532| 0.0356471538543701| 0.0002150535583496|
| KNN	| 0.7058823529411765| 0.6923076923076923| 0.72|	0.6808510638297872|	0.0005688667297363	| 0.0972669124603271|
| SVM	| 0.8518518518518519	| 0.8846153846153846	| 0.8214285714285714	| 0.8297872340425532| 0.0274648666381835	| 0.0030479431152343|
| XGBoost	| 0.9122807017543859	| 1.0	| 0.8387096774193549	| 0.8936170212765957| 0.241973876953125| 0.0040738582611083984|
| RoBERTa| 0.9230769230769231| 0.9230769230769231| 0.9230769230769231	| 0.9148936170212766| 24968.250607967377| 68.44634509086609|

## 📚Chapter: 5 -**Logistic Regression**
 |Topic Name/Tutorial | Video | Code |
|---|---|---|
|[**🌐1-Classification**](https://medium.com/@Coursesteach/machine-learning-part-22-classification-b296f4c7dee4)|[**1**](https://drive.google.com/file/d/1ZTE9BwGg5kvKGPQNxObHJDyeipM6-VL8/view)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Machine_Learning.ipynb)|
|[**🌐2-Hypothesis Representation of Logistic Regression**](https://medium.com/@Coursesteach/machine-learning-part-23-hypothesis-representation-of-logistic-regression-055e0b7cd99b)|[**1**](https://drive.google.com/file/d/1nknhstSW9bmgA6lJNo2ealsyabk4i9_x/view)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Machine_Learning.ipynb)|
|[**🌐3-Decision Boundary**](https://medium.com/@Coursesteach/machine-learning-part-24-decision-boundary-bb60aff7a67d)|[**1**](https://drive.google.com/file/d/1KwzCccx2rwCBJSahz0sKFiB8hManNwHp/view)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Machine_Learning.ipynb)|
|[**🌐4-The Cost Function in Logistic Regression**](https://medium.com/@Coursesteach/machine-learning-part-25-the-cost-function-in-logistic-regression-52d9a071df5c)|[**1**](https://drive.google.com/file/d/18SJy-6jlT_cIZEMqQFwc7Mo1GDwDvC1G/view)[-2](https://www.youtube.com/watch?v=AM6BY4btj-M&list=PLqwozWPBo-FuPu4d9pFOobsCF1vDGdY_I)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Machine_Learning.ipynb)|
|[**🌐5-Simplified Cost Function and Gradient Descent**](https://medium.com/@Coursesteach/machine-learning-part-26-the-cost-function-in-logistic-regression-bfdac2557eb0)|[**1**](https://drive.google.com/file/d/1KQNr7EHCh7JFsKX3VYfnJ_-JGuFFZJqk/view)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Machine_Learning.ipynb)|
|[**🌐6-Advanced Optimization**](https://medium.com/@Coursesteach/machine-learning-part-27-advanced-optimization-a751820111b3)|[**1**](https://drive.google.com/file/d/1KQNr7EHCh7JFsKX3VYfnJ_-JGuFFZJqk/view)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Machine_Learning.ipynb)|
|[**🌐7-Multiclass Classification — One-vs-all**](https://medium.com/@Coursesteach/machine-learning-part-28-multiclass-classification-one-vs-all-f9dc5d0febbc)|[**1**](https://drive.google.com/file/d/1aXQ5dWJ-LUK2f5IpObR5I7-caSOqQq-O/view)[-2](https://www.youtube.com/watch?v=E_mN90TYnlg)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Machine_Learning.ipynb)|
|[**🌐8-Difference Between Linear Regression and Logistic Regression**](https://medium.com/@Coursesteach/machine-learning-part-29-multiclass-classification-difference-between-linear-regression-and-407ff5be2f29)|[**1**](https://www.youtube.com/watch?v=4Wb1Apftkx4)|--|

## 📚Chapter: 6 -**Regularization**
 |Topic Name/Tutorial | Video | Code |
|---|---|---|
|[**🌐1-The problem of overfitting**](https://medium.com/@Coursesteach/machine-learning-part-30-the-problem-of-overfitting-a957f68d0512)|[**1**](https://drive.google.com/file/d/12fTU40hOBNqeuBRtl-mGenm_bpRGcxH_/view)[-2](https://drive.google.com/file/d/13bQnb9hky0xbbxAq0JseUSaSUilLEvUM/view?usp=sharing)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Machine_Learning.ipynb)|
|[**🌐2-Cost Function and Regularization**](https://medium.com/@Coursesteach/machine-learning-part-31-cost-function-and-regularization-4ab26dc6c7eb)|[**1**](https://drive.google.com/file/d/1oEYWClAvVE_QUIkbC0SaLcP1mzvD-Luz/view)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Machine_Learning.ipynb)|
|[**🌐3-Regularized Linear Regression**](https://medium.com/@Coursesteach/machine-learning-part-32-regularized-linear-regression-9aaae2f83e1d)|[**1**](https://drive.google.com/file/d/1QF1OSVpHlktZ3O8959n3Qm1tPicPJvzV/view)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Machine_Learning.ipynb)|
|[**🌐4-Regularized Logistic Regression**](https://medium.com/@Coursesteach/machine-learning-part-33-regularized-logistic-regression-72e0c863c5e9)|[**1**](https://drive.google.com/file/d/19v0aIvEysNi0LYhTLI5hYwA0NNv9n7LW/view)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Machine_Learning.ipynb)|
</details>
</details>

<details> 
<summary> <h2>📚Chapter 02 -Model metrics benchmarks </h2> </summary>

   ##  📚Chapter: 3  **Model metrics benchmarks**

|   | f1  | precision  |  recall |  accuracy | training_time  |  inference_time |
|---|---|---|---|---|---|---|
| NB	| 0.830188679245283	| 0.8461538461538461| 0.8148148148148148| 0.8085106382978723	| 0.0032272338867187	| 0.0007801055908203|
| LR	| 0.8518518518518519	| 0.8846153846153846	| 0.8214285714285714| 0.8297872340425532| 0.0356471538543701| 0.0002150535583496|
| KNN	| 0.7058823529411765| 0.6923076923076923| 0.72|	0.6808510638297872|	0.0005688667297363	| 0.0972669124603271|
| SVM	| 0.8518518518518519	| 0.8846153846153846	| 0.8214285714285714	| 0.8297872340425532| 0.0274648666381835	| 0.0030479431152343|
| XGBoost	| 0.9122807017543859	| 1.0	| 0.8387096774193549	| 0.8936170212765957| 0.241973876953125| 0.0040738582611083984|
| RoBERTa| 0.9230769230769231| 0.9230769230769231| 0.9230769230769231	| 0.9148936170212766| 24968.250607967377| 68.44634509086609|
</details>


<details> 
<summary> <h2>Course 03 - 📚Supervised Learning with scikit_learn </h2> </summary>
 
  ## 📚Chapter:1-**Classification**
| Topic Name/Tutorial | Video | Code |
|---|---|---|
|[**🌐1-Classification (Supervised Learning)-Tutorial**](https://medium.com/@Coursesteach/guide-to-supervised-learning-with-scikit-learn-part-2-5acfda574e82)|[**1**](https://drive.google.com/file/d/1VYi0vfID3gu99TnTxIyJidhb_oqU8JbR/view)[**2**](https://drive.google.com/file/d/1hFMxywXWuzRKqA66jBJKerrzuZ62504z/view)[**3**](https://drive.google.com/file/d/1N4569RvW9R9pdNit6rsVQBvdFtgz8P6_/view?usp=sharing)[**4**](https://drive.google.com/file/d/1JFvHyfcQuvrQfmHUWQLRjwuAeLRjesGc/view?usp=sharing)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Supervised_%28Classification%29_ML_Model_Training_and_Evulation_.ipynb)|
| [**🌐2-Classification using Scikit-Learn-Tutorial**](https://medium.com/@Coursesteach/guide-to-supervised-learning-with-scikit-learn-part-3-c31b01c547f9)| [1](https://drive.google.com/file/d/1hFMxywXWuzRKqA66jBJKerrzuZ62504z/view) | [![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Supervised_%28Classification%29_ML_Model_Training_and_Evulation_.ipynb) |

## 📚Chapter:2-**Regression**
| Topic Name/Tutorial | Video | Code |
|---|---|---|
| [**🌐1-Regression in scikit-learn**](https://medium.com/@Coursesteach/guide-to-supervised-learning-with-scikit-learn-part-5-preprocessing-in-machine-learning-fa5b8bcb2d49) | [1](https://drive.google.com/file/d/11hqhqQMIu52nD9OcEpi5iVPD-sRjBVL6/view)[-2](https://drive.google.com/file/d/1v30FmQ2LUlUrfc3YpDT7h3CPQnTS0us_/view) | [![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Supervised_(Classification)_ML_Model_Training_and_Evulation_.ipynb) |

## 📚Chapter:3-**Data Preprocessing and Pipelines**
| Topic Name/Tutorial | Video | Code |
|---|---|---|
| [**🌐-1-Preprocessing in Machine Learning**](https://medium.com/@Coursesteach/guide-to-supervised-learning-with-scikit-learn-part-4-501068cf021) | [1](https://drive.google.com/file/d/14MyKUWqykavcOp2MNIgQjGVU1TOyqwGg/view) [-2](https://drive.google.com/file/d/19Sx937C_K5JWQYvdv7h2J2aRdiHiucAS/view?usp=sharing)| |
|[**🌐2- Importing the Data Set Using Scikit-Learn**](https://medium.com/@Coursesteach/guide-to-supervised-learning-with-scikit-learn-part-6-importing-the-dataset-6b7e133fca66)|---|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Data_Processing_in_Python_.ipynb)|
|[**🌐3-Handling missing data**](https://medium.com/@Coursesteach/supervised-learning-with-scikit-learn-part-7-handling-missing-data-b1b6263ce996)|[1](https://drive.google.com/file/d/1dN_YRnwuUf8QpUWeSnLEqHm-PtIWoPuF/view)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Data_Processing_in_Python_.ipynb)|
|[**🌐4-Data Imbalanced problem**](https://medium.com/@Coursesteach/supervised-learning-with-scikit-learn-part-8-data-imbalanced-problem-9e307c368a4d)|[1](https://drive.google.com/file/d/1Dcu0uZfT_zFmPrMUS1DkeDNKgA83Nodt/view?usp=sharing)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Data_Processing_in_Python_.ipynb)|
|[**🌐5-Data Transformation**](https://medium.com/@Coursesteach/supervised-learning-with-scikit-learn-part-9-data-transformation-b83ba14b1a2d)|[1](https://drive.google.com/file/d/14MyKUWqykavcOp2MNIgQjGVU1TOyqwGg/view)[-2](https://drive.google.com/file/d/1uY6x3O2G2f_jhngzdjUrXmwVB1o5QhEO/view?usp=sharing)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Data_Processing_in_Python_.ipynb)|
|[**🌐4-Centering and scaling.**](https://medium.com/@Coursesteach/supervised-learning-with-scikit-learn-part-10-centering-and-scaling-08c914162f81)|[1](https://drive.google.com/file/d/1gG742Q_qVbDuRbPMzJjGT_Hx1d-Joz4j/view)[-2](https://drive.google.com/file/d/1ivw7tVzaiecaJRpzoei6azhBDQySySbJ/view?usp=sharing)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Data_Processing_in_Python_.ipynb)|
|[**🌐5-Removing Outliers**](https://medium.com/@Coursesteach/supervised-learning-with-scikit-learn-part-11-removing-outliers-with-scikit-learn-59d6a2051d02)|[1](https://drive.google.com/file/d/1NhUQQx0e2s-oG6oLJKpgNxn-_NBXRQVl/view?usp=sharing)[-2](https://drive.google.com/file/d/1DdFCHKbJm8LU5mqDE9J6PbaepGxGUglY/view?usp=sharing)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Data_Processing_in_Python_.ipynb)|
|[**🌐6-Data Splitting**](https://medium.com/@Coursesteach/supervised-learning-with-scikit-learn-part-12-data-splitting-07658730bb01)|[1](https://drive.google.com/file/d/1vpTQiPWqO-_kb18Tt3L01ZMamFEAG6eT/view)[-2](https://www.youtube.com/watch?v=6dbrR-WymjI&list=PL5-da3qGB5ICeMbQuqbbCOQWcS6OYBr5A&index=8)[-3](https://drive.google.com/file/d/1nhSSLP2bejY_49r-5m2yCZuaTyv2FO38/view)[-4](https://www.youtube.com/watch?v=ivVeqv4oShk&list=PLTKMiZHVd_2KyGirGEvKlniaWeLOHhUF3&index=61)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Data_Processing_in_Python_.ipynb)|
|[**🌐7-Pipelines in scikit-learn**](https://medium.com/@Coursesteach/supervised-learning-with-scikit-learn-part-14-pipelines-in-scikit-learn-dc408eb152d1)|[1](https://drive.google.com/file/d/1A00SABP9KsLGwET-sSA03G7M3byA2j8u/view)[-2](https://www.youtube.com/watch?v=MuPmbW0ln6g&list=PLTKMiZHVd_2KyGirGEvKlniaWeLOHhUF3&index=31)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Pipelines_in_scikit_learn.ipynb)|

## 📚Chapter:4-**Measuring model performance**
| Topic Name/Tutorial | Video | Code |
|---|---|---|
| [**🌐-1-Introduction of Model Evaluation**](https://medium.com/@Coursesteach/supervised-learning-with-scikit-learn-part-15-introduction-of-model-evaluation-3906e2b1bb1a) |---|--- |
|[**🌐2- Confusion Metrix**](https://medium.com/@Coursesteach/supervised-learning-with-scikit-learn-part-16-confusion-metric-8c0dad493d92)|---|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Data_Processing_in_Python_.ipynb)|
|[**🌐3-Handling missing data**](https://medium.com/@Coursesteach/supervised-learning-with-scikit-learn-part-7-handling-missing-data-b1b6263ce996)|[1](https://drive.google.com/file/d/1dN_YRnwuUf8QpUWeSnLEqHm-PtIWoPuF/view)|[![Colab icon](https://img.shields.io/badge/Colab-Open-blue.svg?logo=colab&logoColor=white)](https://github.com/hussain0048/Machine-Learning/blob/master/Data_Processing_in_Python_.ipynb)|
</details>


<details> 
<summary> <h2>Course 01 - 🗞️📚Chapter: 3  - **Resources </h2> </summary>
   
   - [**4 Chatbot Project with python**](https://amankharwal.medium.com/4-chatbot-projects-with-python-5b32fd84af37)
   - [**Awesome Chatbot Projects**](https://github.com/fendouai/Awesome-Chatbot)
   - [**The Super Duper NLP Repo**](https://notebooks.quantumstat.com/?trk=puboslic_pt-text)
</details>


 * [**Association Mining**](https://github.com/hussain0048/Machine-Learning/tree/master/Sklearn/Association%20Mining)
   *  [Apriori_Algorithm](https://github.com/hussain0048/Machine-Learning/blob/master/Sklearn/Association%20Mining/Apriori_Algorithm%20(1).ipynb)

## Module 03 - [**Preprocessing with scikit_learn**](https://github.com/hussain0048/Machine-Learning/tree/master/Preprocessing)
  - [**Data_Processing_in_Python_.ipynb**](https://github.com/hussain0048/Machine-Learning/blob/master/Data_Processing_in_Python_.ipynb)
  - [Upload_Dataset_from_github_to_Colab.ipynb](https://github.com/hussain0048/Machine-Learning/blob/master/Preprocessing/Upload_Dataset_from_github_to_Colab.ipynb)
  - [Feature_Selection](https://github.com/hussain0048/Machine-Learning/blob/master/Feature%20Selection/Feature_Selection.ipynb)
  - [Create_new_Features_(Faker)](https://github.com/hussain0048/Machine-Learning/blob/master/Preprocessing/Create_new_Features_(Faker)_.ipynb)
  - [Give_Columns_name_to_dataset_(resize)_using_Python](https://github.com/hussain0048/Machine-Learning/blob/master/Preprocessing/Give_Columns_name_to_dataset_(resize)_using_Python.ipynb)
  - [StandardScaler in Machine Learning](https://github.com/hussain0048/Machine-Learning/blob/master/Preprocessing/StandardScaler_in_Machine_Learning.ipynb)
  - [Creating_artificial_datasets.ipynb](https://github.com/hussain0048/Machine-Learning/blob/master/Preprocessing/Creating_artificial_datasets.ipynb)
  - [Data_representation_in_scikit_learn.ipynb](https://github.com/hussain0048/Machine-Learning/blob/master/Preprocessing/Data_representation_in_scikit_learn.ipynb)
## Module 04 - [Anomaly Detection](https://github.com/hussain0048/Machine-Learning/tree/master/Preprocessing)
 - [**Anomaly_Detection.ipynb**](https://github.com/hussain0048/Machine-Learning/blob/master/Anomaly_Detection.ipynb)
 - [Anomaly_Detection_using_Using_Python library.ipynb](https://github.com/hussain0048/Machine-Learning/blob/master/Anomaly_Detection_using_Python_Library_.ipynb)

## Module -[**Recommendation System**](https://github.com/hussain0048/Machine-Learning/tree/master/Recommendation%20System)
   *  [Collaborative-Filtering](https://github.com/hussain0048/Machine-Learning/blob/master/ML0101EN_RecSys_Collaborative_Filtering_movies_py_v1.ipynb)
   *  [Content-Based](https://github.com/hussain0048/Machine-Learning/blob/master/ML0101EN_RecSys_Content_Based_movies_py_v1.ipynb)

## Module 04 - [**Model Evaluation with scikit_learn**](https://github.com/hussain0048/Machine-Learning/tree/master/Model%20Evaluation)
  - [Bias and Variance using Python](https://github.com/hussain0048/Machine-Learning/blob/master/Model%20Evaluation/Bias_and_Variance_using_Python.ipynb)
  - [hyperparameter_tuning.ipynb](https://github.com/hussain0048/Machine-Learning/blob/master/Model%20Evaluation/hyperparameter_tuning.ipynb)
  - [What_is_Cross_Validation_in_Machine_Learning_.ipynb](https://github.com/hussain0048/Machine-Learning/blob/master/Model%20Evaluation/What_is_Cross_Validation_in_Machine_Learning_.ipynb)
  - [Scikit_Plot_Visualizing_Machine_Learning_Algorithm_Results_&_Performance (1).ipynb](https://github.com/hussain0048/Machine-Learning/blob/master/Model%20Evaluation/Scikit_Plot_Visualizing_Machine_Learning_Algorithm_Results_%26_Performance%20(1).ipynb)

## Module 05 - [**Data Visualization and Exploratoration with scikit_learn**](https://github.com/hussain0048/Machine-Learning/tree/master/Data%20Visualization)
  - [Automate_Exploratory_Data_Analysis](https://github.com/hussain0048/Machine-Learning/blob/master/Data%20Visualization/Automate_Exploratory_Data_Analysis.ipynb)
  - [**Data_Exploratory_and_Ploting**](https://github.com/hussain0048/Machine-Learning/blob/master/Data_Exploratory_and_Ploting.ipynb)

## Module 06 -  [Statistics](https://github.com/hussain0048/Machine-Learning/blob/master/Statistics_for_Machine_Learning_.ipynb)
  - [**Statistics_for_Machine_Learning**](https://github.com/hussain0048/Machine-Learning/blob/master/Statistics_for_Machine_Learning_.ipynb)
  
## Module 07 - [Machine Learning with Pycaret]()  
  - [**Classification**](https://github.com/hussain0048/Machine-Learning/blob/master/Auto_Model_Training_and_Evaluation_.ipynb)
  - [**Regression**](https://github.com/hussain0048/Machine-Learning/blob/master/Regression_With_Pycaret.ipynb)
  - [**Clustering**](https://github.com/hussain0048/Machine-Learning/blob/master/Clustering_With_Pycaret.ipynb)
  - [**Anomaly Detection**](https://github.com/hussain0048/Machine-Learning/blob/master/Anomaly_Detection_with_PyCaret.ipynb)

 * [**Deep learning library**](https://github.com/hussain0048/Machine-Learning/tree/master/Deep%20Learning%20library)
   *   [FastAI_in_Machine_Learning.ipynb](https://github.com/hussain0048/Machine-Learning/blob/master/Deep%20Learning%20library/FastAI_in_Machine_Learning.ipynb) 

## Module 07 - [Distance Measure ]
   - [Distance Measure ](https://github.com/hussain0048/Machine-Learning/blob/master/Distance_Measure_.ipynb)
 
 
 ## Module 06 - Model Need to implement
  - [50 Machine Learning Algorithms Explained using Python](https://medium.com/coders-camp/50-machine-learning-algorithms-explained-using-python-8e79b1d89c98)
  - [Akramz
/
Hands-on-Machine-Learning-with-Scikit-Learn-Keras-and-TensorFlow
Public](https://github.com/Akramz/Hands-on-Machine-Learning-with-Scikit-Learn-Keras-and-TensorFlow)
  - [Data Cleaning with Python](https://medium.com/bitgrit-data-science-publication/data-cleaning-with-python-f6bc3da64e45)
  - [70+ Machine Learning Algorithms & Models Explained with Python](https://medium.com/coders-camp/all-machine-learning-algorithms-models-explained-adcd95d5fb3c)
  - [Interpreting Tree-Based Model's Prediction of Individual Sample](https://coderzcolumn.com/tutorials/machine-learning/treeinterpreter-interpreting-tree-based-models-prediction-of-individual-sample?fbclid=IwAR2-zcjOO-c3XfiDoG6eufSmBaFz9mnrislreMJF6NluNUAwZZWCWtM8kYI)
  - [Predicting presence of Heart Diseases using Machine Learning](https://towardsdatascience.com/predicting-presence-of-heart-diseases-using-machine-learning-36f00f3edb2c)
  - [How to Master Scikit-learn for Data Science](https://towardsdatascience.com/how-to-master-scikit-learn-for-data-science-c29214ec25b0)
  - [All Machine Learning Algorithms & Models Explained](https://medium.com/coders-camp/all-machine-learning-algorithms-models-explained-adcd95d5fb3c)
  - [Python AI: How to Build a Neural Network & Make Predictions](https://realpython.com/python-ai-neural-network/?fbclid=IwAR2AAOh0PhQU2IjIgPA__4YR_9MnR1rFBCgDVCk2A2Xxi92oDT8zn0qJJ0A)
  - [60 Machine Learning Algorithms & Models Explained with Python](https://medium.com/coders-camp/all-machine-learning-algorithms-models-explained-adcd95d5fb3c)
  - [ageron/handson-ml2](https://github.com/ageron/handson-ml2)
  - [All Machine Learning Algorithms & Models with Python](https://medium.com/coders-camp/all-machine-learning-algorithms-models-explained-adcd95d5fb3c)
  - [How to Master Scikit-learn for Data Science](https://towardsdatascience.com/how-to-master-scikit-learn-for-data-science-c29214ec25b0)
  - [rushter/MLAlgorithms](https://github.com/rushter/MLAlgorithms)
  - [80+ Machine Learning Algorithms & Models Explained with Python](https://medium.com/coders-camp/all-machine-learning-algorithms-models-explained-adcd95d5fb3c)
  - [5x12themlsbook](https://github.com/5x12/themlsbook)
  - [edyoda data-science-complete-tutorial](https://github.com/edyoda/data-science-complete-tutorial)
  - [ageron handson-ml Public](https://github.com/ageron/handson-ml)
 </details>
   
## 💻 Workflow:

- Fork the repository

- Clone your forked repository using terminal or gitbash.

- Make changes to the cloned repository

- Add, Commit and Push

- Then in Github, in your cloned repository find the option to make a pull request 

> print("Start contributing for Machine Learning")
>
## ⚙️ Things to Note

* Make sure you do not copy codes from external sources because that work will not be considered. Plagiarism is strictly not allowed.
* You can only work on issues that have been assigned to you.
* If you want to contribute the algorithm, it's preferrable that you create a new issue before making a PR and link your PR to that issue.
* If you have modified/added code work, make sure the code compiles before submitting.
* Strictly use snake_case (underscore_separated) in your file_name and push it in correct folder.
* Do not update the **[README.md](https://github.com/prathimacode-hub/ML-ProjectKart/blob/main/README.md).**

 🔍 **Explore more👋🛒**
 
Explore cutting-edge tools and Python libraries, access insightful slides and source code, and tap into a wealth of free online courses from top universities and organizations. Connect with like-minded individuals on Reddit, Facebook, and beyond, and stay updated with our YouTube channel and GitHub repository. Don’t wait — enroll now and unleash your Machine Learning  potential!”

* [**Supervised learning with scikit-learn**](https://coursesteach.com/enrol/index.php?id=21)
* [**Fundamental of Machine Learning**](https://coursesteach.com/enrol/index.php?id=6)

<a href="https://app.commanddash.io/agent?github=<your github repo>"><img src="https://img.shields.io/badge/AI-Code%20Gen-EB9FDA"></a>



## **✨Top Contributors**
We would love your help in making this repository even better! If you know of an amazing AI course that isn't listed here, or if you have any suggestions for improvement in any course content, feel free to open an issue or submit a course contribution request.

                       Together, let's make this the best AI learning hub website! 🚀

Thanks goes to these Wonderful People. Contributions of any kind are welcome!🚀

<a href="https://github.com/hussain0048/VU-Chatbot-System/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=hussain0048/VU-Chatbot-System" />
</a>






