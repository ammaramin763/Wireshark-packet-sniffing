# Wireshark-packet-sniffing

Objectives


− To efficiently capture network packets using Wireshark.



− To explore the HTTP message formats and basic operations of HTTP protocol.


In this project, I will perform higher layer Wireshark packet sniffing to explore the HTTP message formats and 
basic operations of HTTP protocol. Also complete TCP handshake and messages will be discussed further. 




✔✔ Answer the following Questions:



Inspect the contents of the first HTTP GET request from your browser to the 
server. Do you see an “IF-MODIFIED-SINCE” line in the HTTP GET?


Inspect the contents of the server response. Did the server explicitly return the 
contents of the file? How can you tell?


 Now inspect the contents of the second HTTP GET request from your browser to 
the server. Do you see an “IF-MODIFIED-SINCE:” line in the HTTP GET? If 
so, what information follows the “IF-MODIFIED-SINCE:” header?


 What is the HTTP status code and phrase returned from the server in response to 
this second HTTP GET? Did the server explicitly return the contents of the file? 
Explain.

 How many HTTP GET request messages did your browser send? Which packet 
number in the trace contains the GET message for the Bill or Rights?

 Which packet number in the trace contains the status code and phrase associated 
with the response to the HTTP GET request?

 What is the status code and phrase in the response?

  
 How many data-containing TCP segments were needed to carry the single HTTP 
response and the text of the Bill of Rights?

 What is the server’s response (status code and phrase) in response to the initial 
HTTP GET message from your browser?


 When your browser’s sends the HTTP GET message for the second time, what 
new field is included in the HTTP GET message?



