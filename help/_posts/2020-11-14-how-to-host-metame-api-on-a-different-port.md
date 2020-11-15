---
layout: question
title: How do I host MetaMe API on a different port?
section: REST API
---

Hosting the MetaMe API on a different port involves setting up appropriate permissions, then updating the `--url` parameter in the settings.

## Step 1. Add urlacl permission for your url using netsh

E.g. to setup MetaMe API on port 9000 run the following:

`netsh http add urlacl url=http://+:9000/ user=\Everyone`

Note the trailing slash at the end of the url

## Step 2. Use netsh show urlacl to check the permission
Check that your new permission has been setup appropriately by running the following:

`netsh http show urlacl`

Check that your new entry is on the list.

## Step 3. Change the MetaMe `--url` setting
Open up MetaMe > Settings > General and modify the `--url` setting. See [this guide](/help/2020/11/14/how-do-i-change-the-metame-api-endpoint) for more details.

After restarting, MetaMe should be hosted on the new port