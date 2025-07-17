<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Jenkins + GitHub CI/CD Guide</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: #f0f4f8;
      color: #333;
    }
    .container {
      max-width: 900px;
      margin: auto;
      padding: 40px 20px;
    }
    h1 {
      text-align: center;
      background: linear-gradient(45deg, #007bff, #00d1ff);
      color: white;
      padding: 20px;
      border-radius: 10px;
      animation: slideUp 2s ease-in-out;
    }
    h2 {
      color: #007bff;
      border-bottom: 2px solid #00d1ff;
      padding-bottom: 5px;
      margin-top: 30px;
    }
    p, li, code {
      font-size: 16px;
      line-height: 1.6;
    }
    code {
      background: #eee;
      padding: 2px 6px;
      border-radius: 4px;
      font-family: Consolas, monospace;
    }
    ul {
      margin-top: 10px;
    }
    pre {
      background: #222;
      color: #fff;
      padding: 10px;
      border-radius: 5px;
      overflow-x: auto;
    }
    .box {
      background: linear-gradient(45deg, #00c6ff, #0072ff);
      padding: 15px;
      color: white;
      border-radius: 8px;
      font-size: 1.2rem;
      margin-top: 10px;
      animation: float 2s ease-in-out infinite alternate;
    }
    @keyframes float {
      from { transform: translateY(0); }
      to { transform: translateY(-10px); }
    }
    @keyframes slideUp {
      from { transform: translateY(30px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>🚀 Jenkins + GitHub CI/CD Setup (Freestyle)</h1>

    <h2>🔧 Prerequisites</h2>
    <ul>
      <li>Jenkins installed (localhost:8080)</li>
      <li>Git + GitHub account</li>
      <li>ngrok (to expose localhost)</li>
    </ul>

    <h2>📁 Step 1: GitHub Project Setup</h2>
    <p>Create a new repository (e.g. <code>ci-cd-demo</code>) and add these files:</p>
    <pre><code>ci-cd-demo/
├── index.html
└── style.css</code></pre>

    <h3>index.html</h3>
    <pre><code>&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
  &lt;meta charset="UTF-8"&gt;
  &lt;title&gt;CI/CD Demo&lt;/title&gt;
  &lt;link rel="stylesheet" href="style.css"&gt;
&lt;/head&gt;
&lt;body&gt;
  &lt;div class="box"&gt;🚀 Deployed via Jenkins CI/CD!&lt;/div&gt;
&lt;/body&gt;
&lt;/html&gt;</code></pre>

    <h3>style.css</h3>
    <pre><code>body {
  background: #f2f2f2;
  font-family: Arial, sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
.box {
  background: linear-gradient(45deg, #007bff, #00d1ff);
  padding: 20px 40px;
  color: white;
  border-radius: 10px;
  font-size: 1.5rem;
  animation: slide 2s ease-in-out infinite alternate;
}
@keyframes slide {
  from { transform: translateY(0); }
  to   { transform: translateY(-10px); }
}</code></pre>

    <h2>🛠 Step 2: Jenkins Freestyle Job</h2>
    <ul>
      <li>Click <strong>New Item</strong> → Name: <code>CI-CD-Demo</code></li>
      <li>Select <strong>Freestyle project</strong> → OK</li>
    </ul>

    <h2>🔗 Step 3: Link GitHub Repo</h2>
    <ul>
      <li>Go to <strong>Source Code Management</strong></li>
      <li>Select Git → Paste repo URL</li>
      <li>Add credentials if private repo</li>
    </ul>

    <h2>⚙️ Step 4: Add Shell Build Step</h2>
    <pre><code>echo "Deploying files..."
mkdir -p /var/www/html/ci-cd-demo
cp -r * /var/www/html/ci-cd-demo/
echo "Deployed!"</code></pre>

    <h2>🌐 Step 5: Setup GitHub Webhook</h2>
    <ul>
      <li>GitHub → Repo → Settings → Webhooks → Add Webhook</li>
      <li>Payload URL: <code>http://&lt;your-ngrok-url&gt;/github-webhook/</code></li>
      <li>Content Type: <code>application/json</code></li>
      <li>Event: Just the push event</li>
    </ul>

    <h2>🚀 Step 6: Jenkins Webhook Trigger</h2>
    <ul>
      <li>In Jenkins job → <strong>Build Triggers</strong></li>
      <li>Enable: <code>GitHub hook trigger for GITScm polling</code></li>
    </ul>

    <h2>✅ Step 7: Push & Test</h2>
    <p>Make a change in code → Push to GitHub → Jenkins triggers build automatically!</p>

    <div class="box">🎉 CI/CD Ready with Jenkins + GitHub!</div>
  </div>
</body>
</html>
