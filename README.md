<h1 align="center">📷 Image Quality Analysis System</h1>
<h3 align="center">Computer Vision using OpenCV</h3>

<hr/>

<h2>🚀 Project Overview</h2>
<p>
This project implements an image quality assessment system using Computer Vision techniques.
It evaluates image sharpness, brightness, contrast, and noise levels using OpenCV.
</p>

<hr/>

<h2>🧠 Implemented Features</h2>

<ul>
<li>🔍 Blur Detection using Laplacian Variance</li>
<li>🌗 Brightness Level Estimation</li>
<li>🎨 Contrast Analysis</li>
<li>📡 Noise Detection</li>
</ul>

<hr/>

<h2>📊 Methodology</h2>

<h3>1️⃣ Blur Detection</h3>
<p>
Laplacian operator is applied to compute image sharpness. 
Low variance indicates a blurred image.
</p>

<h3>2️⃣ Contrast Evaluation</h3>
<p>
Standard deviation of grayscale intensity is used to measure contrast.
</p>

<h3>3️⃣ Brightness Measurement</h3>
<p>
Mean grayscale intensity determines overall brightness level.
</p>

<h3>4️⃣ Noise Estimation</h3>
<p>
Laplacian standard deviation is used to estimate noise intensity.
</p>

<hr/>

<h2>📂 Project Structure</h2>

<pre>
image-quality-analysis-cv/
│
├── Blur_detection_using_laplacian.py
├── images/
│   └── input.jpg
├── README.md
└── requirements.txt
</pre>

<hr/>

<h2>⚙️ How to Run</h2>

<pre>
git clone &lt;repository-link&gt;
cd image-quality-analysis-cv
pip install -r requirements.txt
python Blur_detection_using_laplacian.py
</pre>

<hr/>

<h2>🛠 Requirements</h2>

<pre>
opencv-python
numpy
</pre>

<hr/>

<h2>💡 Engineering Highlights</h2>

<ul>
<li>Classical Computer Vision techniques</li>
<li>Image quality diagnostics</li>
<li>Practical use cases in photography and surveillance systems</li>
</ul>

<hr/>

<div align="center">
<h3>👨‍💻 Developed by abdelkreem abdelhaleem frahat</h3>
<p>AI Engineer | Computer Vision | Deep Learning</p>
</div>
