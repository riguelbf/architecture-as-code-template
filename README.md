
Tabela de conteúdos
=================
<!--ts-->
* [About project)](#about-project)
* [What is Architecture-as-Code (AaC)?](#what-is-architecture-as-code-aac)
* [Motivation](#motivation)
* [How does the folder structure work?](#how-does-the-folder-structure-work)
* [References](#references)
* [Necessary tools](#necessary-tools)

# About project

Simple template to use architecture as code to create documentation about any project using C4 template

# What is Architecture-as-Code (AaC)?

Architecture-as-Code is under major construction at the moment, including this documentation. We’re doing a major design and implementation overhaul to address 3 primary objectives:

* Adoptability / Approachability - If AaC is going to provide any value, the intended stakeholders must be willing to use it and get value from it.
* Extensibility - The domains we work in are complex and require tailoring of any solution. Ensure AaC provides an approachable solution for extension.
* Productivity / Efficiency - Embrace the DevOps principle of Flow by providing key automations to bridge MBSE and product development / delivery.

# Motivation

> Teams with good documentation deliver software faster and more reliably
than those with poor documentation
Accelerate State of DevOps Report, Google 2021

Architectural documentation is one of the team's many responsibilities. Keeping architecture documentation consistent and up-to-date can be a challenging and time-consuming task, especially when things change quickly and the tools are not appropriate. Disturbing workflows, lack of automation and version control, as well as storing documentation separately from code are frequently encountered problems. As a result, architecture documents can become inconsistent and out of date.

# How does the folder structure work?

```bash

├── src
│   ├── ADRs
│   │   ├── README.md // explaining how, why, ex, etc..
│   │   ├── Theme-1
│   │   │   ├── Something_1.md
│   │   │   ├── Something_2.md
│   ├── RFCs
│   │   ├── README.md // explaining how, why, ex, etc..
│   │   ├── Theme-1
│   │   │   ├── Something_1.md
│   │   │   ├── Something_2.md
│   ├── C4-Model // do not reach C4 leave this part to the devs so that it is not imposing but suggestive
│   │   ├── README.md // explaining how, why, ex, etc..
│   │   ├── C1.drawio
│   │   ├── C2.drawio // if necessary
│   │   │   ├── Diagrama_Dinamico.drawio (shows how elements in a static model collaborate at runtime, eg. us)
│   │   │   ├── Diagrama_de_Implementacao.drawio (allows you to illustrate how the software systems/containers in the static model are mapped to the infrastructure)
│   │   ├── C3.drawio // if necessary
│   │   │   ├── Component-1
│   │   │   │   ├── Workflows-1.drawio
│   │   │   │   ├── Workflows-1.drawio
│   ├── Data
│   │   ├── ER_DB1.model // some schema
│   │   ├── ER_DB1.png  // some image of schema
├── Glossary_Service.md
├── README.md
├── CONTRIBUITING.md
├── CURRENT_ARCHITECTURE_IMAGE.png
├── cli-automation.sh // bash tool for help during the implementation

```

# References

* [Software Architecture As Code Tools](https://newsletter.techworld-with-milan.com/p/software-architecture-as-code-tools)
* [Architecture-as-Code (AaC)](https://jondavid-black.github.io/AaC/)
* [Architecture as code: The key to cloud success](https://www.cio.com/article/238479/architecture-as-code-the-key-to-cloud-success.html)
* [Pulumi Blog - Architecture as Code](https://www.pulumi.com/blog/architecture-as-code-intro/)
* [Top 7 diagrams as code tools for software architecture](https://icepanel.medium.com/top-7-diagrams-as-code-tools-for-software-architecture-1a9dd0df1815)

# Necessary tools

* [VsCode](https://code.visualstudio.com/)
* [VsCode Drawio extension](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio)
