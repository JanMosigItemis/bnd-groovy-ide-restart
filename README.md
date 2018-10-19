See [https://github.com/bndtools/bndtools/issues/1943](https://github.com/bndtools/bndtools/issues/1943)
See [https://bugs.eclipse.org/bugs/show_bug.cgi?id=540316](https://bugs.eclipse.org/bugs/show_bug.cgi?id=540316)

## What is this?
A test project to showcase an error when running JUnit based integration tests in an OSGi container with bnd+Eclipse.

## How to use
- Have a copy of Eclipse 2018-09 (4.9.0) with bnd 4.0.0 ready.
- Open IDE with a new empty Eclipse workspace.
- Import the bnd workspace located in this repository with File -> Import -> Existing bnd workspace.
- Right click on the testproject and choose Run -> Bnd OSGi Run Launcher (JUnit).
- Wait until the test has been finished and framework has been shut down.
- Close IDE.
- Start IDE again, choose same Eclipse worksapce location.
- Eclipse will crash.

## How to compile on console:
`./gradlew clean build`

