# Traffic Sign Detection

Bem vindos! Os objetivos deste projeto sao:

- Treinar modelos de reconhecimento de sinais de transito
- Criar um dataset para testar os modelos treinados
- Definir metricas de desempenho 
- Avaliar os modelos

# Setup

## 1. Verificando o repositorio no diretorio home

```sh
cd traffic-signs-recog-project
git pull origin master
```
Clonando o repositorio

```sh
git clone https://github.com/cjss2211/traffic_signs_recog_project.git
cd traffic_signs_recog_project
```

## 2. Ambiente Python 

Run `conda env create` para criar um ambiente chamado `traffic-signs`, como definido em `environment.yml`.
As bibliotecas python serao instaladas utilizando `pip-sync`
Para ativar o ambiente e instalar as dependencias.

```sh
conda activate traffic-signs
pip-sync requirements-dev.txt
```

Qualquer alteracao nas dependencias, basta editar o  arquivo `.in`, executar

```
pip-compile requirements-dev.in
```
e sincronizar novamente via pip-sync requirements-dev.txt
