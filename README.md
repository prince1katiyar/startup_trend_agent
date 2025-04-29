<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>AI Startup Trend Analyzer - README</title>
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6; padding: 20px; color: #333; background: #fff;">

<h1 style="color: #4527A0;">📈 AI Startup Trend Analyzer</h1>
<p><strong>AI-powered market research and startup analysis platform built with Streamlit, CrewAI, and LangChain.</strong></p>

<hr>

<h2 style="color: #5E35B1;">🔍 Overview</h2>
<p>The AI Startup Trend Analyzer helps entrepreneurs, researchers, and investors discover valuable startup opportunities through comprehensive market, competitor, financial, and strategic analysis — all powered by Large Language Models (LLMs).</p>

<hr>

<h2 style="color: #5E35B1;">🚀 Features</h2>
<ul>
  <li>End-to-end <strong>market opportunity analysis</strong></li>
  <li>Multi-agent research system using <strong>CrewAI</strong></li>
  <li><strong>DuckDuckGo search</strong> + <strong>Newspaper3k article fetching</strong></li>
  <li>RAG-based <strong>interactive Q&A</strong> about the analysis</li>
  <li>Beautiful <strong>Streamlit dashboard</strong> with metrics, charts, and SWOT</li>
  <li>Market size projections and competitor pie charts using <strong>Plotly</strong></li>
  <li>Download results as <strong>Markdown</strong> or <strong>JSON</strong> files</li>
</ul>

<hr>

<h2 style="color: #5E35B1;">⚙️ How It Works</h2>
<ol>
  <li>Enter a startup topic or choose an example.</li>
  <li>The app runs multi-agent research to analyze the market, competitors, business models, and financial factors.</li>
  <li>It displays a complete dashboard including charts, SWOT analysis, and key recommendations.</li>
  <li>Use the Q&A interface to ask detailed questions based on the analyzed data.</li>
</ol>

<hr>

<h2 style="color: #5E35B1;">🛠 Installation</h2>
<pre style="background: #f4f4f4; padding: 10px; border-radius: 5px;">
git clone https://github.com/yourusername/ai-startup-trend-analyzer.git
cd ai-startup-trend-analyzer
pip install -r requirements.txt
</pre>

<hr>

<h2 style="color: #5E35B1;">💻 Usage</h2>
<pre style="background: #f4f4f4; padding: 10px; border-radius: 5px;">
streamlit run app.py
</pre>
<p>✅ Make sure to provide your OpenAI API key in the sidebar for analysis and Q&A features.</p>

<hr>

<h2 style="color: #5E35B1;">📂 Folder Structure</h2>
<ul>
  <li><strong>app.py</strong> – Main Streamlit application</li>
  <li><strong>startup_trend_agent/</strong>
    <ul>
      <li><strong>agents.py</strong> – CrewAI agent definitions and RAG setup</li>
      <li><strong>ui.py</strong> – Streamlit UI components, dashboards, charts</li>
    </ul>
  </li>
  <li><strong>requirements.txt</strong> – Required Python libraries</li>
</ul>

<hr>

<h2 style="color: #5E35B1;">🧰 Technologies Used</h2>
<ul>
  <li><strong>Streamlit</strong> - Frontend interface</li>
  <li><strong>CrewAI</strong> - Multi-agent workflow orchestration</li>
  <li><strong>LangChain</strong> - Conversational RAG pipelines</li>
  <li><strong>FAISS</strong> - Vector storage for embeddings</li>
  <li><strong>DuckDuckGo Search</strong> - Web search results</li>
  <li><strong>Newspaper3k</strong> - Article extraction</li>
  <li><strong>Plotly</strong> - Interactive visualizations</li>
</ul>

<hr>

<h2 style="color: #5E35B1;">✨ Future Enhancements</h2>
<ul>
  <li>Multi-topic portfolio analysis</li>
  <li>PDF report generation</li>
  <li>Save and reload full project workspaces</li>
  <li>Customizable agent goals and workflows</li>
</ul>

<hr>

<h2 style="color: #5E35B1;">📄 License</h2>
<p><strong>MIT License</strong> – Feel free to use, modify, and share!</p>

<hr>

<h2 style="color: #5E35B1;">🙌 Acknowledgements</h2>
<ul>
  <li>OpenAI for API access</li>
  <li>LangChain and CrewAI open-source communities</li>
  <li>Streamlit team for the powerful app framework</li>
</ul>

<hr>

<p align="center" style="color: #4527A0;"><strong>🚀 Ready to discover the next big startup idea?</strong></p>

</body>
</html>
