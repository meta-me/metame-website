---
layout: question
title: How does MetaMe store my data?
section: General
---

{{ site.productname }} stores your computer usage data in a local SQLite database. You can find out more about SQLite [here](https://www.sqlite.org). 

The SQLite database can be found at '%LocalAppData%\MetaMe\UNIQUE_ID\database.sqlite3', where UNIQUE_ID is a unique id generated by {{ site.productname }}.