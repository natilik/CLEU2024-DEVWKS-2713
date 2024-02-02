## Introduction
In this workshop, we'll explore how OpenTelemetry can help you gain valuable insights into the performance and behavior of your software in complex, distributed environments.

OpenTelemetry is an open-source project that provides a standardized way to collect traces and metrics from your applications. It's designed to be language-agnostic, scalable, and compatible with various observability backends, offering flexibility and ease of integration.

In the era of microservices and cloud-native architectures, understanding how different components of your application interact and perform is crucial. OpenTelemetry makes this task easier by providing a unified set of APIs and libraries for instrumenting your code, allowing you to trace requests and collect metrics seamlessly.

In this workshop we will deploy The OpenTelemetry Astronomy Shop Demo which is an excellent resource for showcasing the value of OpenTelemetry in a tangible and relatable context. 

In this workshop you will have a pre-built `kind` (Kubernetes in Docker) Kubernetes cluster available.

We will be covering the following areas:
- Deploy OpenTelemetry Astronomy Shop
- Explain OpenTelemetry Astronomy Shop micro-services architecture
- Walk through the integration of OpenTelemetry with popular observability tools - Shop, Grafana, Jaegar and Locust
- Breaking stuff - Injecting errors
