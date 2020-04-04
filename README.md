# Example docker-flask-web

<h2>commands</h2>

<p>docker build:</p>
<pre><code>docker build --tag flask-web:1.0 .</code></pre>

<p>run docker container:</p>
<pre><code>docker run --name flask-web-app -p 5000:5000 flask-web:1.0</code></pre>
<p>Local server: http://0.0.0.0:5000/</p>

<p>delete container:</p>
<pre><code>docker rm --force flask-web-app</code></pre>

<p>Login to docker</p>
<pre><code>docker login</code></pre>
<pre><code>docker login -u "username" -p "password" docker.io</code></pre>

<p>Tag a docker image</p>
<pre><code>docker tag flask-web:1.0 player0gg/flask-web:1.0</code></pre>
<p>Push a docker image to docker hub</p>
<pre><code>docker push player0gg/flask-web:1.0</code></pre>

<h2>Links</h2>
<p>Link to example: https://www.fullstackpython.com/blog/develop-flask-web-apps-docker-containers-macos.html</p>
<p>Info about latest: https://vsupalov.com/docker-latest-tag/</p>
