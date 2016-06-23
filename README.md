# Lonline
Lonline allows to log your program into the cloud and is powered by Dynamicloud service.  Lonline allows you to log your program's execution into the cloud to avoid server access and disk space usage

Lonline provides 6 levels of logging and 2 methods to execute reports.  Lonline is a library to log your program through a storing service called Dynamicloud.  With Dynamicloud we can store data dynamically and very easy, Lonline allows you to set more features and this way log more than only text, level and program trace.

1. [Dynamicloud](#dynamicloud) 
2. [Levels](#levels)
3. [Ruby language](#ruby-language)
4. [Java language](#java-language)
5. [NodeJs](#nodejs)

#Dynamicloud
Dynamicloud is a service to store data into the cloud, it allows you to create structures dynamically without intervention from IT teams.  This service allows lonline to store log information very easy and fast.  Additionally, lonline gets the power of Dynamicloud to execute queries and provide reports for your analysis about created logs in a specific time, date, year, etc.

#Levels
Lonline provides 6 levels of logging, check out the below table to understand how these levels are activated according the level of logging in your program:

| Level | Activated levels | Description (From the great Log4j library) |
| --- | --- | --- |
| `fatal` | Fatal | Designates very severe error events that will presumably lead the application to abort.|
| `error` | Fatal, Error | Designates error events that might still allow the application to continue running.|
| `warn` | Fatal, Error, Warn | Designates potentially harmful situations.|
| `info` | Fatal, Error, Warn, Info | Designates informational messages that highlight the progress of the application at coarse-grained level.|
| `debug` | Fatal, Error, Info, Warn, Debug | Designates fine-grained informational events that are most useful to debug an application.|
| `trace` | All levels | Traces the code execution between methods, lines, etc.|
| `off` | None | The highest possible rank and is intended to turn off logging.|

#Ruby Language
0.0.2

If you're a Ruby developer visit our lonline Ruby version [Lonline Ruby version documentation](https://github.com/dynamicloud/lonline_for_ruby "Lonline Ruby version documentation") 

#Java Language
0.0.1

If you're a Java developer visit our lonline Java version [Lonline Java version documentation](https://github.com/dynamicloud/lonline_for_java "Lonline Java version documentation") 

#NodeJs
0.0.2

If you're a NodeJs developer visit our lonline NodeJs version [Lonline NodeJs version documentation](https://github.com/dynamicloud/lonline_for_nodejs "Lonline NodeJs version documentation") 



**There are all the guidelines to use lonline for Java, Ruby and NodeJs.**

For further information and support about lonline, contact us at [Contact](https://www.dynamicloud.org/contact "Dynamicloud contact")
