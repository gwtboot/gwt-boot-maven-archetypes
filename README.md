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
  -DprojectName="my-project-name"
  -DprojectDescription="my-project-description"
```

Example:
```
mvn archetype:generate -DarchetypeGroupId=com.github.gwtboot -DarchetypeArtifactId=gwt-boot-basic-archetype 
```

where:
 * **"my-groupid"** == my newly created KissMDA app Maven group
 * **"my-artifactId"** == my newly creadted KissMDA app Maven artifact
 * **"my-project-name"** == the name of my project
 * **"my-project-description"** == the description of my project

 # Possible Archetype for GWT Boot
 * gwt-boot-basic-archetype

 

 
