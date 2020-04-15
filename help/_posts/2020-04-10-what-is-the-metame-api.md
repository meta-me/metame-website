---
layout: question
title: What is the MetaMe REST API?
section: REST API
---

The REST API is useful for getting data and statistics about your computer usage along with many other functions. MetaMe REST API is a web service exposed by the MetaMe.WindowsClient.exe process.

The REST API is exposed at the following endpoint:

```
http://localhost/Temporary_Listen_Addresses/MetaMe/api
```

#### Using the REST API
To test whether the API is running, open in a browser the following url: 

```
http://localhost/Temporary_Listen_Addresses/MetaMe/api/foreground
```
This shows information on your current foreground window.

You can also get data access to [time series](/help/2020/04/08/how-do-i-export-time-series-using-api), and also the [most used application](/help/2020/04/08/how-do-i-export-most-used-apps) in this way.