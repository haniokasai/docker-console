<h1>Web Terminal For Docker</h1>


<p>1, git clone https://github.com/lanbiter/Docker-console.git</p>
<p>2, pip install -r requirements.txt</p>
<p>3, edit /etc/default/docker add DOCKER_OPTIONS="-H unix:///var/run/docker.sock -H 0.0.0.0:2375" or /etc/sysconfig/docker-network,add  DOCKER_NETWORK_OPTIONS="-H unix:///var/run/docker.sock -H 0.0.0.0:2375" or /lib/systemd/system/docker.service ,and then restart docker service</p>
<p>4, vim configure.py</p>
<p>5,set Timeout and set CONTAINER_ID</p>
<p>6, execute start.sh and visit http://(website):5000/</p>
<hr>
<img src='static/show.png'>
