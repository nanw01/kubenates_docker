To restart jenkins after an upgrade:
  brew services restart jenkins
Or, if you don't want/need a background service you can just run:
  /usr/local/opt/openjdk@11/bin/java -Dmail.smtp.starttls.enable=true -jar /usr/local/opt/jenkins/libexec/jenkins.war --httpListenAddress=127.0.0.1 --httpPort=8080

Sample commands:

```bash
Install the latest Weekly version: brew install jenkins
Install a specific Weekly version: brew install jenkins@YOUR_VERSION
Start the Jenkins service: brew services start jenkins
Restart the Jenkins service: brew services restart jenkins
Update the Jenkins version: brew upgrade jenkins
```
jenkins
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

jenkins-01
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

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
jenkins-02
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
jenkins-03
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

api token
11bd8c66f99b85704cb5c2a70d5443c5ff