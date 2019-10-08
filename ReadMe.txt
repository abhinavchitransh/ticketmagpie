dependency check is neither part of the build nor site

mvn dependency-check:check

mvn package sonar:sonar
    dependency check report is loaded to sonar since it is not cleaned after previous step

mvn clean package sonar:sonar

SonarLint
    - Analyze All Files with SonarLint
