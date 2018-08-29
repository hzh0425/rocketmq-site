---
title: "Release Notes - Apache RocketMQ - Version 4.3.1"
categories:
  - Release_Notes
tags:
  - Release_Notes
  - RocketMQ
  - Version
---

Below is a summary of the issues addressed in the 4.3.1 release of RocketMQ. For full documentation of the release, a guide to get started, please refer to <a href='/docs/quick-start/'>Quick Start</a>.


[^_^]: <h2> Download the 4.3.1 release</h2>
    
[^_^]: * Source: [rocketmq-all-4.3.1-source-release.zip](https://www.apache.org/dyn/closer.cgi?path=rocketmq/4.3.1/rocketmq-all-4.3.1-source-release.zip) [[PGP](https://www.apache.org/dist/rocketmq/4.3.1/rocketmq-all-4.3.1-source-release.zip.asc)] [[MD5](https://www.apache.org/dist/rocketmq/4.3.1/rocketmq-all-4.3.1-source-release.zip.md5)] [[SHA1](https://www.apache.org/dist/rocketmq/4.3.1/rocketmq-all-4.3.1-source-release.zip.sha1)]
[^_^]: * Binary: [rocketmq-all-4.3.1-bin-release.zip](https://www.apache.org/dyn/closer.cgi?path=rocketmq/4.3.1/rocketmq-all-4.3.1-bin-release.zip) [[PGP](https://www.apache.org/dist/rocketmq/4.3.1/rocketmq-all-4.3.1-bin-release.zip.asc)] [[MD5](https://www.apache.org/dist/rocketmq/4.3.1/rocketmq-all-4.3.1-bin-release.zip.md5)] [[SHA1](https://www.apache.org/dist/rocketmq/4.3.1/rocketmq-all-4.3.1-bin-release.zip.sha1)]


## Improvement
<ul>
<li>[<a href='https://github.com/apache/rocketmq/issues/395'>ISSUE-395</a>] -  Enhance the compatibility of transactional producer API, and change the default topic to "TBW102", ensuring that the server can be backward compatible with older clients.
</li>
<li>[<a href='https://github.com/apache/rocketmq/issues/396'>ISSUE-396</a>] -  Enhance transactional message implementation, add admin tools and seprate thread pool for EndTransactionProcessor.
</li>
<li>[<a href='https://github.com/apache/rocketmq/issues/430'>ISSUE-430</a>] -  Remove scripts related to mqfilter server.
</li>
</ul>

## Bug

<ul>
<li>[<a href='https://github.com/apache/rocketmq/issues/392'>ISSUE-392</a>] -  Fix the Nullpointer exception occcured during the process of producer shutdown.
</li>
<li>[<a href='https://github.com/apache/rocketmq/issues/408'>ISSUE-408</a>] -  Restored code lost during merge process.
</li>
</ul>
                                        
            

