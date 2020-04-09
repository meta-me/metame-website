---
layout: question
title: How do I export my time series data?
section: REST API
---

You can export your time series data using following endpoint:

```
http://localhost:9000/api/series?groupName={groupName}&start={start}&interval={interval}&length={length}
```

Parameters
- *groupName* must be one or more of the following: *Productive*, *Unproductive*, *Neutral*
- *start* is the starting datetime of the series in the format *YYYY-MM-DDTHH:mm:ss.sssZ* 
   - E.g. April 1st, 2020 7PM UTC = 2020-04-01T19:00:00.000Z
- *interval* is the period between each data point in minutes. 
- *length* is the number of data points. 