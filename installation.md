# Installation

This installation covers a range of objects in the OpenSherlock ecosystem. The installation begins by a description of installation on a single computer; in fact, development has been conducted entirely on a MacBook Pro with an i7 and 16gb ram. A section will then cover issues related to installing in a distributed manner.

## Requirements

### Hardware

Recommended: a strong CPU, i3 or better, 8gb ram \(caveat: on a single system installation, memory less than 16gb will reduce the processing power of the system\).

### Software Support

Java 1.8 or higher

Apache Maven

PostgreSQL 9.6 or higher

ElasticSearch 6+

Kafka 1.1.0 \(the current release at this time\)

## OpenSherlock

All OpenSherlock software in this section is Java, with Maven builds. Since we are not yet registered with a Maven repo, the process is to download each repository listed below, and build each. The command line we use in each repository root where pom.xml is located is this:

```text
mvn clean install -DskipTests -Dgpg.skip
```

Building essentially proceeds from the bottom of the following figure.

![Software Dependencies](.gitbook/assets/dependencies.jpg)

  
Items listed below carry the following codes:

* Plain text repo name means the code does not yet exist
* **Bold** means the repo is online and ready to build
* _Italic_ means the repo is online but it will be a while before code exists
* _**Bold and Italic**_ means the repo is online and the code will be uploaded soon

These are the repositories in play now

* **tq-support** [https://github.com/topicquests/tq-support](https://github.com/topicquests/tq-support) 
* **tqks-common** [https://github.com/topicquests/tqks-common  ](https://github.com/topicquests/tqks-common  )
* **tqks-kafka-support** [https://github.com/topicquests/tqks-kafka-support  ](https://github.com/topicquests/tqks-kafka-support  )
* **tqks-postgres-provider** [https://github.com/KnowledgeGarden/tqks-postgress-provider  ](https://github.com/KnowledgeGarden/tqks-postgress-provider  )
* **blueprints-sql-provider** [https://github.com/topicquests/blueprints-sql-provider  ](https://github.com/topicquests/blueprints-sql-provider  )
* **tqks-elastic6-provider** [https://github.com/KnowledgeGarden/tqks-elastic6-provider  ](https://github.com/KnowledgeGarden/tqks-elastic6-provider  )
* **tqks-statistics** [https://github.com/topicquests/tqks-statistics  ](https://github.com/topicquests/tqks-statistics  )
* _tqks-tagomizer_ [https://github.com/topicquests/tqks-tagomizer](https://github.com/topicquests/tqks-tagomizer)
* **tqks-subject-server** [https://github.com/topicquests/tqks-subject-server  ](https://github.com/topicquests/tqks-subject-server  )
* **tqos-topicmerge-agent** [https://github.com/topicquests/tqos-topicmerge-agent](https://github.com/topicquests/tqos-topicmerge-agent)
* **tqos-asr-core** [https://github.com/topicquests/tqos-asr-core  ](https://github.com/topicquests/tqos-asr-core  )
* tqos-asr-dsl
* _tqos-asr-reade_r [https://github.com/topicquests/tqos-asr-reader  ](https://github.com/topicquests/tqos-asr-reader  )
* _tqos-asr-citeomizer_ [https://github.com/topicquests/tqos-asr-citeomizer  ](https://github.com/topicquests/tqos-asr-citeomizer  )
* _**tqos-asr-documizer**_ [https://github.com/topicquests/tqos-asr-documizer  ](https://github.com/topicquests/tqos-asr-documizer  )
* _**tqos-asr-gramolizer**_ [https://github.com/topicquests/tqos-asr-gramolizer  ](https://github.com/topicquests/tqos-asr-gramolizer  )
* **tqos-general-database** [https://github.com/topicquests/tqos-general-database  ](https://github.com/topicquests/tqos-general-database  )
* _**tqos-asr-sentence-registry**_ [https://github.com/topicquests/tqos-asr-sentence-registry  ](https://github.com/topicquests/tqos-asr-sentence-registry  )
* 
## Installing the Components



