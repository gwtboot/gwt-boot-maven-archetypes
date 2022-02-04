# GWT Boot Maven Archetypes
Maven Archetypes for GWT Boot projects. You can generate all the GWT Boot projects with this Maven Archetypes.

To run the archetypes:

```
mvn archetype:generate 
  -DarchetypeGroupId=com.github.gwtboot 
  -DarchetypeArtifactId="gwt-boot-artifactId" 
  -DarchetypeVersion=[Version Number] 
  -DgroupId="my-groupid" 
  -DartifactId="my-artifactId"
```

Example:
```
mvn archetype:generate -DarchetypeGroupId=com.github.gwtboot -DarchetypeArtifactId=gwt-boot-basic-archetype 
```

where:
 * **"my-groupid"** == my newly created GWT Boot app Maven group
 * **"my-artifactId"** == my newly created GWT Boot app Maven artifact
 * **"gwt-boot-artifactId"** == possible archetype, see below

 # Possible Archetype for GWT Boot
 * gwt-boot-basic-archetype

 

 
