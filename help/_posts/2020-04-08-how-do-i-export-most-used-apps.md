---
layout: question
title: How do I export the most used apps for a given time period?
section: REST API
---

You can export the top x applications used for a time period using following endpoint:

```
http://localhost/Temporary_Listen_Addresses/MetaMe/api/analytics/most-used-apps?start={start}&end={end}&limit={limit}
```

For top x applications in a group you can use the optional group parameter:

```
http://localhost/Temporary_Listen_Addresses/MetaMe/api/analytics/most-used-apps?start={start}&end={end}&limit={limit}&group={group}
```

Parameters
- *start* is the start of the period as a date in the format *YYYY-MM-DDTHH:mm:ss.sssZ* 
   - E.g. April 1st, 2020 7PM UTC = 2020-04-01T19:00:00.000Z
- *end* is the end of the period as a date in the format *YYYY-MM-DDTHH:mm:ss.sssZ* 
- *limit* is the number of records to return
- (Optional) *group* can be specified to only include applications in the specified group. Only supports values *Productive*, *Unproductive*, and *Neutral*