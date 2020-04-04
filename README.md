# Example docker-flask-web

<h2>commands</h2>

<p>docker build:</p>
<pre><code>docker build --tag flask-web:1.0 .</code></pre>

<p>run docker container:</p>
<pre><code>docker run --name flask-web-app -p 5000:5000 flask-web:1.0</code></pre>
<p>Local server: http://0.0.0.0:5000/</p>

<p>delete container:</p>
<pre><code>docker rm --force flask-web-app</code></pre>


<p>Link to example: https://www.fullstackpython.com/blog/develop-flask-web-apps-docker-containers-macos.html</p>
<p>Info to latest: https://vsupalov.com/docker-latest-tag/</p>
