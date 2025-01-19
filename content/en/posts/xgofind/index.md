---
title: xgofind
date: 2024-11-16
author: yhk0
description: An HTTP and HTTPS traffic interceptor between client and server
tags:
  - HTTP
  - HTTPS
  - pentest
---

# XGOFIND
The goal of the **xgofind** project is to create a flexible and efficient HTTP interceptor proxy that enables real-time inspection, modification, and manipulation of HTTP and HTTPS traffic. This tool primarily aims to assist security 
professionals, developers, and researchers in tasks such as:

## How to use

```bash
$ go build cmd/proxy/main.go
$ ./main.go --port 8080
```
#### Parameters:
```bash
--help
--port
--dest
--log
```

### Security Testing (Pentesting):

Inspect and modify requests and responses to identify vulnerabilities in web applications.
Simulate attacks like header injections, payload manipulation, and authentication testing.

### Application Development and Debugging:

Monitor traffic between clients and servers to understand API and web application behavior.
Test request modifications without altering client or server code.

### Customizable Flexibility:

Enable the extension of the proxy with new features, such as detailed logging, header injection, or custom traffic manipulation rules.

---------------------------
The xgofind project is designed to be simple, modular, and open-source, allowing users to adapt the tool to their specific needs. It also serves as an educational project for exploring Go’s capabilities in building network-based applications.

see more on [Github](https://github.com/yhk0/xgofind)