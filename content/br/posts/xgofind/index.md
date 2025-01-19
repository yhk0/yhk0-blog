---
title: xgofind
date: 2024-11-16
author: yhk0
description: um interceptor de trafico http e https entre cliente e servidor
tags:
  - HTTP
  - HTTPS
  - pentest
---

# XGOFIND
O objetivo do projeto **xgofind** é criar um proxy interceptor HTTP flexível e eficiente que permita a inspeção, modificação e manipulação em tempo real do tráfego HTTP e HTTPS. 
Esta ferramenta visa principalmente auxiliar profissionais de segurança, desenvolvedores e pesquisadores em tarefas como:

# Como usar:

```bash
$ go build cmd/proxy/main.go
$ ./main.go --port 8080
```
#### Parametros:
```bash
--help
--port
--dest
--log
```

# Testes de Segurança (Pentesting):
Inspeção e modificação de requisições e respostas para identificar vulnerabilidades em aplicações web. Simulação de ataques como injeções de cabeçalho, manipulação de payloads e testes de autenticação.

# Desenvolvimento de Aplicações e Depuração:
Monitoramento do tráfego entre clientes e servidores para entender o comportamento de APIs e aplicações web. Teste de modificações em requisições sem alterar o código do cliente ou do servidor.

# Flexibilidade Customizável:
Possibilita a extensão do proxy com novas funcionalidades, como logging detalhado, injeção de cabeçalhos ou regras customizadas de manipulação de tráfego.

veja mais no [Github](https://github.com/yhk0/xgofind)