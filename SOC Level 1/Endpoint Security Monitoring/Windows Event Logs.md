<h1> Windows Event Logs </h1>

<h3> Task 2  Event Viewer </h3>
  ANSWER 1:	40961 <br/>
  ANSWER 2: whoami <br/>
  ANSWER 3: Execute a Remote Command <br/>
  ANSWER 4: Pipeline Execution Details <br/>

<h3> Task 3  wevtutil.exe </h3>
  ANSWER 1:	1071 <br/>
  ANSWER 2: event log, log file, structured query <br/>
  ANSWER 3: /lf:true <br/>
  ANSWER 4: Xpath query <br/>
  ANSWER 5: Application <br/>
  ANSWER 6: Event read direction <br/>
  ANSWER 7: Maximum number of events to read<br/>
  
<h3> Task 4  Get-WinEvent </h3>
  ANSWER 1:	OpenSSH/Admin,OpenSSH/Operational <br/>
  ANSWER 2: Microsoft-Windows-PowerShell-DesiredStateConfiguration-FileDownloadManager <br/>
  ANSWER 3: 192 <br/>
  ANSWER 4: -MaxEvents <br/>
  ANSWER 5: 4 <br/>

<h3> Task 5  XPath Queries </h3>
  ANSWER 1:	Get-WinEvent -LogName Application -FilterXPath '*/System/Provider[@Name="WLMS"] and */System/TimeCreated[@SystemTime="2020-12-15T01:09:08.940277500Z"]' <br/>
  ANSWER 2: Get-WinEvent -LogName Security -FilterXPath '*/EventData/Data[@Name="TargetUserName"]="Sam" and */System/EventID=4720' <br/>
  ANSWER 3: 2 <br/>
  ANSWER 4: A user account was created <br/>
  ANSWER 5: 12/17/2020 1:57:14 PM <br/>
  ANSWER 6: Microsoft-Windows-Security-Auditing <br/>

<h3> Task 7  Putting theory into practice </h3>
  ANSWER 1:	400 <br/>
  ANSWER 2: 12/18/2020 7:50:33 AM <br/>
  ANSWER 3: 27736 <br/>
  ANSWER 4: PC01.example.corp <br/>
  ANSWER 5: $Va5w3n8 <br/>
  ANSWER 6: 8/25/2020 10:09:28 PM <br/>
  ANSWER 7: 6620 <br/>
  ANSWER 8: S-1-5-32-544 <br/>
  ANSWER 9: 4799 <br/>
 
