This is a dead simple Maven project which uses Hadoop. It follows [this guide](http://hadoopi.wordpress.com/2013/05/25/setup-maven-project-for-hadoop-in-5mn/).

### Quick Start

Assuming you have [hadoop](http://www.apache.org/dyn/closer.cgi/hadoop/common/) and mvn available on your machine:

    $ git clone ...
    $ cd maven-hadoop-quickstart
    $ mvn package
    $ hadoop jar target/MapReduce-1.0-SNAPSHOT.jar org.danvk.hadoop.WordCount /usr/share/dict/words /tmp/wordcount
    $ head /tmp/wordcount/part-r-00000
    A	1
    Aani	1
    Aaron	1
    Aaronic	1
    Aaronical	1
    Aaronite	1
    Aaronitic	1
    Aaru	1
    Ab	1
    Ababdeh	1
