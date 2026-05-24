<h1 align="center">NLP Text Classification and Embeddings</h1>

<p align="center">
  <b>Natural Language Processing Project</b><br>
  Comparative study of multiple text representation, preprocessing strategies,
  and classification architectures.
</p>

<hr>

<h2>Project Overview</h2>

<p>
This repository contains an introductory exploration of fundamental concepts in
Natural Language Processing (NLP), focused on <b>text classification</b>,
<b>text preprocessing</b>, and <b>representation learning techniques</b>.
</p>

<p>
The project evaluates and compares different NLP architectures ranging from
traditional statistical approaches to more advanced embedding-based methods.
The notebooks are organized progressively to facilitate understanding of the
evolution of NLP preprocessing pipelines and text representation strategies.
</p>

<hr>

<h2>NLP Topics Covered</h2>

<p>
<span style="background-color:#eef;padding:4px 8px;border-radius:8px;">Text Classification</span>
<span style="background-color:#eef;padding:4px 8px;border-radius:8px;">Bag of Words</span>
<span style="background-color:#eef;padding:4px 8px;border-radius:8px;">TF-IDF</span>
<span style="background-color:#eef;padding:4px 8px;border-radius:8px;">Word Embeddings</span>
<span style="background-color:#eef;padding:4px 8px;border-radius:8px;">Advanced Embeddings</span>
<span style="background-color:#eef;padding:4px 8px;border-radius:8px;">NLP Preprocessing</span>
<span style="background-color:#eef;padding:4px 8px;border-radius:8px;">Model Comparison</span>
<span style="background-color:#eef;padding:4px 8px;border-radius:8px;">Feature Engineering</span>
</p>

<hr>

<h2>Repository Structure</h2>

<pre>
📦 Text-Classification-and-Embeddings
│
├── 📁 Baseline_Model
│   ├── TF-IDF experiments
│   └── Bag-of-Words experiments
│
├── 📁 Word_Embedding
│   └── Classical embedding approaches
│
├── 📁 Advanced_Embeddings
│   └── Advanced embedding architectures
│
├── 📁 Comparisons
│   └── Comparative analysis between models
│
├── 📁 preprocessed_data_pipeline_0
│   └── Raw dataset splits without preprocessing
│
├── 📁 preprocessed_data_pipeline_1
│   └── Stopword removal + lemmatization
│
├── 📁 preprocessed_data_pipeline_2
│   └── Lemmatization without stopword removal
│
├── 📁 preprocessed_data_pipeline_3
│   └── Stopword removal without lemmatization
│
├── 📄 IMDB_EDA.ipynb
│   └── Exploratory Data Analysis of the IMDB dataset
│
└── 📄 IMDB_Preprocessing.ipynb
    └── NLP preprocessing pipelines and dataset generation
</pre>

<hr>

<h2>Preprocessing Pipelines</h2>

<p>
The project includes multiple preprocessing pipelines designed to analyze how
different text normalization strategies affect NLP model performance.
</p>

<table>
<tr>
<th>Pipeline</th>
<th>Description</th>
</tr>

<tr>
<td><b>Pipeline 0</b></td>
<td>Raw dataset without preprocessing</td>
</tr>

<tr>
<td><b>Pipeline 1</b></td>
<td>Lowercasing + stopword removal + lemmatization</td>
</tr>

<tr>
<td><b>Pipeline 2</b></td>
<td>Lowercasing + lemmatization without stopword removal</td>
</tr>

<tr>
<td><b>Pipeline 3</b></td>
<td>Lowercasing + stopword removal without lemmatization</td>
</tr>

</table>

<p>
Each preprocessing pipeline generates independent:
</p>

<ul>
  <li>Training datasets</li>
  <li>Validation datasets</li>
  <li>Testing datasets</li>
</ul>

<p>
This structure enables reproducible experimentation across multiple NLP
architectures and preprocessing configurations.
</p>

<hr>

<h2>Project Objective</h2>

<p>
The primary goal of this project is to analyze how different preprocessing
strategies and text representation methods influence classification performance
in NLP tasks.
</p>

<p>
The repository progresses from:
</p>

<ul>
  <li>Raw textual representations</li>
  <li>Classical statistical representations (Bag of Words, TF-IDF)</li>
  <li>Preprocessed and normalized textual datasets</li>
  <li>Dense vector representations (Word Embeddings)</li>
  <li>Advanced embedding techniques</li>
  <li>Comparative evaluation between preprocessing pipelines and architectures</li>
</ul>

<hr>

<h2>Dataset</h2>

<p>
The experiments are conducted using the <b>IMDB Movie Reviews Dataset</b>,
commonly used for sentiment analysis and NLP benchmarking tasks.
</p>

<p>
The dataset is divided into:
</p>

<ul>
  <li>Training set</li>
  <li>Validation set</li>
  <li>Testing set</li>
</ul>

<p>
for each preprocessing pipeline independently.
</p>

<hr>

<h2>Authors</h2>

<ul>
  <li><b>Code and Implementation:</b> Alessa Melo</li>
  <li><b>Professor:</b> PhD Diego Peluffo</li>
</ul>

<hr>

<h2>Technologies Used</h2>

<p>
<span style="background-color:#eef;padding:6px 12px;border-radius:10px;">Python</span>
<span style="background-color:#eef;padding:6px 12px;border-radius:10px;">Jupyter Notebook</span>
<span style="background-color:#eef;padding:6px 12px;border-radius:10px;">Scikit-learn</span>
<span style="background-color:#eef;padding:6px 12px;border-radius:10px;">NLTK</span>
<span style="background-color:#eef;padding:6px 12px;border-radius:10px;">NumPy</span>
<span style="background-color:#eef;padding:6px 12px;border-radius:10px;">Pandas</span>
</p>

<hr>

<h2 align="center">Introduction to NLP Representation Learning</h2>

<p align="center">
Understanding how preprocessing strategies and representation methods influence
machine understanding of natural language.
</p>