# sem2-pi-24.25-g121-repo
 
This repository contains the development of the Integrative Project for the second semester of the 2024/25 academic year. The project aims to create an IT solution that simulates the operation of railway networks. It’s developed within the scope of the following courses:
 
 **・ESOFT** – Software Engineering
 
 **・PPROG** – Programming Paradigms
 
 **・MATCP** – Computational Mathematics
 
 **・MDISC** – Discrete Mathematics
 
 **・LAPR2** – Laboratory Project II
 
 
 The solution is divided into two main components:
 
 1. **Map and Scenario Editor** – Allows the creation of maps with cities and industries and the definition of scenarios with historical and technological context.
 
 2. **Simulation Tool** – Enables the management of railway networks, including stations, trains, routes, and cargo transportation, with tools for performance analysis and network connectivity evaluation.

# Project Structure
src/main/java/ – Main application source code.  
src/main/resources/ – Resources used by the application (configuration files, etc).  
src/test/java/ – Automated tests.  
Data/ – Serialised data for maps, scenarios, and simulations.  
MATCP/ – Algorithms and statistical analyses developed for MATCP.  
MDISC/ – Examples, graphs, and artefacts related to discrete mathematics.  
UserManual_SelfAssessment/ – User manual and self-assessment.  
brainStorming/ – Diagrams, ideas, and initial planning.  
docs/ – Detailed documentation, global artefacts, and team tasks.  
javadoc/ – Automatically generated Java code documentation.

# Technologies Used
- Java 17+  
- Maven (dependency and build management)  
- JUnit (testing)  
- PlantUML (diagrams)

# Credits
Project developed for the curricular unit LAPR2 (2024/2025).  
This project was developed with the collaboration of the following team:  
- [André Pinho](https://github.com/AndreSiPinho)  
- [Bianca Almeida](https://github.com/Brma505)  
- [Carlota Lemos](https://github.com/carlotalemos)  
- [Eduardo Almeida](https://github.com/EduardoAlmeida-1241418)  
- [Mara Santos](https://github.com/1241452)

# How to Build and Run
Ensure you have Java 17+ and Maven installed.

## Build
mvn clean install

## Run
mvn exec:java -Dexec.mainClass="<main-class-path>"
