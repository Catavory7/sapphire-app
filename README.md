<p align="center">
  <img src="https://raw.githubusercontent.com/Catavory7/sapphire-app/refs/heads/main/uv.png" alt="Sapphire Logo" height="200">
</p>

<h1 align="center">Sapphire</h1>

<p align="center">
  <strong>Sapphire</strong> is a deployable all-in-one proxy bundle, based on <a href="https://github.com/titaniumnetwork-dev/Ultraviolet">Ultraviolet</a>. It enables anyone to bypass internet censorship or browse within a controlled sandbox using advanced service worker-based technology.
</p>

<hr>

<h2>Public Deployment</h2>
<ol>
  <li>Sign up for a free account at <a href="https://www.koyeb.com/">Koyeb</a>.</li>
  <li>Fork this repository.</li>
  <li>On Koyeb, create a new service and connect it to your GitHub account.</li>
  <li>Select your forked repository and deploy the service.</li>
</ol>

<h2>Local Deployment</h2>
<ol>
  <li>Clone the repository:<br>
    <code>git clone https://github.com/Project-Lapis/sapphire-app.git</code><br>
    <code>cd sapphire-app</code>
  </li>
  <li>Install dependencies:<br>
    <code>npm install</code>
  </li>
  <li>Build the application:<br>
    <code>npm run build</code>
  </li>
  <li>Start the server:<br>
    <code>npm start</code>
  </li>
</ol>

<blockquote>
  <strong>Important:</strong> Until deployed on a domain with a valid SSL certificate, Firefox will block the site. Use a Chromium-based browser for local testing.
</blockquote>

<h2>HTTP Transport Options</h2>
<p>
  Sapphire uses various transport layers to fetch encrypted or unencrypted proxied data. The links below are supported transport options:
</p>

<ul>
  <li><a href="https://github.com/MercuryWorkshop/EpoxyTransport">EpoxyTransport</a> – Encrypted transport (default in example)</li>
  <li><a href="https://github.com/MercuryWorkshop/CurlTransport">CurlTransport</a> – Alternative encrypted transport using curl</li>
  <li><a href="https://github.com/MercuryWorkshop/Bare-as-module3">Bare-Client</a> – Legacy unencrypted transport</li>
</ul>

<p>
  For advanced configurations and routing, see the <a href="https://github.com/MercuryWorkshop/bare-mux">bare-mux documentation</a>.
</p>
