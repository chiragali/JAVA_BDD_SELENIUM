# seafarer-db-web-qa-automation

This repo is related to test automation of seafarer - synergy

1. Requirement :- 
	Java 8, 
	Maven - Download from here - https://maven.apache.org/download.cgi 

2. Environment Variable :- Set variable path of Java and Maven in Environment variable of local machine.
	For Maven :- {Path where Maven is located}\bin
	
3. Command to run the Code :- Go to Project Location and run following command

	mvn test verify -Dcucumber.options="--tags @<tag_name>" "-DexcelFilePath={Path where 'Testdata.xlsx' is located}\\TestData.xlsx" "-DsheetName=Data"
	
	For e.g :- mvn test verify -Dcucumber.options="--tags @REGRESSION" "-DexcelFilePath=C:\\Projects\\Synergy\\TestData.xlsx" "-DsheetName=Data"

"# JAVA_BDD_SELENIUM" 
