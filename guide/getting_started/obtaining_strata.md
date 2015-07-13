---
title: Obtaining Strata
permalink: /obtaining_strata/
---

There are a number of ways to obtain Strata.


## From Maven Central

Strata is available in Maven Central.

To reference the top-level Report module, add the following dependency:

```
<dependency>
  <groupId>com.opengamma.strata</groupId>
  <artifactId>strata-report-beta</artifactId>
  <version>0.7.0</version>
</dependency>
```

## From GitHub Releases

Strata is also released to GitHub through the standard [repository release pages](https://github.com/OpenGamma/Strata/releases). The downloads include:

 * `strata-dist` -- the full Strata distribution containing the Strata jars, Strata's dependencies and Javadoc.
 * `report-tool` -- the [command-line tool](command_line_tool) for easy access to the reporting capabilities.
 * Source code -- the source code as of the release, documentation source and tool chain.

## For Developers

### Source code

As noted above, the source code for Strata is available from GitHub releases, however, the most up-to-date code can be obtained directly from [GitHub](https://github.com/OpenGamma/Strata). To do this you will need [Git](https://git-scm.com/download/).

Simply clone the repository locally:

```
    git clone https://github.com/OpenGamma/Strata.git
```

### Building

To build Strata from source code, the following dependencies are required:

 * Java SE Development Kit (JDK) 8
 * Maven 3.2 or later

To build, simply change to the root directory of the cloned source code, and from the command line run:

```
$ mvn compile
```

### Using an IDE

Strata works out-of-the-box with most IDEs and no special settings are required.

The Strata codebase should be imported as a Maven project using the included `pom.xml`.

To help with contributions back to Strata, settings are included in the codebase for the Eclipse IDE providing formatting rules and templates. For further information on working with Strata in the Eclipse IDE see [here](https://github.com/OpenGamma/Strata/tree/master/eclipse).
