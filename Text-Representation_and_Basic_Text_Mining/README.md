<h1 align="center">Text Representation and Basic Text Mining</h1>

<p align="center">
  <b>Introductory Natural Language Processing Notebook</b><br>
  Understanding classical text representation methods and basic text mining concepts.
</p>

<br>

<h2>Project Overview</h2>

<p>
This notebook is an introductory exploration of fundamental concepts in
Natural Language Processing (NLP), focused on text representation methods
and basic text mining techniques.
</p>

<p>
Unlike a fully application-oriented project, this notebook is designed with a
strong theoretical and analytical perspective. The objective is to understand
how classical NLP representations work mathematically, how they behave in
small examples, and what their strengths and limitations are in practice.
</p>

<p>
The notebook manually constructs and analyzes simple examples using three
sentences to study the behavior of:
</p>

<ul>
  <li>Term Frequency (TF)</li>
  <li>Inverse Document Frequency (IDF)</li>
  <li>TF-IDF representation</li>
  <li>Basic text mining interpretation</li>
</ul>

<p>
The project compares:
</p>

<ol>
  <li>Manual mathematical computation of TF, IDF, and TF-IDF</li>
  <li>Automated implementation using Scikit-learn</li>
  <li>Differences between theoretical calculations and library outputs</li>
</ol>

<br>

<h2>Objectives</h2>

<p>
The main goals of this notebook are:
</p>

<ul>
  <li>Understand the mathematical intuition behind TF and TF-IDF</li>
  <li>Explore how words are represented numerically in NLP</li>
  <li>Analyze the importance of terms across documents</li>
  <li>Compare manual computations against Scikit-learn implementations</li>
  <li>Develop analytical reasoning about representation effectiveness</li>
  <li>Study the limitations and interpretability of classical vector-space models</li>
</ul>

<br>

<h2>NLP Topics Covered</h2>

<p>
<span style="background-color:#eef;padding:5px 10px;border-radius:10px;">Text Representation</span>
<span style="background-color:#eef;padding:5px 10px;border-radius:10px;">Bag of Words</span>
<span style="background-color:#eef;padding:5px 10px;border-radius:10px;">Term Frequency</span>
<span style="background-color:#eef;padding:5px 10px;border-radius:10px;">Inverse Document Frequency</span>
<span style="background-color:#eef;padding:5px 10px;border-radius:10px;">TF-IDF</span>
<span style="background-color:#eef;padding:5px 10px;border-radius:10px;">Sparse Vectors</span>
<span style="background-color:#eef;padding:5px 10px;border-radius:10px;">Basic Text Mining</span>
<span style="background-color:#eef;padding:5px 10px;border-radius:10px;">Feature Engineering</span>
<span style="background-color:#eef;padding:5px 10px;border-radius:10px;">Scikit-learn</span>
</p>

<br>

<h2>Methodology</h2>

<h3>1. Manual Example Construction</h3>

<p>
Three example sentences are created and analyzed manually to understand
how words are transformed into numerical representations.
</p>

<h3>2. Frequency Analysis</h3>

<p>
Word frequencies are computed step by step to analyze term distribution
across documents.
</p>

<h3>3. TF and IDF Computation</h3>

<p>
The notebook manually applies the mathematical formulations of:
</p>

<p align="center">
  <b>TF(t,d)</b>
</p>

<p align="center">
  <b>IDF(t)</b>
</p>

<p align="center">
  <b>TFIDF(t,d) = TF(t,d) × IDF(t)</b>
</p>

<h3>4. Scikit-learn Implementation</h3>

<p>
The same examples are implemented using Scikit-learn vectorizers to compare:
</p>

<ul>
  <li>Numerical differences</li>
  <li>Normalization effects</li>
  <li>Smoothing strategies</li>
  <li>Implementation behavior</li>
</ul>

<h3>5. Analytical Discussion</h3>

<p>
The notebook includes conceptual questions and reflections regarding:
</p>

<ul>
  <li>Representation effectiveness</li>
  <li>Word importance</li>
  <li>Sparsity</li>
  <li>Interpretability</li>
  <li>Advantages and limitations of TF-IDF</li>
</ul>

<br>

<h2>Repository Purpose</h2>

<p>
This project is not intended to be a complete production-oriented NLP pipeline.
Instead, it serves as an educational notebook focused on conceptual understanding,
mathematical intuition, and analytical discussion of classical NLP representation methods.
</p>

<br>

<h2>Technologies Used</h2>

<ul>
  <li>Python</li>
  <li>Jupyter Notebook</li>
  <li>Scikit-learn</li>
  <li>NumPy</li>
  <li>Pandas</li>
</ul>

<br>

<h2>Authors</h2>

<ul>
  <li><b>Code and Analysis:</b> Alessa Melo</li>
  <li><b>Professor:</b> PhD Diego Peluffo</li>
</ul>

<br>

<h2 align="center">Educational Focus</h2>

<p align="center">
Building foundational intuition for NLP representation learning through
mathematical analysis and implementation comparison.
</p>