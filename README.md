# LH_CD_RODRIGOPRATES

Repositório criado com o intuito de resolver o desafio de Ciência de dados, proposto pela empresa Indicium, no processo seletivo do programa Lighthouse.

Abaixo segue um passo a passo para a instalação dos requisitos necessários e execução do projeto.

## Requisitos base

Este projeto foi todo desenvolvido utilizando o VS CODE. Portanto, se torna necessário a instalação deste ou de algum outro interpretador de código para o seu correto funcionamento. Em seguida, foram instaladas as extensões do Python e Jupyter Notebook, além do Anaconda para executar alguns comandos no terminal.

## Criando um ambiente virtual Python

Feita as instalações acima listadas, agora pode-se criar um ambiente virtual python para a execução dos códigos deste repositório. Isto pode ser feita executando os comandos abaixo no terminal do VS CODE.

```bash
conda create -n lh python=3.8
conda activate lh
```

OBS: o nome 'lh' do ambiente foi escolhido ao acaso. Pode-se dar qualquer nome que seja mais conveniente.

## Instalação das bibliotecas

Com o ambiente virtual 'lh' criado e ativado, agora é necessário instalar as bibliotecas, listadas no arquivo 'requirements.txt', que foram utilizadas no desenvolvimento do projeto. Para isso, executa-se, ainda no terminal, o comando abaixo.

```bash
pip install -r requirements.txt
```

Instaladas tais bibliotecas dentro do ambiente, agora pode-se rodar as linhas de código presentes nos arquivos 'EDA.ipynb' e 'Modelling.ipynb' utilizando este ambiente criado.