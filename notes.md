## Chapter 1
- Spring as main replacement of JEE servers
- Spring philosophy => minimal impact
- Spring DI => javabeans and interface
- flexibility of defining dependency configuration
    -  XML files, Java configuration classes, annotations within your code, or the new Groovy bean definition method
-  any Spring-managed resource is referred to as a bean
- Using Spring for DI relies on nothing more than following the JavaBeans naming conventions within your classes
- AOP Sprng:provides the ability to implement crosscutting logic —that is, logic that applies to many parts of your application—in a single place and to have that logic applied across your application automatically
- AOP applications: logging, transaction management
-  Spring Expression Language: manipulate Java objects at runtime:  evaluating expressions and for accessing Java objects and Spring beans at runtime.
- http://projects.spring.io/spring-data: Spring Data. How spring supports non relational database
- Spring Data Access: you may be running an application with Oracle, using Hibernate for much of your data access logic. if you want to take advantage of some Oracle-specific features, implement that by using Spring’s JDBC APIs
- you will often need to transform a JavaBean into XML format
- Spring provides common interfaces for marshalling (transforming JavaBeans into XML) and unmarshalling (transforming XML into Java objects) 
- spring Test tools
- spring eclipse

## Chapter 2
- A bean is what an instance of a class is called in Spring
- To inform Spring about the DI requirement, we use the p namespace attribute
- type-safe getBean() method
- Starting with Spring 3.0, XML configuration files are no longer necessary when developing a Spring application. They can be replaced with annotations and configuration classes.