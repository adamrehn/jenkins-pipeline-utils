# Jenkins Pipeline Utils

This repository contains small snippets of code for use in [Jenkins Declarative Pipelines](https://jenkins.io/doc/book/pipeline/).

To dynamically load this library in a Pipeline without the need to preconfigure it in Jenkins, use the following code:

```groovy
library identifier: 'jenkins-pipeline-utils@master', retriever: modernSCM([$class: 'GitSCMSource', remote: 'https://github.com/adamrehn/jenkins-pipeline-utils.git'])
```
