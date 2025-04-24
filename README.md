<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Zomato Gen AI - README</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      max-width: 900px;
      margin: 0 auto;
      padding: 20px;
      background: #fefefe;
      color: #333;
    }
    h1, h2, h3 {
      color: #d9230f;
    }
    code {
      background: #eee;
      padding: 2px 6px;
      border-radius: 4px;
    }
    pre {
      background: #f4f4f4;
      padding: 10px;
      overflow-x: auto;
      border-left: 4px solid #d9230f;
    }
    .badge {
      margin: 0 5px;
    }
  </style>
</head>
<body>

<h1>🍽️ Zomato Gen AI: Restaurant Data Scraper & RAG Chatbot</h1>

<p>
  <img class="badge" src="https://img.shields.io/badge/Built%20With-Python-blue?logo=python" />
  <img class="badge" src="https://img.shields.io/badge/UI-Streamlit-red?logo=streamlit" />
  <img class="badge" src="https://img.shields.io/badge/Scraping-BeautifulSoup-green?logo=beautifulsoup" />
  <img class="badge" src="https://img.shields.io/badge/NLP-Hugging%20Face-yellow?logo=huggingface" />
  <img class="badge" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
</p>

<h2>🌟 Overview</h2>
<p>
This project combines web scraping and RAG-based chatbot to answer natural language questions about restaurants using real-time data.
</p>

<blockquote>
  <p>"Which restaurant has the best vegetarian options?"<br/>
  "Compare spice levels in restaurant A and B."<br/>
  "What's the dessert price range at XYZ?"</p>
</blockquote>

<h2>📌 Features</h2>
<ul>
  <li>🔎 Web Scraper: Extracts menus, features, prices, and more</li>
  <li>📚 Knowledge Base: Preprocessed and indexed for efficient retrieval</li>
  <li>🤖 RAG Chatbot: Smart, contextual, generative answers</li>
  <li>💬 Query Handling: Menu, pricing, features, restrictions</li>
  <li>🖥️ UI: Streamlit-based user interface</li>
</ul>

<h2>🏗️ System Architecture</h2>
<pre>
[Web Scraper] → [Preprocessing & Knowledge Base] → [Retriever] → [Generator (HF)] → [Response]
                                               ↑                                         ↓
                                          [Indexing]                              [User Interface]
</pre>

<h2>🚀 Getting Started</h2>
<h3>🔧 Prerequisites</h3>
<ul>
  <li>Python 3.8+</li>
  <li>Pip or Conda</li>
</ul>

<h3>🛠️ Installation</h3>
<pre>
git clone https://github.com/yourusername/zomato-genai-assignment.git
cd zomato-genai-assignment
pip install -r requirements.txt
</pre>

<h3>▶️ Run the App</h3>
<pre>
streamlit run ui/app.py
</pre>

<h2>🧠 Query Examples</h2>
<ul>
  <li>✅ "Show me vegetarian options at XYZ restaurant"</li>
  <li>✅ "Does ABC have gluten-free dishes?"</li>
  <li>✅ "Compare spice levels between A and B"</li>
  <li>✅ "What's the price range of desserts at XYZ?"</li>
</ul>

<h2>📈 Datasets</h2>
<ul>
  <li>🥗 Menus scraped from restaurant websites</li>
  <li>📋 Metadata like location, timing, contact</li>
  <li>💬 Menu descriptions with prices, allergens, spice levels</li>
</ul>

<p><strong>Note:</strong> Scraping done ethically with robots.txt compliance.</p>

<h2>🛠️ Technologies Used</h2>
<ul>
  <li>🐍 Python</li>
  <li>🍲 BeautifulSoup</li>
  <li>🤗 Hugging Face Transformers</li>
  <li>🔍 TF-IDF / FAISS</li>
  <li>🎛️ Streamlit</li>
  <li>🗃️ Pandas, NumPy</li>
</ul>

<h2>📄 Documentation</h2>
<ul>
  <li>✅ Architecture Overview</li>
  <li>✅ Scraping Assumptions & Limitations</li>
  <li>✅ KB Design & Query Types</li>
  <li>✅ Edge Case Handling</li>
  <li>✅ Future Scope</li>
</ul>

<p>Full docs at <code>docs/technical_doc.md</code> 📄</p>

<h2>📹 Demo Video</h2>
<p>🎥 <a href="https://your-demo-video-link.com" target="_blank">Watch the Demo</a></p>

<h2>🔮 Future Improvements</h2>
<ul>
  <li>🔁 Caching layer</li>
  <li>🌐 Zomato API integration</li>
  <li>🧾 OCR for printed menus</li>
  <li>🗣️ Multilingual query support</li>
</ul>

<h2>🤝 Contribution</h2>
<p>Feel free to fork, raise PRs, or open issues.</p>

<h2>📬 Contact</h2>
<p>
  👩‍💻 <strong>Divyansh Diwakar</strong><br/>
  📧 divyansh_d@ch.iitr.ac.in<br/>
  📍 IIT Roorkee | Chemical Engineering
</p>

<p><em>🚨 Note: This project is for educational use only and not affiliated with Zomato.</em></p>

</body>
</html>
