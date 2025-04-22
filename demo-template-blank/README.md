# {{ cookiecutter.project_name }}

## Overview

Esse projeto utiliza o `kedro` como framework de experimentação. Antes rodar o projeto, siga os seguintes passos:
1. Clone esse repositório para sua máquina local
2. Instale as dependências rodando o `uv sync`
3. Ative o ambiente virtual criado (`source venv/bin/activate`)
4. [Logue](https://github.com/arcotech-services/guidelines/tree/main/aws#:~:text=admin%2Drole%22%20run%3A-,saml2aws%20configure%20%5C,-%2D%2Dusername%3Dyour%2Demail) na AWS via CLI
5. Instale o `pre-commit`, rodando `pre-commit install`
6. Puxe os dados do versionamento

```bash
uvx kedro new --starter git@github.com:LucianoBatista/arcotech-kedro-starters.git --directory demo-template-blank --telemetry no
```

After the project is created, navigate to the newly created project directory:

```bash
cd <my-project-name>  # change directory 
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Now you can run the project:

```bash
kedro run
```

To visualise the default pipeline, run:
```bash
kedro viz
```

This will open the default browser and display the following pipeline visualisation:

![](./images/pipeline_visualisation_with_layers.png)

