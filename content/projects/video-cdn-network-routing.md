---
title: Video CDN / Network Routing
date: 2023-10-19T08:11:19.700Z
description: Routing packets on a distributed, unknown network toplology along
  with implementing HTTP streaming
taxonomies:
  tags:
    - Python
    - Networks
    - DistributedSystems
extra:
  image: /media/screenshot-2024-07-04-at-4.14.59-pm.png
  link: " "
---
## C﻿DN:

* D﻿designed Server Model (thread based server) to handle video streaming requests (Can Serve 1000+ clients)
* H﻿ttp compliant error codes and partial content segmentation based on specified maximum segment size
* F﻿iletype agnostic implementation

## R﻿outing:

•Designed custom packet and heartbeat messaging for link state advertisement

•Can run on any machine to act as a node in the network

•Config parsing and online network updates

• Every node can output the whole network topology when queried