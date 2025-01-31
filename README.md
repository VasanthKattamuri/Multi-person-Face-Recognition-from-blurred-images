<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>

<h1>Multi-person Face Recognition from Blurred Images</h1>

<h2>Overview</h2>
<p>This project focuses on improving multi-person face recognition in blurred images using Deep Learning techniques. It enhances recognition accuracy by preprocessing and augmenting the <b>"Images of Groups"</b> dataset with noise reduction methods. Transfer Learning with AlexNet is leveraged to optimize feature extraction and improve recognition precision in challenging scenarios such as occlusion and pose variations.</p>

<h2>Problem Statement</h2>
<p>Face recognition from blurred images is a challenging task, especially in real-world scenarios where occlusion, pose variations, and noise significantly impact accuracy. Traditional models struggle to extract meaningful features from such images. This project addresses these issues using advanced image preprocessing techniques and Deep Learning models.</p>

<h2>Approach</h2>

<h3>1. Data Preprocessing & Augmentation</h3>
<ul>
    <li>Used the <b>"Images of Groups"</b> dataset, containing group photos with varying levels of occlusion and pose variations.</li>
    <li>Applied <b>MATLAB and OpenCV</b> for image preprocessing:</li>
    <ul>
        <li><b>Noise Reduction:</b> Used <b>Gaussian blur filtering</b> and <b>edge-preserving smoothing</b> to enhance image quality.</li>
        <li><b>Data Augmentation:</b> Performed transformations like rotation, scaling, and brightness adjustments to improve model generalization.</li>
    </ul>
</ul>

<h3>2. Feature Extraction & Model Development</h3>
<ul>
    <li><b>Deep Learning techniques</b> were applied to recognize faces in blurred images.</li>
    <li><b>Transfer Learning with AlexNet</b> was used for feature extraction, enabling efficient learning from pre-trained models.</li>
    <li>Fine-tuned AlexNet on the dataset to improve recognition accuracy in challenging conditions.</li>
</ul>

<h3>3. Model Optimization & Evaluation</h3>
<ul>
    <li><b>Performance Improvements:</b></li>
    <ul>
        <li>Noise reduction techniques increased model accuracy by <b>20%</b>.</li>
        <li>Transfer Learning improved feature extraction efficiency.</li>
    </ul>
    <li><b>Evaluation Metrics:</b> Used <b>accuracy, precision, recall, and F1-score</b> to assess the model's performance.</li>
</ul>

<h2>Key Features</h2>
<ul>
    <li>Preprocessed and augmented images for better recognition accuracy.</li>
    <li>Applied <b>Gaussian blur filtering</b> and <b>edge-preserving smoothing</b> for noise reduction.</li>
    <li>Utilized <b>Transfer Learning with AlexNet</b> for feature extraction and classification.</li>
    <li>Addressed challenges like <b>occlusion, pose variations, and noise</b> in blurred images.</li>
</ul>

<h2>Tools & Technologies Used</h2>
<ul>
    <li><b>Programming Language:</b> Python</li>
    <li><b>Libraries & Frameworks:</b> OpenCV, TensorFlow/Keras, PyTorch, MATLAB</li>
    <li><b>Techniques:</b> Transfer Learning, Image Preprocessing, Feature Extraction, Deep Learning</li>
</ul>

<h2>Installation & Setup</h2>

<ol>
    <li><b>Clone the repository:</b></li>
    <pre><code>git clone https://github.com/VasanthKattamuri/multi-person-face-recognition.git
cd multi-person-face-recognition</code></pre>

    <li><b>Install dependencies:</b></li>
    <pre><code>pip install -r requirements.txt</code></pre>

    <li><b>Run the notebook or script:</b></li>
    <ul>
        <li>Open <b>Google Colaboratory</b> or Jupyter Notebook.</li>
        <li>Load the dataset and execute the preprocessing steps.</li>
        <li>Train the model using the provided scripts.</li>
    </ul>
</ol>

<h2>Usage</h2>
<ul>
    <li>Load the dataset into the notebook.</li>
    <li>Run preprocessing steps for noise reduction and augmentation.</li>
    <li>Train the model using AlexNet for feature extraction.</li>
    <li>Evaluate the model's performance on test data.</li>
</ul>

<h2>Dataset</h2>
<ul>
    <li>Used the <b>"Images of Groups"</b> dataset containing real-world blurred group images.</li>
    <li>Includes diverse facial occlusions, lighting conditions, and pose variations.</li>
</ul>

<h2>Results</h2>
<ul>
    <li>Achieved <b>20% improvement</b> in accuracy using noise reduction techniques.</li>
    <li>Enhanced recognition precision in <b>occlusion and pose variation scenarios</b>.</li>
</ul>

<h2>Future Work</h2>
<ul>
    <li>Experiment with <b>advanced CNN architectures</b> like ResNet or Vision Transformers.</li>
    <li>Develop an <b>AI-based real-time face recognition system</b> for surveillance.</li>
    <li>Implement <b>GAN-based image enhancement</b> to improve blurred images before recognition.</li>
</ul>

<h2>Contributing</h2>
<p>Contributions are welcome! Fork the repository and submit a pull request for improvements.</p>

</body>
</html>
