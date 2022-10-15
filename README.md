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
 * gwt-boot-basic-archetype
 * gwt-boot-ui-domino-dagger2

## Examples
```
mvn archetype:generate -DarchetypeGroupId=com.github.gwtboot 
  -DarchetypeArtifactId=gwt-boot-basic-archetype 

mvn archetype:generate -DarchetypeGroupId=com.github.gwtboot 
  -DarchetypeArtifactId=gwt-boot-ui-domino-dagger2-archetype
```

 
