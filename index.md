---

layout: col-sidebar
title: OWASP Damn Vulnerable Web Sockets
tags: example-tag
level: 1
type: 
pitch: A very brief, one-line description of your project

---

Damn Vulnerable Web Sockets (DVWS) is a deliberately vulnerable and insecure web application which works on web sockets for client-server communication. It is built on PHP with Ratchet and utilizes MySQL as backend database. It allows users to test their web sockets testing skills, tools and scripts for web socket vulnerabilities. Web socket testing can be performed using popular tools such as OWASP ZAP and Burp Suite.

## Description
_Damn Vulnerable Web Sockets (DVWS)_ is a deliberately vulnerable and insecure web application which works on web sockets for client-server communication. It is built on PHP with Ratchet and utilizes MySQL as backend database. DVWS has a number of functionalities which you commonly see in every other web application, they have been implemented in web sockets which is different from a typical web application communication.

The following vulnerabilities can be found:
- Brute Force
- Command Execution
- Cross-Site Request Forgery
- File Inclusion
- Error based SQL Injection
- Blind SQL Injection
- Reflected Cross-Site Scripting
- Stored Cross-Site Scripting
- Session Management Issues
- Cross Origin Issue

It requires the following to work properly:
- Apache + PHP + MySQL
- PHP with MySQLi support
- Ratchet
- ReactPHP-MySQL
Note: Ratchet and ReactPHP-MySQL are packaged inside DVWS. Separate installation is not required.

## Licensing
This program is free software: you can redistribute it and/or modify it under the terms of the MIT License.
