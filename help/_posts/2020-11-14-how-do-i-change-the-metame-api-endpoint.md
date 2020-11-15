---
layout: question
title: How do I change the MetaMe API endpoint?
section: REST API
---

The default MetaMe API url setting is http://+:80/Temporary_Listen_Addresses/MetaMe/api. 

This url setting can be changed by going to Settings > General and modifying the `--url` parameter. Click "SAVE & RESTART" to save the settings and restart.

The url prefix "+" or "*" must be used in place of "localhost"

<img class="m-1" src="/assets/metame-service-command-line-args.png" alt="MetaMe service command line arguments" width="300"/>

MetaMe will require appropriate permissions setup for this. See [how to host MetaMe API on a different port](/help/2020/11/14/how-to-host-metame-api-on-a-different-port) for more detail.