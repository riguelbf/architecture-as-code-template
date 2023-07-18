# architecture-as-code-template

Simple template to use architecture as code to create documentation about any project using C4 template

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

``````
