<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Detecting Spam Emails with Machine Learning</title>
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6; padding: 20px; max-width: 800px; margin: auto;">

  <h1>📧 Detecting Spam Emails with Machine Learning</h1>
  <p>
    Spam emails flood our inboxes daily. In this project, I built a machine learning pipeline to 
    <strong>detect and classify spam messages</strong> using Python and natural language processing (NLP) techniques.
  </p>

  <h2>🔍 Project Overview</h2>
  <p>
    This project demonstrates a complete workflow for building a <strong>spam detection system</strong>. It includes:
  </p>
  <ul>
    <li>Data preprocessing</li>
    <li>Exploratory Data Analysis (EDA)</li>
    <li>Text cleaning</li>
    <li>Vectorization</li>
    <li>Model training and evaluation</li>
  </ul>
  <p>The aim is to distinguish between <strong>ham (legitimate)</strong> and <strong>spam</strong> emails using supervised learning techniques.</p>

  <h2>📂 Dataset</h2>
  <ul>
    <li><strong>Source:</strong> Public spam/ham dataset (CSV format)</li>
    <li><strong>Columns:</strong> <code>label</code> (spam/ham), <code>text</code> (email message)</li>
    <li><strong>Balanced:</strong> Ham downsampled to match spam count</li>
  </ul>

  <h2>⚙️ Technologies & Libraries Used</h2>
  <table border="1" cellpadding="8" cellspacing="0">
    <tr><th>Category</th><th>Tools</th></tr>
    <tr><td>Language</td><td>Python</td></tr>
    <tr><td>Data Handling</td><td>Pandas, NumPy</td></tr>
    <tr><td>Visualization</td><td>Matplotlib, Seaborn, WordCloud</td></tr>
    <tr><td>NLP Preprocessing</td><td>NLTK, string</td></tr>
    <tr><td>Machine Learning</td><td>TensorFlow (Keras), Scikit-learn</td></tr>
    <tr><td>Other</td><td>Warnings, Streamlit (optional)</td></tr>
  </table>

  <h2>🧹 Text Preprocessing Steps</h2>
  <ol>
    <li>Label encoding</li>
    <li>Removing "Subject" text</li>
    <li>Punctuation removal</li>
    <li>Lowercasing</li>
    <li>Stopword removal</li>
    <li>Tokenization</li>
    <li>Sequence padding</li>
  </ol>

  <h2>🧠 Model Architecture</h2>
  <ul>
    <li><strong>Framework:</strong> Keras (with TensorFlow backend)</li>
    <li><strong>Loss Function:</strong> binary_crossentropy</li>
    <li><strong>Optimizer:</strong> Adam</li>
    <li><strong>Callbacks:</strong> EarlyStopping, ReduceLROnPlateau</li>
  </ul>

  <h2>📊 Evaluation Metrics</h2>
  <ul>
    <li>Accuracy</li>
    <li>Confusion Matrix</li>
    <li>Precision, Recall, F1 Score</li>
  </ul>

  <h2>🚀 How to Run the Project</h2>
  <ol>
    <li>Clone the repository:
      <pre><code>git clone https://github.com/yourusername/Detecting_spam_email.git
cd Detecting_spam_email</code></pre>
    </li>
    <li>Install the required libraries:
      <pre><code>pip install -r requirements.txt</code></pre>
    </li>
    <li>Run the notebook:
      <pre><code>jupyter notebook Detecting_spam_email.ipynb</code></pre>
    </li>
  </ol>

  <h2>🎨 Sample Visuals</h2>
  <ul>
    <li>WordClouds for Ham and Spam</li>
    <li>Class distribution bar chart</li>
    <li>Accuracy and loss training curves</li>
  </ul>

  <h2>📌 Project Status</h2>
  <ul>
    <li>✅ Complete</li>
    <li>🔄 Future: Add real-time input & web interface (Streamlit)</li>
  </ul>

  <h2>🙋‍♂️ Author</h2>
  <p>
    <strong>Talha Zulfiqar</strong><br>
    📧 <a href="mailto:zulfiqartalha426@gmail.com">zulfiqartalha426@gmail.com</a><br>
    📍 Lahore, Pakistan
  </p>

  <h2>🌐 Connect With Me</h2>
  <ul>
    <li><a href="https://www.linkedin.com/in/talhazulfiqar" target="_blank">LinkedIn</a></li>
    <li><a href="https://github.com/yourusername" target="_blank">GitHub</a></li>
  </ul>

  <h2>📄 License</h2>
  <p>This project is licensed under the MIT License - see the <code>LICENSE</code> file for details.</p>

</body>
</html>
