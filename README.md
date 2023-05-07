# Instalação do Python 3.8 no Ubuntu 18.04
## Este guia fornece instruções passo a passo para instalar o Python 3.8 em um sistema operacional Ubuntu 18.04 e executar um aplicativo Python de amostra.

## Pré-requisitos
## Antes de começar, você precisará ter acesso de superusuário em seu sistema.

# Instruções
# Adicionar o repositório deadsnakes/ppa
## Abra o terminal e execute o seguinte comando para adicionar o repositório deadsnakes/ppa:
sudo add-apt-repository ppa:deadsnakes/ppa
# Instalar o Python 3.8 e o ambiente virtual Python 3.8
## Instale o Python 3.8 e o ambiente virtual Python 3.8 usando o seguinte comando:

sudo apt install python3.8 python3.8-venv
# Criar um ambiente virtual Python
## Crie um ambiente virtual Python 3.8 executando o seguinte comando:

python3.8 -m venv venv 
## Ativar o ambiente virtual

# Ative o ambiente virtual Python executando o seguinte comando:

source ./venv/bin/activate
# Instalar as dependências do projeto
## Instale as dependências do projeto executando o seguinte comando:

pip install -r requirements.txt
# Executar o aplicativo Python
## Execute o aplicativo Python usando o seguinte comando:
python app.py
# Conclusão
## Agora que você tem o Python 3.8 instalado em seu sistema Ubuntu 18.04 e um ambiente virtual Python configurado, você pode continuar com o desenvolvimento do seu projeto Python.
