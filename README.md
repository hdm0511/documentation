# Cacti (tm) Documentation

![Cacti](images/logo.png)

Cacti is designed to be a complete graphing solution based on the RRDtool's
framework. Its goal is to make a network administrator's job easier by taking
care of all the necessary details necessary to create meaningful graphs.

Please see the official Cacti website for information, support, and updates.

## Developers

- Ian Berry (raX)

- Larry Adams (TheWitness)

- Tony Roman (rony)

- J.P. Pasnak, CD (Linegod)

- Jimmy Conner (cigamit)

- Reinhard Scheck (gandalf)

- Andreas Braun (browniebraun)

- Mark Brugnoli-Vinten (netniV)

## Thanks

A very special thanks to Tobi Oetiker, the creator of RRDtool and the very
popular MRTG. The users of Cacti Especially anyone who has taken the time to
create an issue report, or otherwise help fix a Cacti related problems. Also
to anyone who has contributed to supporting Cacti.

Cacti is licensed under the GNU GPL:

This program is free software; you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation; either version 2 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT
ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

## Table of Contents

1. [Installation](README.md#installation)

   This section contains information on how to install and/or upgrade the
   Cacti system.  It covers requirements, different platforms and the steps
   needed to get your system working under normal circumstances.

2. [Standard Operations](README.md#standard-operations)

   This section covers materials from viewing your graphs to templates and
   script server operations.

3. [Advanced Operations](README.md#advanced-operations)

   This section covers more advanced material such as using a custom script
   or the replacement variables that can be used within templates, etc.

4. [Plugins](README.md#plugins)

   This section contains all Plugin related information.
   Guidelines, hooks, references, etc.
   More information can be found on the [Cacti Forums](https://forums.cacti.net/viewforum.php?f=6).

5. [How To's](README.md#how-tos)

   This section contains how to's for several topics.

6. [Contributing](README.md#contributing)

   This section contains information on how to contribute to Cacti.

7. [Development Standards](README.md#development-standards)

   This section contains the relevant information on how to ensure that any
   contribution is kept to the same standards that are applied for the Cacti
   Group.  It should be noted that non-compliance does not mean automatically
   exclusion of proposed changes.

### Installation

1. [Requirements](Requirements.md)

2. [General Installing Instructions](General-Installing-Instructions.md)

3. [Installing Under Windows](Installing-Under-Windows.md)

4. [Upgrading Cacti](Upgrading-Cacti.md)

### Standard Operations

1. [Principles of Operation](Principles-of-Operation.md)

2. [Graph Overview](Graph-Overview.md)

3. [How to Graph Your Network](How-to-Graph-Your-Network.md)

4. [Viewing Graphs](Viewing-Graphs.md)

5. [Aggregate Overview](Aggregate-Overview.md)

6. [User Management](User-Management.md)

7. [Graph a Single SNMP OID](Graph-a-Single-SNMP-OID.md)

8. [Data Input Methods](Data-Input-Methods.md)

9. [Data Queries](Data-Queries.md)

10. [Templates](Templates.md)

11. [PHP Script Server](PHP-Script-Server.md)

12. [Spine](Spine.md)

### Advanced Operations

1. [How to Graph a Custom Collection Script](How-to-Graph-a-Custom-Collection-Script.md)

2. [Frequently Asked Questions](Frequently-Asked-Questions.md)

3. [Variables](Variables.md)

4. [RRDTool Specific Features](RRDTool-Specific-Features.md)

5. [Command Line Scripts](Command-Line-Scripts.md)

6. [Debugging](Debugging.md)

7. [Version Specific Release Notes](Version-Specific-Release-Notes.md)

8. [Plugin Development](Plugin-Development.md)

### Plugins

1. [Plugin Guidelines](Plugin-Guidelines.md)

2. [Creating Plugins](Plugin-Creating-Plugins.md)

3. [References](Plugin-Reference.md)

4. [Hook API Reference](Plugin-Hook-API-Ref.md)

### How Tos

1. [Determine template version](How-To-Determine-Template-Version.md)

2. [Using SSH Tunnels](How-To-SSH-Tunnels.md)

3. [Data Query Templates](How-To-Data-Query-Templates.md)

### Contributing

1. [Contributing](Contributing.md)

2. [Translations](Contributing-Translations.md)

### Development Standards

1. [Documentation](Standards-Documentation.md)

2. [Code Formating](Standards-Code-Formatting.md)

3. [PHP Specific Constructs](Standards-PHP-Spec-Constructs.md)

4. [File System Layout](Standards-FileSystem-Layout.md)

5. [Patch Creation](Standards-Patch-Creation.md)

6. [SQL Standards](Standards-SQL.md)

7. [Security](Standards-Security.md)

---
Copyright (c) 2018 Cacti Group
