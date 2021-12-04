# One step closer to the cloud: forward Gerrit events to Jenkins via AWS Kinesis

In the effort of making Gerrit more cloud-native, we cannot neglect tools
integrating with Gerrit. Jenkins, currently, doesn't have a way to integrate
with Gerrit via cloud-native tools.

In this lightning talk, I will demo AWS Kinesis Consumer, a Jenkins plugin
allowing the consumption of Gerrit stream events from Kinesis.

## Polls

> How do you integrate Jenkins with Gerrit?
> - Gerrit Trigger plugin
> - Gerrit Code Review Plugin
> - Other

> What are the main issue you face with your setup?
> - integration is difficult to setup
> - scalability issues with big Jenkins installation
> - loosing events when Gerrit restarts
> - loosing events when Jenkins restarts
> - difficult to debug issues

- Slides (TO BE PUBLISHED)
- [Video](https://youtu.be/XLuL-EKFRbc)

*[Fabio Ponciroli, GerritForge](../speakers.md#fponciroli)*
