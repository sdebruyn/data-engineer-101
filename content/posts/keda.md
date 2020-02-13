---
title: "Keda"
tags: ["tool", "kubernetes"]
uri: "https://keda.sh"
img: "keda.png"
free: true
---

Keda stands for Kubernetes-based Event Driven Autoscaling. Like the name says, it allows you to configure your Kubernetes so that it automatically scales up or down. Keda uses "scalers" as sources of events to decide if the cluster has to be scaled. An example of such a scaler can be an AWS SQS Queue or an Azure Service Bus.