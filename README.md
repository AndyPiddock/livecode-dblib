# DB Lib

Introduction
============
I've wanted to build this library since forever. After using similar libraries with PHP and Ruby, I decided that we really needed some 
easy library for database access but I always postponed creating one.

After Ralf released RevIgniter (http://www.revigniter.com) I became spoiled by his database implementation. It was perfect but it worked
only on the server side. Now with my mobile developments, I needed something that worked locally with SQLite. So I decided to build
this library.

Documentation
==============
Check the PDF that is bundled with this download, really, please!!!! Also check out the docs generated by RevDoc that are inside the docs folder.
Look into the code of the little demo stack that is bundled and read the source code from DB Lib itself.

This library is pretty small but it is clever. It will take very little time to read the code and understand everything. As always my libraries are
unlocked and the best documentation is the source code. 

Have I told you that the PDF is 30+ pages?

The API Docs have more information than the PDF, don't miss it. The guide is more pleasant but it is no substitute for the auto-generated docs

Support Forum
=============
Use the issues at this repository to ask for help or email me at support@andregarzia.com


What you are allowed to do?
===========================

You can use this library and its source code or parts of it in your own free or commercial products but please don't resell it as your own work.
LiveCode community is small, we all know each other so I trust you guys with all the source code because I know there is no way to maintain software with 
locked stacks.

Version History
===============

* 1.0: Initial Beta Release
* 1.1: Changes to dbWhere and dbLike.
	* added new concatenation to dbWhere and dbLike
	to make possible to do OR. Check API docs.
* 1.2: Fixed a bug in both dbWhere and dbLike where issuing multiple dbWhere
     for the same column would cause problems.
* 1.3: Bug fixing.
* 1.4: Changes to documentation and links to forum.
* 1.9: Bug fixing regarding database connection ids.
* 1.10: Added null and not null options to dbWhere.
* 1.11: New build system. (built on: Tue, 11 Sep 2012 12:55:55 -0300)
* DataStorage Lib 0.3 BETA: Bug fix in dsGet() due to missing key. (built on: Tue, 18 Sep 2012 02:19:38 -0300)
* DB Lib 1.12: Improvements to build system. New DS version. (built on: Tue, 18 Sep 2012 02:20:35 -0300)
* DB Lib 1.13: Adding optional parenthesis to where clauses (built on: Fri, 26 Oct 2012 18:12:11 -0200)
* DB Lib 1.14: Adding support for RevIgniter (built on: Fri, 26 Oct 2012 18:25:50 -0200)
* DB Lib 1.15: Added dbLastSQL, dbIn and dbNotIn handlers (built on: Fri, 9 Nov 2012 15:00:17 -0200)
* DB Lib 1.17: Added GPLv3 dual licensing. (built on: Tue, 21 May 2013 13:08:55 -0300)
