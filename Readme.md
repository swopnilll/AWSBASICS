# Amazon Elastic Compute Cloud (Amazon EC2) Overview

## Introduction

**Amazon EC2** provides secure, resizable compute capacity in the cloud. It is a highly flexible, cost-effective, and quick way to gain access to virtual servers compared to traditional on-premises servers.

## Key Concepts

### Client-Server Model in EC2

- The client/server model is a fundamental concept where a client sends a request to a server, the server processes it, and then sends a response.
- Example: In a coffee shop, the client requests coffee, and the barista (server) prepares and delivers it.

### Use Cases for EC2

- EC2 is applicable across various industries such as healthcare, manufacturing, insurance, and video content delivery.
- Businesses require raw compute capacity to host applications and provide necessary compute power.

## Benefits of Using EC2

### Flexibility

- **Quick to get started:** AWS has already built and secured the data centers, bought the servers, and made them ready for use.
- Easily launch and terminate EC2 instances within minutes as needed.

### Cost Efficiency

- Only pay for running instances, not stopped or terminated instances.
- Avoid upfront costs associated with purchasing and maintaining physical servers.
- Scale resources up or down based on demand, avoiding over-provisioning.

### Quick Provisioning

- Compared to on-premises resources, EC2 instances can be launched and ready to use much faster.

### Multitenancy and Virtualization

- EC2 runs on physical host machines managed by AWS using virtualization technology.
- Multiple EC2 instances (virtual machines) share the underlying physical resources of a host machine.
- The hypervisor coordinates this multitenancy, ensuring security and isolation between instances.

## EC2 Features

### Instance Configuration

- Choose the operating system (Windows or Linux) and the specific hardware configuration (instance type) for your EC2 instances.
- Configure software running on the instance, including internal business applications, web apps, databases, or third-party software.
- Instances are resizable, allowing for vertical scaling by adding more memory and CPU as needed.

### Networking Control

- Control the type of network traffic that can flow into and out of your instances.
- Decide if instances are publicly or privately accessible.

## How Amazon EC2 Works

### Launch

1. **Select a Template:** Choose a template with basic configurations, including the OS, application server, and applications.
2. **Choose Instance Type:** Select the hardware configuration for your instance.
3. **Specify Security Settings:** Control network traffic into and out of your instance.

### Connect

- Multiple methods to connect to the instance, allowing for direct access and logging in.

### Use

- Install software, manage storage, and organize files as needed once connected to the instance.

## Summary

Amazon EC2 allows for easy provisioning and management of virtual servers in the cloud. It provides flexibility, cost-efficiency, and scalability, making it an ideal solution for businesses across various industries. By leveraging EC2, companies can innovate more quickly and focus on what differentiates their business, rather than managing infrastructure.
