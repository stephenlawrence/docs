+++
date = "2017-06-30T00:00:00Z"
lastmod = "2017-06-30T00:00:00Z"
title = "Docker 17.06 CE and v1 Registry Protocol"
weight = "999999"
categories = [ "Knowledgebase", "Developer Resources" ]
+++

[Changes to Docker v17.06](https://docs.docker.com/release-notes/docker-ce/#17060-ce-2017-06-28) CE edition have removed support for v1 registry protocol. Because of this change, images that were originally pushed
with v1 protocol will no longer work as expected during pull operations.

The easiest way to resolve this issue is to re-push your images using a recent version of Docker so that it will be pushed as v2 registry protocol.
