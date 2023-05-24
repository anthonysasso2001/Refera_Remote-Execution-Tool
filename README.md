<!--
 Copyright 2023 Anthony Sasso. All rights reserved.
 Use of this source code is governed by a BSD-style
 license that can be found in the LICENSE file.
-->

# **Refera - Remote Execution Tool**

- [**Refera - Remote Execution Tool**](#refera---remote-execution-tool)
  - [**Introduction**](#introduction)
  - [**Goals, Requirements, User-Stories**](#goals-requirements-user-stories)
    - [Remote](#remote)
    - [Encrypted](#encrypted)
    - [File](#file)
    - [Execution](#execution)
    - [Return](#return)
    - [Assistant](#assistant)

## **Introduction**

Refera is an acronym for:

**R**emote \
**E**ncrypted \
**F**ile \
**E**xecution \
**R**eturn \
**A**ssistant

## **Goals, Requirements, User-Stories**

The goals of this program are the following user stories as listed (categorized in each topic):

### Remote

- [ ] This program shall execute code on a remote server.
  - [ ] This server shall be any of the following: linux, bsd, OR windows operating systems.

### Encrypted

- [ ] This program shall encrypt the server-side cache using a public-private key stream cipher known only to the sending client.
- [ ] After receiving the terminal output from the server, this program shall be able to decrypt the terminal output file using the private key.
- [ ] This program shall save the public-private key pairs for reuse or cataloguing within a key-value pair DB.
- [ ] This program shall allow a proxy function with that server wrapping cached files in it's own public-private key between the server and it.
  - [ ] The proxy shall do so without having knowledge of the clients private key.

### File

- [ ] The program shall store the Key-Value(s) pairs used in encryption in a client side DB which will archive returned output files.
  - [ ] This DB should use a generated Key which will also be used to name the terminal output file on the server & client sides.
- [ ] The DB should Support additional security parameters, such as a password, and sub-passwords for specific collections of Key-Value(s) pairs.

**TODO** FINISH REST OF README / REQUIREMENTS

### Execution

- [ ] 

### Return

### Assistant
