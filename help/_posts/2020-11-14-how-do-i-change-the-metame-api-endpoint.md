---
layout: question
title: How do I change the MetaMe API endpoint?
section: REST API
---

The default MetaMe API url is http://+:80/Temporary_Listen_Addresses/MetaMe/api. 

From version 0.20.1, you can change this url by going to Settings > General and changing the `--url` parameter. Click "SAVE & RESTART" to save the settings and restart.

The url prefix "+" or "*" must be used in place of "localhost"

<img class="m-1" src="/assets/metame-service-command-line-args.png" alt="MetaMe service command line arguments" width="300"/>

*Please note that MetaMe will require appropriate permissions for this. See [how to host MetaMe API on a different port](/help/2020/11/14/how-to-host-metame-api-on-a-different-port) for more detail.