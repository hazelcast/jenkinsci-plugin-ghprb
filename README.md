# GitHub Pull Request Builder Plugin

This repository+branch contains Hazelcast tweaks (patches) for the original repo:

https://github.com/jenkinsci/ghprb-plugin

See also https://plugins.jenkins.io/ghprb/

## Installing

Find the latest version in https://repo1.maven.org/maven2/com/hazelcast/jenkins/plugins/ghprb/

Go to the Advanced settings tab in the Plugin Manager Jenkins configuration and
fill the `hpi` URL to deploy.

E.g. go to https://jenkins.hazelcast.com/manage/pluginManager/advanced
and in the `Deploy Plugin` section fill:

```
https://repo1.maven.org/maven2/com/hazelcast/jenkins/plugins/ghprb/5.0.0/ghprb-5.0.0.hpi
``` 
