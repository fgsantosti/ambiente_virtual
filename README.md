# Criando um Ambiente Virtual

Vamos criar um ambiente virtual (também chamado um virtualenv). O virtualenv isolará seu código Python/Django em um ambiente organizado por projetos. Isso significa que as alterações que você fizer em um website não afetarão os outros projetos que você estiver desenvolvendo ao mesmo tempo. Legal, né? (Ref. https://tutorial.djangogirls.org/pt/django_installation/)

Tudo o que você precisa fazer é encontrar o diretório em que você quer criar o virtualenv; seu diretório Home, por exemplo. No Windows, pode aparecer como C:\Users\Name (onde Nome é seu usuário de login).

### Instalar o Django e Configurar um Ambiente Virtual Windows

Criando ambientes virtuais para projetos Python com o Virtualenv
https://www.treinaweb.com.br/blog/criando-ambientes-virtuais-para-projetos-python-com-o-virtualenv/

### Instalar o Django e Configurar um Ambiente Virtual  Linux
#### Crie um diretório

```mkdir django-apps ```

```cd django-apps```

#### Atualizar o sistema

```sudo apt update```

```sudo apt -y upgrade```

#### Instalar o pip3

```sudo apt install python3-pip```

#### Instalar ferramentas adicionais

```sudo apt install build-essential libssl-dev libffi-dev python3-dev```

#### Instalando o env

```sudo apt install -y python3-venv```


```sudo apt install python3-virtualenv```

#### Criando seu ambiente virtual. Vamos chamá-lo de generic env

```virtualenv env```

#### Ative o ambiente virtual 

```. env/bin/activate```

#### Pode instalar as bibliotecas necessárias, como exemplo:

```pip install django```

#### Desativar o Ambiente Virtual, na pasta

```deactivate``` 

```quit()```
