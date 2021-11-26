# An introduction to the pull-replication plugin

Over the last year GerritForge took an effort to improve Gerrit replication
performance by introducing the pull-replication plugin.

This presentation will show the current state of the pull-replication plugin,
introduce the main concepts behind it and explain how they can improve
replication performance, provide more predictable behaviour and help to avoid
split-brain issues.

I will also explain how the pull-replication plugin can be setup as a standalone
solution or work together with the replication plugin. 
 
At the end of the talk I would like to show the pull-replication plugin in action.

## Pools
> What is your average replication execution time?
- < 1 second
- < 30 seconds
- < 1 minute
- < 5 minutes
- < 10 minutes
- > 10 minutes

*[Marcin Czech, GerritForge](../speakers.md#mczech)*
