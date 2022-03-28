#### Solution:
<p>Right now repository has a working http server application in docker that builds and publishes image to Docker Hub.</p>
<p>Unfortunatly, I underestimated complexity of source code and instead cutting down a few lines for https, got stuck with automated tests.</p>
<p>Best approach in this situation would be to use borrowed version of application as is with modifyed pipelines and configuration.</p>
<p>Then writing clean http-only version of app when time allows.</p>

#### Home assignment
1. Build a Web application that outputs the client IP address, in any programming/scripting
language of your choice

2. Put your web application inside a Docker Container, using a web server of your choice.
Make sure your Dockerfile is as simple and small as possible.

3. Open an account in Github/Gitlab and upload your code to a new repository using Git

4. Develop a CI flow that builds your docker image on every commit to master, and pushes
it to a image repository of your choice (You may use Docker Hub for example)

