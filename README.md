# Mule Parquet File Connector

The project is inspired from the sources below. Please have a look- 

Website: https://dejim.com/how-to-read-and-write-apache-parquet-files-in-mulesoft/?utm_source=rss&utm_medium=rss&utm_campaign=how-to-read-and-write-apache-parquet-files-in-mulesoft
Youtuebe: https://youtu.be/V2TL4H5EB7I
GitHub: https://github.com/djuang1/parquet

## Tech Used
- The connector is completely written in Java with latest Mule-Sdk

## Features
- Convert sample JSON data into Parquet format and write it into a file
- Read a Parquet file and convert it back into JSON format

## Prerequisites
- Mule-4 or above
- You need to create Avro schema for your JSON Data

## Installation

Install the dependencies and devDependencies and start the server.

1) Clone the the project into your local system
2) Go to the folder consisting of pom.xml
3) open Command Propmt(CMD) and Run the below maven command

```sh
mvn clean install -DskipTests
```
4) Now the connector is installed into your local system.
5) It's time to use it into your Mule project 
6) Add below dependency into your pom.xml file 

```sh
<dependency>
    <groupId>com.apisero</groupId>
	<artifactId>mule-parquet-connector</artifactId>
	<version>1.0.2</version>
</dependency> 
```
7) Now you can see the connector in the palletes
8) Drag and Drop it into canvas and feel free to use
