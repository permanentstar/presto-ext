# presto-ext
presto extension align with presto version

# usage
put daasyyds-hive-connector-patch-${presto-version}-${release-version}.jar into $PRESTO_HOME/plugin/hive-hadoop2  
put daasyyds-hudi-connector-patch-${presto-version}-${release-version}.jar into $PRESTO_HOME/plugin/hudi

# release note
## tag 0.276.1-202209.1
- resolve hudi connector bug fix on presto 0.276.1
- resolve hive connector compatibility with hudi table on presto 0.276.1
- deployed tag to mvn central 
