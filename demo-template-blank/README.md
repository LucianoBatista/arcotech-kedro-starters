# {{ cookiecutter.project_name }}

## Overview

Esse projeto utiliza o `kedro` como framework de experimentação. Antes rodar o projeto, siga os seguintes passos:
1. Clone esse repositório para sua máquina local
1. `cd {{ cookiecutter.repo_name }}`
2. Instale as dependências rodando o `uv sync`
3. Ative o ambiente virtual criado (`source venv/bin/activate`)
4. [Logue](https://github.com/arcotech-services/guidelines/tree/main/aws#:~:text=admin%2Drole%22%20run%3A-,saml2aws%20configure%20%5C,-%2D%2Dusername%3Dyour%2Demail) na AWS via CLI
5. Instale o `pre-commit`, rodando `pre-commit install`
6. Puxe os dados do versionamento (`dvc pull`)
7. Visualize todo o pipeline (`kedro viz`)
8. Rode todo o pipeline (`kedro run`)

...
