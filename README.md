# maven-java-app

## archetype:generate
# Full name:

org.apache.maven.plugins:maven-archetype-plugin:3.2.0:generate

# Description:

Generates a new project from an archetype, or updates the actual project if using a partial archetype. If the project is fully generated, it is generated in a directory corresponding to its artifactId. If the project is updated with a partial archetype, it is done in the current directory.

# Attributes:

Invokes the execution of the lifecycle phase generate-sources prior to executing itself.

# Parameter Details
<archetypeArtifactId>
The archetype's artifactId.
- Type: java.lang.String
- Required: No
- User Property: archetypeArtifactId

# <archetypeGroupId>
The archetype's groupId.
Type: java.lang.String
Required: No
User Property: archetypeGroupId
  
# <archetypeVersion>
The archetype's version.
Type: java.lang.String
Required: No
User Property: archetypeVersion
