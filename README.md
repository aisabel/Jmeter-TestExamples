
<h2> Jmeter-TestExamples </h2>
<h2>Description</h2>
<p align="justified">This repository contains practice scripts using Jmeter for performance testing.</br>
Below a basic guide on how to install,run, architecture folder structure and useful resources.</p>

<h2>Architecture folder structure</h2>
<ul>
  <li>Examples > Contains the csv sample files </li>
  <li>Test Plan - IntroductionTestExamples > Contains the actual tests excercises </li>
  <li>SourcesOfKnowledge > Contains the key tips, cheatsheet, pdf guide with terms </li>
</ul>

<h2>Install</h2>
<p>The Apache JMeter™ application is open source software, a 100% pure Java application designed to load test functional behavior and measure performance. This repository is using version apache-jmeter-5.1.1. The tool can be downloaded at: https://jmeter.apache.org/download_jmeter.cgi</br>
</p>

<h2>Run Tests: </h2>
<h3>How to run tests locally by UI</h3>
<ul>
  <li>Install Jmeter </li>
  <li>Double click in Jmeter batch file (jmeter.bat) </li>
  <li>In the top menu go to File > Open and locate the file with the jmx extension (example: Jmeter-IntroductionTestsExamples.jmx)</li>
  <li>Click on the green top play button > to run all tests  </li>
  <li>Under each ThreadGroup you can see a "View Results Tree". To verify results of the tests individually</li>
  <li>Summary report displays a table with results</li>
 </ul>
<h3>How to run tests from the command line</h3>
<ul>
  <li>To run the testplan from the command line you need to open a command prompt</li>
  <li>Traverse locally until jmeter bin folder is located (ex: \apache-jmeter-5.1.1\bin)</li>
  <li>Run the command: jmeter -n -t <path to jmx file> -l <name of the JTL file where the results are logged></il>
    <li>Parameters:
<ol>-n: This specifies JMeter is to run in cli mode</ol>
<ol>-t [name of JMX file that contains the Test Plan].</ol>
<ol>-l [name of JTL file to log sample results to]</ol>
<ol>.-j [name of JMeter run log file].</ol>
<ol>- r Run the test in the servers specified by the JMeter property "remote_hosts"</ol>
<ol>-R [list of remote servers] Run the test in the specified remote servers</ol>
<ol>-g [path to CSV file] generate report dashboard only-egenerate report dashboard after load test</ol>
<ol>-o output folder where to generate the report dashboard after load test. Folder must not exist or be empty</ol>
    </li>
</ul>
    
<h2>External references: </h2>
<ul>
 <li><a href="https://jmeter.apache.org/usermanual/get-started.html">Apache Jmeter Foundation (User manuals)</a></li>
<li><a href="https://academy.blazemeter.com/">BlazeMeter Academy</a></li>  
<li><a href="https://www.blazemeter.com/university/">BlazeMeter University</a></li>

