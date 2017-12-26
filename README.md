# HadoopSample

Code right from Cloudera ![website](https://www.cloudera.com/documentation/other/tutorial/CDH5/topics/ht_wordcount1.html)
IDE: Eclipse

Solved Error:
1. ![log4j:WARN No appenders could be found for logger](https://www.maolintu.com/2017/12/25/hadoop-error-log4jwarn-no-appenders-could-be-found-for-logger/)
2. ![java.lang.ClassNotFoundException:org.codehaus.jackson.map.JsonMappingException](https://www.maolintu.com/2017/12/25/hadoop-error-java-lang-classnotfoundexceptionorg-codehaus-jackson-map-jsonmappingexception/)

1. WordCount

Basic function about WordCount

run configuration:
- Program arguments:
```

/path/to/input 
/path/to/output
```
- VM arguments:
```
-Dlog4j.configuration=file:///path/to/workspace/Wordcount/src/main/resources/log4j.properties
```

2. WordCount2

Add CaseSensitive function

run configuration:
- Program arguments:
```

/path/to/input 
/path/to/output
```
- VM arguments:
```
-Dlog4j.configuration=file:///path/to/workspace/Wordcount/src/main/resources/log4j.properties
```

3. WordCount3


Add skipping unimportant words function

run configuration:
- Program arguments:
```
/path/to/input 
/path/to/output
-skip /path/to/stop_words.text
```
- VM arguments:
```
-Dlog4j.configuration=file:///path/to/workspace/Wordcount/src/main/resources/log4j.properties
```
