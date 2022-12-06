# Scaling-Group
[![Slack Status](https://img.shields.io/badge/slack-join_chat-white.svg?logo=slack&style=social)](https://knative.slack.com)

A standalone plugin component for Knative to prewarm the chained services, and accelerate service response, including scaling from zero and non-zero.

## Why do we need Scaling-Group?
A complete application may contain multiple microservices(assume it's equal to Knative services), and there is a chain call between microservices, as a result, cloud providers may encounter difficulties with quite long response times(chained code-start time). To alleviate this issue, Scaling-Group can scale up the chained Knative services simultaneously when they need to call each other. It will reduce the response time of requesting chained services. Also, the longer the requesting path, the more response time is reduced.


## How does Scaling-Group help accelerate chained services?
TBD

## Installation
TBD

## Performers test
TBD
