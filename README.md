# Maven-Assignment ## " Ayush Rai (1707) "
---------------------------------------------------------------------------
----------------------------------------------------------------------------


# It's a project with multiple modules. The modules "string api" and "string impl" are part of the "Assign" module. 

# For each module, we have three pom files. We generated the modules and put the assembly plugin in the Assign pom.xml file. 

# In this case, the package should be "pom." We mentioned the parent module specs with packaging as "jar" in the string api pom.xml file. 

# We mentioned the parent module specs with packaging as "jar" in the "string impl pom.xml" file. Because we wish to invoke the string api java class from within the string impl, we named the dependency string-api. 

# We've also included the plugins, such as checkstyle and spotbugs."StringFunctions.java" is in the string api module, and Application.java is in the string impl module.

# We've basically generated two methods in StringFunctions: stringReverse and stringLength.

# Then, in the Application class, we created a StringFunctions object and called it.

# Run the following command to create the Target folder: mvn clean compile assembly:

# Then run this command from the string impl/target directory. - jar string impl-1.0-SNAPSHOT-jar-with-dependencies.jar



