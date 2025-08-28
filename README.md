<h1 align="center">👕 Virtual Try-On AI</h1>

<p align="center">
  <strong>AI-powered Virtual Try-On System</strong><br>
  Built with <code>Roboflow</code>, <code>Ultralytics SAM</code>, and <code>Segmind SDXL</code>
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
This project is an AI-based Virtual Try-On tool.  
Users can upload their own image, select <strong>upper</strong> or <strong>lower body</strong>, and generate new clothing styles with text prompts.  
The system combines <strong>object detection</strong> (Roboflow), <strong>segmentation</strong> (Ultralytics SAM), and <strong>inpainting</strong> (Segmind SDXL API).
</p>

<ul>
  <li>🎯 Automatic region detection (upper/lower)</li>
  <li>✂️ Smart segmentation with SAM</li>
  <li>🖌️ Inpainting with custom clothing prompts</li>
  <li>📷 Instant visualization of results</li>
</ul>

<hr>

<h2>🚀 Features</h2>

<ul>
  <li>📤 Upload your own image in Google Colab</li>
  <li>👕 Select clothing region (upper / lower)</li>
  <li>🎨 Describe clothing style (e.g., "A Hawaiian shirt")</li>
  <li>⚡ Generates realistic try-on results using Segmind SDXL</li>
</ul>

<hr>

<h2>🧠 How It Works</h2>

<ol>
  <li>Upload your image in Google Colab</li>
  <li>Run Roboflow model to detect clothing regions</li>
  <li>Use Ultralytics SAM for segmentation mask</li>
  <li>Send image + mask + clothing prompt to Segmind API</li>
  <li>Get your virtual try-on result instantly!</li>
</ol>

<hr>

<h2>📂 Folder Structure</h2>

<pre>
virtual-tryon-ai/
│
├── Virtual Try-On.ipynb    ← Main Colab Notebook
├── requirements.txt        ← Dependencies
└── README.md               ← Documentation
</pre>

<hr>

<h2>⚙️ Setup Instructions</h2>

<ol>
  <li>Clone the repository</li>
  
  <pre><code>git clone https://github.com/yourusername/virtual-tryon-ai.git</code></pre>

  <li>Install dependencies</li>

  <pre><code>pip install -r requirements.txt</code></pre>

  <li>Open the notebook in Google Colab and run step by step</li>
</ol>

<hr>

<h2>🔑 API Keys</h2>

<p>
You will need free API keys:
</p>

<ul>
  <li><strong>Roboflow API Key</strong> → for detection</li>
  <li><strong>Segmind API Key</strong> → for inpainting</li>
</ul>

Store them safely inside the notebook (or use <code>.env</code> file if running locally).

<hr>

<h2>🙌 Credits</h2>

<p>
Created by <strong>Mehadi Hassan</strong> using Roboflow + SAM + Segmind.  
</p>

<hr>

<p align="center">⭐ Star this repo if you find it useful!</p>
