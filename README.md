maven-repository
================

Maven repository for Platypus Java and Android libraries.

How to use this repository
--------------------------

Add this in your `pom.xml` file:

    <repositories>
        <repository>
            <id>psigen-snapshots</id>
            <url>https://raw.github.com/PlatypusLLC/maven-repository/master/snapshots</url>
        </repository>
        <repository>
            <id>psigen-releases</id>
            <url>https://raw.github.com/PlatypusLLC/maven-repository/master/releases</url>
        </repository>
    </repositories>


References
----------

* http://cemerick.com/2010/08/24/hosting-maven-repos-on-github/
  * http://stackoverflow.com/questions/14013644/hosting-a-maven-repository-on-github/14013645#14013645
