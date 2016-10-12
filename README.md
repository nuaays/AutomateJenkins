## Automate Jenkins Operations

```
Python scripts for automating jenkins operation: create/copy/delete/build jobs|folders, create/delete slave ...
```

## Reference
* http://pythonhosted.org/jenkinsapi/using_jenkinsapi.html
* http://pythonhosted.org/jenkinsapi/build.html
* https://github.com/pycontribs/jenkinsapi/blob/master/examples/how_to/query_a_build.py


## Jenkins Plugin download
* http://updates.jenkins-ci.org/download/plugins/
* CloudBees Folders Plugin 5.3 - com.cloudbees.hudson.plugins.folder.Folder
* AnsiColor - https://wiki.jenkins-ci.org/display/JENKINS/AnsiColor+Plugin

## Slave Node Operation
* Config - http://XX.XX.XX.XX/computer/node1/config.xml 
* Delete - curl -X POST http://XX.XX.XX/computer/node1/doDelete\?json={}\&Submit=Yes
* 

## Slave Node Connected to Jenkins Master using JNLP (Java Web Start) in Docker Container
* https://github.com/carlossg/jenkins-slave-docker
* https://hub.docker.com/r/csanchez/jenkins-slave/
* https://hub.docker.com/r/jenkinsci/jnlp-slave/
```
wget http://XX.XX.XX.XX/jnlpJars/slave.jar
java -jar slave.jar -jnlpUrl -noReconnect  http://XX.XX.XX.XX/computer/node1/slave-agent.jnlp
```
  

## Dockerfile for Jenkins Setup
* https://github.com/larrycai/docker-images/blob/master/jenkins-demo1/Dockerfile
* https://github.com/blacklabelops/jenkins/blob/master/Dockerfile
* https://github.com/jenkinsci/docker
* http://www.open-open.com/lib/view/open1436922756240.html
* http://www.open-open.com/lib/view/open1415669219461.html
