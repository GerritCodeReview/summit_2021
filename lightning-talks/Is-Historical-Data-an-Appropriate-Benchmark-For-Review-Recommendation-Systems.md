#Is Historical Data An Appropriate Benchmark For Review Recommendation Systems?

Reviewer recommendation systems are used to suggest community members to review change requests. It is customary to evaluate recommendations using held out historical data. While history-based evaluation makes pragmatic use of available data, historical records may be:
(1) overly optimistic, since past assignees may have been suboptimal choices for the task at hand; or (2) overly pessimistic, since ‘incorrect' recommendations may have been equal (or even better) choices.

In this talk, I will present research performed to evaluate the extent to which historical data is an appropriate benchmark for reviewer recommendation systems. Using code review data pulled from the Gerrit project and featuring both questionnaires and semi-structured interviews with the Gerrit community, we assess how often historical data is found to be a sub-optimal benchmark for testing review recommendation systems.

We find that history-based evaluation is far more pessimistic than optimistic in the context of Gerrit review recommendations. We find that in a majority of cases (74%), changes labeled as ‘incorrect’ by historical data were actually apt suggestions for reviewers.


*[Ian Gauthier, Flywheel.io](../speakers.md#igauthier)*
