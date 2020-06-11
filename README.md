# SNOWtoFTP
Exporting a file from ServiceNow to FTP Server by scripting.

Files:
1) MIDServerScriptFileGenerator
      - The script is the MID Server Script (ecc_agent_script_include) to connect to the FTP Server and generate a file and send to the FTP Server.
2) ServerSideScriptJavascriptProbe
      - The script is the server side script such as Script Include, Business Rule, etc. to create JavascriptProbe to send the parameters and call the function in MIDServerScriptFileGenerator to generate a file and send to a FTP Server.


REMARK: The MID Server should be installed in a server that is located in the same network of the ftp server. 
