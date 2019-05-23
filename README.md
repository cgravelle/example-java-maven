# [:] Example Maven Project

[![Build Status](https://travis-ci.org/cgravelle/example-java-maven.svg?branch=master)](https://travis-ci.org/cgravelle/example-java-maven)
[![Black Duck Security Risk](https://copilot.blackducksoftware.com/github/repos/cgravelle/example-java-maven/branches/master/badge-risk.svg)](https://copilot.blackducksoftware.com/github/repos/cgravelle/example-java-maven/branches/master)

An example maven project to demonstrate [srcclr](https://www.srcclr.com) scans.

## Try me!

```
brew tap srcclr/srcclr
brew install srcclr
srcclr activate
srcclr scan --url https://github.com/srcclr/example-java-maven
```

## With SourceClear's Maven Plugin
```
git clone https://github.com/srcclr/example-java-maven
cd example-java-maven
mvn clean compile com.srcclr:srcclr-maven-plugin:scan -DapiToken=<yourSourceClearToken>
```
