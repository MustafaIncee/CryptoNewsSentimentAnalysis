<!DOCTYPE html>
<html>
<head>
<style>
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 20px;
    background: linear-gradient(135deg, #1e2024 0%, #17181c 100%);
    color: #fff;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
}

.header {
    text-align: center;
    padding: 40px 0;
    background: rgba(255,255,255,0.05);
    border-radius: 15px;
    margin-bottom: 30px;
}

.header h1 {
    font-size: 3em;
    margin: 0;
    background: linear-gradient(45deg, #00ff88, #00a1ff);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

.section {
    background: rgba(255,255,255,0.05);
    padding: 25px;
    border-radius: 15px;
    margin-bottom: 20px;
    border: 1px solid rgba(255,255,255,0.1);
}

.section h2 {
    color: #00ff88;
    margin-top: 0;
}

.models-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    margin: 20px 0;
}

.model-card {
    background: rgba(0,0,0,0.2);
    padding: 20px;
    border-radius: 10px;
    border: 1px solid rgba(255,255,255,0.1);
}

.feature-list {
    list-style: none;
    padding: 0;
}

.feature-list li {
    margin: 10px 0;
    padding-left: 25px;
    position: relative;
}

.feature-list li:before {
    content: "🔥";
    position: absolute;
    left: 0;
}

.pipeline {
    background: rgba(0,0,0,0.2);
    padding: 20px;
    border-radius: 10px;
}

.pipeline-step {
    display: flex;
    align-items: center;
    margin: 15px 0;
}

.step-number {
    background: #00ff88;
    color: #000;
    width: 30px;
    height: 30px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-right: 15px;
    font-weight: bold;
}

.tech-stack {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin: 20px 0;
}

.tech-badge {
    background: rgba(0,161,255,0.2);
    padding: 8px 15px;
    border-radius: 20px;
    font-size: 0.9em;
    border: 1px solid #00a1ff;
}

footer {
    text-align: center;
    margin-top: 50px;
    padding: 20px;
    color: rgba(255,255,255,0.5);
}
</style>
</head>
<body>

<div class="container">
    <div class="header">
        <h1>🚀 Crypto Sentiment Analysis Project</h1>
        <p>Advanced NLP Analysis for Cryptocurrency Market Sentiment</p>
    </div>

    <div class="section">
        <h2>🎯 Overview</h2>
        <p>A state-of-the-art sentiment analysis system utilizing multiple transformer models to analyze cryptocurrency market sentiment from news articles. Our system processes both Turkish and English content, providing comprehensive market insights.</p>
    </div>

    <div class="section">
        <h2>🤖 Implemented Models</h2>
        <div class="models-grid">
            <div class="model-card">
                <h3>BERT</h3>
                <p>Base transformer model for general sentiment analysis</p>
            </div>
            <div class="model-card">
                <h3>DistilBERT</h3>
                <p>Lightweight BERT variant for efficient processing</p>
            </div>
            <div class="model-card">
                <h3>DeBERTa</h3>
                <p>Enhanced BERT with disentangled attention</p>
            </div>
            <div class="model-card">
                <h3>FinBERT</h3>
                <p>Specialized model for financial text</p>
            </div>
            <div class="model-card">
                <h3>ALBERT</h3>
                <p>Memory-efficient BERT variant</p>
            </div>
            <div class="model-card">
                <h3>GPT-2</h3>
                <p>Generative model adapted for classification</p>
            </div>
        </div>
    </div>

    <div class="section">
        <h2>✨ Key Features</h2>
        <ul class="feature-list">
            <li>Multi-model ensemble approach</li>
            <li>Specialized financial text processing</li>
            <li>Turkish-English translation capabilities</li>
            <li>Comprehensive data cleaning</li>
            <li>Advanced sentiment scoring</li>
            <li>Large-scale news processing</li>
        </ul>
    </div>

    <div class="section">
        <h2>🔄 Data Pipeline</h2>
        <div class="pipeline">
            <div class="pipeline-step">
                <div class="step-number">1</div>
                <div>Raw crypto news collection</div>
            </div>
            <div class="pipeline-step">
                <div class="step-number">2</div>
                <div>Text cleaning and normalization</div>
            </div>
            <div class="pipeline-step">
                <div class="step-number">3</div>
                <div>Language detection and translation</div>
            </div>
            <div class="pipeline-step">
                <div class="step-number">4</div>
                <div>Multi-model sentiment analysis</div>
            </div>
            <div class="pipeline-step">
                <div class="step-number">5</div>
                <div>Ensemble prediction generation</div>
            </div>
            <div class="pipeline-step">
                <div class="step-number">6</div>
                <div>Results aggregation and scoring</div>
            </div>
        </div>
    </div>

    <div class="section">
        <h2>🛠 Technical Stack</h2>
        <div class="tech-stack">
            <span class="tech-badge">PyTorch</span>
            <span class="tech-badge">Hugging Face Transformers</span>
            <span class="tech-badge">CUDA</span>
            <span class="tech-badge">Pandas</span>
            <span class="tech-badge">Advanced NLP Tools</span>
        </div>
    </div>

    <footer>
        <p>Developed with 💚 for advanced cryptocurrency market analysis</p>
    </footer>
</div>

</body>
</html>
