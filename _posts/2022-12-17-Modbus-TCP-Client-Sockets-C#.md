---
title: "Modbus TCP Client example by using sockets in C#"
categories:
  - blog
---

Very simple Modbus TCP Client example coded in C# that uses network .NET sockets library (System.Net.Sockets) to read holding registers from a Modbus TCP Server device. 
No EXTERNAL Modbus libraries like EasymodbusTCP are used.

Firstly the connection through a network socket is established, then a Modbus request message is constructed and sent to the ModbusTCP Server. Lastly the socket is waiting for response from Modbus TCP Server. 
ModRSsim2 can be used to simulate the Modbus TCP Server device.


<a href="https://github.com/kallileo/Modbus-TCP-Client-Example">Modbus TCP Client example by using sockets in C# - GitHub</a>

