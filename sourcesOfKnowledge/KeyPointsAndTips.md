<h3>Creating dashboards</h3>
<p align="justified">In order to be able to analyze the results of the test there is an option to create dashboards. A dashboard is based on a generated jtl file. In order to generate a dashboard run the command: -g <path to jtl file> -o <path where the dashboard should be created>.</br> Example: jmeter -g ImportMatrixMerged1.jtl -o C:\dashboard1</p>
  
  <h3>Connecting databases</h3>
<p align="justified">With Jmeter it is possible to access the database, run queries and store the results into variables.</br>
To be able to do this you this you will need a <a href="https://docs.microsoft.com/en-us/sql/connect/jdbc/download-microsoft-jdbc-driver-for-sql-server?view=sql-server-2017">JDBC driver this can be downloaded here.</a></br>
After downloading copy the jar file (mssql-jdbc-7.2.2.jre8) place it into the apache "lib" ( \apache-jmeter-5.1.1\lib ) folder of Jmeter.</br>
Note: Jmeter should be closed and restarted in order to pick up the configuration.</br>

<h3>Apdex</h3>
<p align="justified">The APDEX user a toleration threshold and a frustration threshold. These thresholds can be configured per measured API. Of course you will need the thresholds as non functional requirements to be able to configure it. The dashboard makes use of an Application Performance Index APDEX. <a href="https://en.wikipedia.org/wiki/Apdex">More information about APDEX can be found here.</a></p>
