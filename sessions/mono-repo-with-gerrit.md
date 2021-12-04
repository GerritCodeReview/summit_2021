# How to survive with mono-repos in Gerrit

GerritForge keeps on working for improving the performance of using Gerrit with
very large mono-repos, with millions of refs, hundreds of GBs and tens of
millions of objects.

Luca presents the work done over the past two years for overcoming the
significant difficulties:
- Reducing the overhead of refs advertisement
- Speed-up clones by a 10x factor
- Reduce system load when accessing change notes
- Increasing performance of replication
- Surviving the deadly "search-for-reuse" phase during git-upload-pack

## Polls

> ### What is the size of the largest repo you have?
> - around 1GB
> - around 10GB
> - around 50GB
> - around 100GB
> - over 100GB

> ### What is the most urgent problem for your mono-repos?
> - memory or disk consumption on the server
> - bandwidth consumption during git-upload-pack
> - long refs negotiations during git-upload-pack
> - huge binaries bloating the repository
> - long replication times
> - batch reindexing tasks piling up

- [Slides](https://storage.googleapis.com/gerrit-talks/summit/2021/TracklingMonoRepos-with-Gerrit.pdf)
- [Video](https://youtu.be/eANday2TsOk)

*[Luca Milanesio, GerritForge, Gerrit Maintainer - Release Manager - Member of the ESC](../speakers.md#lmilanesio)*
