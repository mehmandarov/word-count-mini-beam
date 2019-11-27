# Minimal Word Count Example with Pipeline Representation Dump
Apache Beam project based on the [minimal word count example][1], modified to show how to get the pipeline representation.

More info about the word count example can be found in the [documentation][2].

## Running the code

### Software Requirements

* Java 8 (Java 9 or above are [not officially supported][2] by Beam yet)
* Maven 3.6.x

### Running on your local machine (direct runner)
```bash
mvn compile exec:java \
        -Dexec.mainClass=org.apache.beam.examples.MinimalWordCount \
        -Dexec.args="--inputFile=pom.xml --output=counts" \
        -Pdirect-runner
```



[1]: https://github.com/apache/beam/blob/master/examples/java/src/main/java/org/apache/beam/examples/MinimalWordCount.java
[2]: https://beam.apache.org/get-started/wordcount-example/
[3]: https://issues.apache.org/jira/browse/BEAM-2530
