# spring-annotationbased-bean-configuration
In spring framework it is possible to configure the dependency using annotations.
So instead of using XML to describe a bean wiring, we
can move the bean configuration into the component class itself by using annotations on the relevant class, method, or field declaration.
we need to add the following property into the bean.xml file in case annotation base configuration;
    
    <context:annotation-config/>

 However in this project repo we will work several annotation and how they work.
 Spring provide the following annotion to configure the dependency:
 @AutoWired, @Required @ Qualifire @Resource, @PostConstruct and @PreDestroy
