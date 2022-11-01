# GWT Boot Maven Archetypes
Maven archetypes for GWT Boot projects. You can generate all the GWT Boot projects with this Maven archetypes. 
All the archetypes are based on [GWT Boot Starters](https://github.com/gwtboot/gwt-boot-modules)

To run the archetypes:

```
mvn archetype:generate 
  -DarchetypeGroupId=com.github.gwtboot 
  -DarchetypeArtifactId="gwt-boot-artifactId" 
  -DarchetypeVersion=[Version Number] 
  -DgroupId="my-groupid" 
  -DartifactId="my-artifactId"
```

where:
 * **"my-groupid"** == my newly created GWT Boot app Maven group
 * **"my-artifactId"** == my newly created GWT Boot app Maven artifact
 * **"gwt-boot-artifactId"** == possible archetype, see below

 ## Possible Archetype for GWT Boot
 * gwt-boot-basic-archetype: this is the [Basic example](https://github.com/gwtboot/gwt-boot-samples/tree/master/gwt-boot-sample-basic)
 * gwt-boot-ui-domino-dagger2-archetype: this is the [UI Domino and Dagger example](https://github.com/gwtboot/gwt-boot-samples/tree/master/gwt-boot-sample-ui-domino-dagger2)

## Examples
```
mvn archetype:generate -DarchetypeGroupId=com.github.gwtboot -DarchetypeArtifactId=gwt-boot-basic-archetype 

mvn archetype:generate -DarchetypeGroupId=com.github.gwtboot -DarchetypeArtifactId=gwt-boot-ui-domino-dagger2-archetype
```

Following properties must be given (please use Maven standard): 
- *groupId*: example: *com.test.order*
- *artifactId*: example: *company-order*
- *version*: *1.0-SNAPSHOT* as a standard value
- *package*: the groupId as a standard value: example: *com.test.order*