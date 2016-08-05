---
layout: page
title: Work History
permalink: /work-history/
---

## Senior DBA (Oracle and Postgres)

### Blackboard

#### October 2015 — now()

Blackboard Cloud Services already have a very large number of clients, mostly running on Oracle Enterprise with in their private cloud. The majority of my work is around complex database administration issues including:
* load testing and sizing (Linux and Oracle memory parameters)
* task automation/scripting (bash / Python / Ruby)
* Oracle performance tuning and root cause analysis
I am working closely with our Support, Operations, Development, and Infrastructure teams.

Blackboard is also in the processing of migrating their hosting to the AWS cloud, with Postgres databases. This provides an exciting opportunity to expand my knowledge of both cloud computing and databases, gain hands-on experience of several key DevOps tools: AWS CLI (Command Line Interface), Jenkins (for Continuous Integrations) and Chef (Infrastructure as Code).

## Senior DBA (Oracle)

### Servicenow

#### May 2013 - October 2015 

The majority of their clients are running on MySQL, with only a small proportion of the largest clients running on Oracle DBs.

I was responsible for maintaining complex, cross-datacenter database replication topologies in the Servicenow's private cloud. One of the major challenges was the high volume of DB transactions we handled, this involved tuning both the Oracle DB and Dell Shareplex replication engine. I worked on a number of performance tuning issues directly for the core product and also for tuning the background replication processing. Typical changes I have initiated were extra indexes, additional database statistics, automation for adding supplemental logging, adjusting Oracle & Shareplex parameters: pga_aggregate_target, shareplex checkpoint frequency...

In all my previous jobs I have been working Oracle EE (with Tuning & Performance pack). At Servicenow we were running Oracle SE. I developed very useful monitoring scripts based on v$ views (v$session, v$process, v$sql, v$lock, v$tempseg_usage… ). Later on we bought Toad+Spotlight licenses from Quest/Dell, which have good advisors built in, however my monitoring scripts still proved very useful.

I also worked on typical operational issues:
* enhancing and debugging shell scripts (bash and python)
* DB patching & upgrades 
* cloning DBs via Shareplex

While I wasn't typically working directly with MySQL, I was working very closely with the MySQL DBAs and it was interesting to see:
* how monitoring and cloning worked for MySQL
* quirky performance differences between Oracle and MySQL DB engines 

Lastly there were some clients with MongoDB. I didn't get to work directly on these, but this did motivate me to completed several MongoDB University (7-week) online training courses:
* M101P: MongoDB for Developers (Python)
* M101JS: MongoDB for Developers (JavaScript)
* M102: MongoDB for DBAs
I also reviewed some real-world Mongo troubleshooting issues with the performance tuning team in Amsterdam.


## Senior DBA (Oracle)

### Blackboard

#### June 2010 – May 2013 

Senior Oracle DBA

(3 years)Amsterdam, Netherlands
Working for Blackboard’s very strong Hosting business was a great career move; we were managing over 1000 production databases and a similar number of staging and test environments in our datacenters around the world. 

Within my first year at Blackboard I was promoted to Senior DBA and a major part of my work has been cross training my fellow DBAs, writing scripts (sql, bash, perl and some python) and procedures to improve the quality of our monitoring and analysis. I have received some great feedback regarding this cross training and my ability to break down and explain the root causes of complex database problems.

Before Blackboard my main experience was running Oracle on Solaris and HP-UX. At Blackboard, I worked extensively with Oracle on Linux, include tuning low-level kernel and memory issues. I was working with both traditional and virtualised Linux environments. Some of our large clients were running with Oracle RAC, and I have been involved in some advanced RAC analysis as well. This has stretched my networking and infrastructure knowledge.

I also developed new Oracle real time monitoring and diagnostic scripts. These scripts alert on performance, application issues and capture real time low level process details.

While at Blackboard, I worked closely with the application support teams (Apache HTTP and Tomcat) and became relatively comfortable with the basics of TomCat: inspected thread dumps, checking for full GCs (garbage collections) issues and monitoring key Linux metrics (top, netstat and ps). I wrote advanced python scripts to match Java stack traces with their Linux CPU usage.