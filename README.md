# Example docker-flask-web

<h2>commands</h2>

<p>docker build:</p>
<pre><code>docker build --tag flask_web .</code></pre>

<p>run docker container:</p>
<pre><code>docker run --name flask_web-app -p 5000:5000 flask_web</code></pre>
<p>Local server: http://0.0.0.0:5000/</p>

<p>delete container:</p>
<pre><code>docker rm --force flask_web-app</code></pre>


<p>Link to example: https://www.fullstackpython.com/blog/develop-flask-web-apps-docker-containers-macos.html</p>
