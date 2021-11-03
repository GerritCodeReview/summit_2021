# One step closer to the cloud: forward Gerrit events to Jenkins via AWS Kinesis

In the effort of making Gerrit more cloud-native, we cannot neglect tools
integrating with Gerrit. Jenkins is one of the main ones and currently it
doesn't have a way to integrate with Gerrit via cloud-native tools.

In this lightning talk, I will demo AWS Kinesis Consumer, a Jenkins plugin
allowing the consumption of Gerrit stream events from Kinesis.

*[Fabio Ponciroli, GerritForge](../speakers.md#fponciroli)*
