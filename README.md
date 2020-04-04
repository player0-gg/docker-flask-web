# Example docker-flask-web

<h2>Docker</h2>

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

<h3>Links</h3>
<p>Macos example: https://www.fullstackpython.com/blog/develop-flask-web-apps-docker-containers-macos.html</p>
<p>Docker latest tag: https://vsupalov.com/docker-latest-tag/</p>


<h2>Kubernetes</h2>

<p>Deployment using config file deployment.yaml</p>
<pre><code>kubectl apply -f deployment.yaml</code></pre>

<p>Cleaning up the deployment, the replica set, and the pods that are running the flask-web application</p>
<pre><code>kubectl delete deployment flask-web</code></pre>

<p>Expose a service using config file services.yaml</p>
<pre><code>kubectl apply -f services.yaml</code></pre>

<h3>Useful commands</h3>
<p>Check deployments:</p>
<pre><code>kubectl get deployments</code></pre>

<p>Check nodes:</p>
<pre><code>kubectl get nodes</code></pre>

<p>Check pods:</p>
<pre><code>kubectl get pods</code></pre>

<p>Get details about a pod (e.g. flask-web-58dbcd4c6-dl8s8)</p>
<pre><code>kubectl describe pod flask-web-58dbcd4c6-dl8s8</code></pre>

<h3>Links</h3>
<p>Kubernetes with Docker on Mac: https://rominirani.com/tutorial-getting-started-with-kubernetes-with-docker-on-mac-7f58467203fd</p>
<p>Creating a service for an application running: https://kubernetes.io/docs/tutorials/stateless-application/expose-external-ip-address/</p>
<p>Connecting applications with services: https://kubernetes.io/docs/concepts/services-networking/connect-applications-service/</p>

<p>Kubernetes cheatsheet: https://kubernetes.io/docs/reference/kubectl/cheatsheet/</p>