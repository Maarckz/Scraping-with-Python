# Scraping-with-Python
Primeiramente você deve fazer a instalação do material necessário.

## Instalação

Se não possuir, instale o python3 e o pip.
```bash
sudo apt install python3 python3-pip
```

Use o gerenciador de pacotes [pip](https://pypi.org/project/virtualenv/) para instalar o virtualenv.
```bash
sudo pip3 install virtualenv
```

Crie uma pasta para organizar seus projetos.
```bash
mkdir -pv MeuProjeto
```

Crie um ambiente virtual (o virtualenv basicamente cria uma cópia de todos os diretórios necessários para que um programa Python seja executado).
```bash
virtualenv venv
```

Deixe seu ambiente ativo.
```bash
source [diretorio]/bin/activate
```

Por fim, instale as bibliotecas.
```bash
pip3 install selenium
pip3 install urllib3
pip3 install lxml
```


## Modo de usar (em breve)

```python
#Em breve
```

## Contribuição
Pull requests são bem-vindas. Para grandes mudanças, abra um problema primeiro para discutir o que você gostaria de mudar.

Certifique-se de atualizar os testes conforme apropriado.

## License
[MIT](https://choosealicense.com/licenses/mit/)
