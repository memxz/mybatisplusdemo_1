# mybatisplusdemo

## structure

```xml
mybatisplusdemo.
│   .gitignore
│   HELP.md
│   mvnw
│   mvnw.cmd
│   pom.xml
│
├───.idea
│       .gitignore
│       compiler.xml
│       encodings.xml
│       jarRepositories.xml
│       misc.xml
│       sqldialects.xml
│       uiDesigner.xml
│       vcs.xml
│       workspace.xml
│
├───.mvn
│   └───wrapper
│           maven-wrapper.jar
│           maven-wrapper.properties
│
├───src
│   ├───main
│   │   ├───java
│   │   │   └───com
│   │   │       └───mybatisplus
│   │   │           └───demo
│   │   │               │   MybatisplusdemoApplication.java
│   │   │               │
│   │   │               ├───entity
│   │   │               │       User.java
│   │   │               │
│   │   │               └───mapper
│   │   │                       UserMapper.java
│   │   │
│   │   └───resources
│   │       │   application.yml
│   │       │
│   │       ├───db
│   │       │       data-h2.sql
│   │       │       schema-h2.sql
│   │       │
│   │       ├───static
│   │       └───templates
│   └───test
│       └───java
│           └───com
│               └───mybatisplus
│                   └───demo
│                           DemobilisationApplicationTests.java
│
└───target
    ├───classes
    │   │   application.yml
    │   │
    │   ├───com
    │   │   └───mybatisplus
    │   │       └───demo
    │   │           │   MybatisplusdemoApplication.class
    │   │           │
    │   │           ├───entity
    │   │           │       User.class
    │   │           │
    │   │           └───mapper
    │   │                   UserMapper.class
    │   │
    │   └───db
    │           data-h2.sql
    │           schema-h2.sql
    │
    ├───generated-sources
    │   └───annotations
    ├───generated-test-sources
    │   └───test-annotations
    ├───maven-status
    │   └───maven-compiler-plugin
    │       ├───compile
    │       │   └───default-compile
    │       │           createdFiles.lst
    │       │           inputFiles.lst
    │       │
    │       └───testCompile
    │           └───default-testCompile
    │                   createdFiles.lst
    │                   inputFiles.lst
    │
    └───test-classes
        └───com
            └───mybatisplus
                └───demo
                        DemobilisationApplicationTests.class

```