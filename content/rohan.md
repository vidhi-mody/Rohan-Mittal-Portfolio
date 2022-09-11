+++
title = "About"
+++

## Education

**University of Massachusetts Amherst** (Sep 2021 – Dec 2022) \
M.S. Computer Science \
GPA: 3.75/4.0 

**Shiv Nadar University** (July 2016 – July 2020) \
B.Tech. Computer Science and Engineering with minor in Mathematics \
GPA: 9.1/10

## Professional Experience

**Roostify** (June - Aug 2022) \
Engineering Intern 
- Automating a bank-transaction category identification task using transformer based models trained on the transaction description text. Framework: Pytorch, HuggingFace - Transformers
- Creating visualisation reports and dashboards using SQL and LookML for gaining insights into mortgage underwriting conditions data

## Publications

In chronological order:
1. Mishra, P., & Mittal, R. (2021). NeuralNERE: Neural Named Entity Relationship Extraction for End-to-End Climate Change Knowledge Graph Construction. In Tackling Climate Change with Machine Learning Workshop at ICML.
2. Jain, S., Mittal, R., Jain, A., & Sinha, A. (2019, September). An efficient framework for monitoring tree cover in an area through aerial images. In Applications of machine learning (Vol. 11139, pp. 327-333). SPIE.
3. Jain, S., Mittal, R., Mishra, P., & Sinha, A. (2019, September). Road network mapping from aerial images. In Applications of Machine Learning (Vol. 11139, pp. 321-326). SPIE.


## Projects

**Climate change knowledge graph construction** | Natural Language Processing
- Developed an end-to-end deep learning based model for extracting the intended relationship phrase given subject and
object entity pairs directly using raw text of relevant news articles
- Proposed an unsupervised learning scheme for obtaining the subject - relationship - object triplets for constructing a
knowledge graph
- Created the dataset by web scraping over 11k climate change news articles from the Science Daily website
- Accepted in Tackling Climate Change using Machine Learning workshop at [ICML 2021](https://www.climatechange.ai/papers/icml2021/76)


**Sentiment Analysis on Code-Mixed Languages** | Python, Pytorch, HuggingFace
- Fine-tuned a baseline Distil m-BERT model for the task of sentiment analysis on code-mixed Hinglish language
- Implemented data augmentation techniques including backtranslation using two separately trained mt5 models; as well as
transliteration through Google translate
- Implemented a modified tokenization scheme by tuning the model tokenizer on the training set
- Visualized attention maps of the sentiment analysis models for increased model interpretability


**Music Thumbnailing through Artist Recognition** | Python, Pytorch, Scikit-Learn, NumPy
- Implemented and trained an attention-based neural network model on the task of music artist recognition
- Generated music thumbnails using attention scores for each song segment
- Verified the efficacy of the attention based model by evaluating the attention score results using a separately trained
convolutional recurrent neural network (CRNN) model
- Observed an increase from 55% accuracy on the lowest attention score segments to 74% accuracy on the highest attention
score segments using the CRNN model

**Monitoring tree cover in an area through aerial images** | Python, Tensorflow, NumPy
- Adopted the Mask R-CNN model for the task of tree instance segmentation and counting, through transfer learning
- Used a Gist Feature based sampling technique to minimize the amount of training data required for scaling the model to
regions with varied geographical features
- Published in [Proc. SPIE, Applications of Machine Learning 2019](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/11139/2529442/An-efficient-framework-for-monitoring-tree-cover-in-an-area/10.1117/12.2529442.short?SSO=1)
  
**Covid-19 Visualisation Dashboard** | Javascript, D3.js, HTML, CSS, Bootstrap
- Built an interactive covid-19 visualization dashboard for depicting the number of covid cases, state-wise, through time
using a color gradient based approach
- Combined the covid-19 data with state-wise mental health care data to interactively visualize the trend between covid-19
and mental health cases in each state