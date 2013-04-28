UltimateStatus
==============

UltimateStatus - an example Application for JavaFX/Maven

## Setup MacOS

* install JDK7 (see https://jdk7.java.net/download.html )

* first, fixing classpathes for JavaFX/JDK7 in MacOS

        sudo mvn com.zenjava:javafx-maven-plugin:1.5:fix-classpath

* run with

        mvn jfx:run

* create webstart folder

        mvn jfx:build-webstart

* build a native DMG (with all dependencies added)

        mvn jfx:build-native


## References

* Using the great Maven JavaFX Plugin from zonski (see https://github.com/zonski/javafx-maven-plugin ) 
* Using standard CSS/JavaFX Example from Oracle (see http://docs.oracle.com/javafx/2/get_started/css.htm )
