---
title: "Top Five Intellij Plugins for Java/Kotlin Devs"
date: 2021-04-28T21:31:49+02:00
Description: ""
author: "Cristian Silva"
tags: ["codequality", "programming", "java", "kotlin", "maven", "IntelliJIDEA", "tools", "plugins"]
thumbnail: "images/posts/plugins.jpg"
draft: true
---

Plugins can be very handy in many situations in our daily coding. It can extend core functionalities, provide various integrations and support to automate many tasks.  

# These are my top plugins

## ![SonarLint icon](/images/posts/sonarLintIcon-48.png "SonarLint icon")  SonarLint 
SonarLint lets you fix bugs and vulnerabilities as you write code!

It highlights coding issues on the fly, with clear remediation guidance so you can fix them before the code is even committed.  
This is a must have. It helps a lot to write better code.   

## ![Maven Helper icon](/images/posts/mavenHelperIcon-48.png "Maven Helper icon")  Maven Helper  
Are you a grateful Maven user?  I'm too!  
#### It provides  
* easy way for analyzing and excluding conflicting dependencies  
* easy way to search for direct or transitive dependencies
* actions to run/debug maven goals for a module that contains the current file or on the root module
* action to open terminal at the current maven module path  
* actions to run/debug the current test file  
If maven-surefire-plugin is configured to skip or exclude the test, 'verify' goal will be used. Different configuration styles can be found at https://github.com/harishkannarao/MavenSurefireFailsafeExamples

## CodeMetrics  
Provides inlay indicators based on a customizable complexity calculation for Java files.
It will show hints, in classes and methods, so you can easily identify what needs to be reviewed.  

It is not a standard metric, but it is a close approximation of [Cyclomatic complexity](https://en.wikipedia.org/wiki/Cyclomatic_complexity). You can also customize the complexity calculation for the project by adjusting the relevant configuration entries.

## ![String Manipulation icon](/images/posts/stringManipulationIcon-48.png "String Manipulation icon") String Manipulation  
Case switching, sorting, filtering, incrementing, aligning to columns, grepping, escaping, encoding and much more...

## ![JPA Buddy icon](/images/posts/jpaBuddyIcon-48.png "JPA Buddy icon") JPA Buddy  
JPA Buddy simplifies and accelerates everything related to JPA. It provides tools to assist your work with Hibernate, Spring Data JPA, Liquibase, Flyway and similar things.  

#### Key features
* JPA entities: creating and editing entities, entity attributes, lifecycle callbacks, indexes and constraints. Support for JPA converters and Hibernate custom types. Ability to use Lombok annotations for entities.
* Generating proper equals, hashCode and toString method implementations for JPA entities.
* Source code intentions, inspections and quick fixes for JPA entity declarations.
* Displaying entity relationship graph in the JPA Structure panel, under the Persistent Units node.
* Liquibase changelogs and Flyway versioned migrations automatic generation: comparing database to database, model to database, model to snapshot.
* Liquibase changelog visual designer and coding assistance: creating and editing elements, references to table names, column names, included files etc.
* Actions: creating Liquibase snapshot, running "liquibase update" and "liquibase updateSQL" commands.
* Spring Data Repositories: creating repositories, creating repository methods, editing method properties, creating projection based on entity class, extract JPQL query.
* Kotlin: all visual designers fully support code generation for Kotlin entities and repositories.

Well, I said it was a top 5... but I have one more...  

## ![Extra Icons](/images/posts/extraIcons-48.png "Extra Icons") Extra Icons  
It's an icon pack that adds icons for files like Markdown, Yaml, Maven, Git and many many others.
You will get used to it as it helps to easily recognize files. It's for sure recommended.

Those are my top 5 + 1 most used plugins :)  
What are yours?
