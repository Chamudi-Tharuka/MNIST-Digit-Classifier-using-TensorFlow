# 📘 MNIST Digit Classifier using TensorFlow</p>
<p>A simple machine learning project that trains a neural network to recognize handwritten digits (0–9) using the MNIST dataset.<br>
This project is built using TensorFlow &amp; Keras, and runs perfectly in Google Colab or VS Code.</p><br>

# <p>📌 Project Overview</p>
<p>This project uses a fully connected neural network to classify grayscale digit images (28×28 pixels).<br>
It serves as an excellent beginner-friendly introduction to:</p>
<ul>
  <li>Neural Networks</li>
  <li>TensorFlow / Keras</li>
  <li>Data preprocessing</li>
  <li>>Model training & evaluation</li>
</ul><br>

# <p>🧠 Technologies Used</p>
<ul>
  <li>Python</li>
  <li>TensorFlow</li>
  <li>Keras</li>
  <li>NumPy</li>
  <li>Google Colab, Jupyter Notebook</li>
</ul><br>

#  <p>📂 Dataset</p>
<p>This project uses the built-in MNIST dataset, which contains:</p><br>
<ul>
  <li>60,000 training images</li>
  <li>10,000 testing images</li>
  <li>Each image is a handwritten digit from 0–9.</li>
</ul><br>

# <p>🧩 Model Architecture</p>
<ul>
  <p>The model architecture is simple and effective:</p>
  <li>Flatten → Dense(128, relu) → Dropout(0.2) → Dense(10)</li>
  <li>Flatten converts the 28×28 pixel grid into a 784-length vector</li>
  <li>Dense(128) adds a fully connected hidden layer</li>
  <li>Dropout(0.2) reduces overfitting</li>
  <li>Dense(10) outputs class scores for digits 0–9</li>
</ul><br>

# 📊 Results
<ul>
  <li>Achieves around 97–98% accuracy on test data</li>
  <li>Simple & fast training</li>
  <li>Perfect for beginners learning ML</li>
</ul><br>

# 🚀 How to Run the Project
<p>Option 1 — Google Colab (Recommended)</p>
<ol>
  <li>Upload the .ipynb file to Google Colab</li>
  <li>Click Runtime → Run All</li>
  <li>Done!</li>
</ol>

<p>Option 2 — VS Code / Local PC</p>
<ol>
  <li>Install Python</li>
  <li>Install required libraries:</li>
    <ul>
      <li>pip install tensorflow numpy</li>
    </ul>
  <li>Run the notebook or script.</li>
</ol><br>

# ⭐ Future Improvements
<ul>
  <li>Convert to a Convolutional Neural Network (CNN)</li>
  <li>Add digit visualization</li>
  <li>Deploy model as a web app</li>
  <li>Add confusion matrix</li>
</ul>
























