![Badge Concluido](http://img.shields.io/static/v1?label=STATUS&message=%20CONCLUIDO&color=GREEN&style=for-the-badge)
# :page_with_curl:  Organizador de arquivos
O módulo **os** fornece diversas funções e métodos para interagir com o Sistema Operacional.
Ele é usado para manipular arquivos e pastas.
Como ele é nativo do Python não é necessário instalar, é só importar
````python
Import os
````
:movie_camera:

<img src=".\Animação01.gif" alt="Código funcionando" width="600px" heidth="400px">

:film_strip:

<img src=".\Animação02.gif" alt="Código 2 funcionando" width="600px" heidth="400px">

Utilizando o método **getcwd()** podemos verificar em qual diretório estamos trabalhando.
````python
os.getcwd()
````

Com o método **listdir()** podemos listar os arquivos existentes no diretório.
````python
os.listdir()
````

O método **chdir()** muda para o diretório no qual vai ser usado o código da organização de arquivos.
````python
os.chdir(“C:\\Users\\nome\\Downloads”)
````

Para mapear os arquivos e identificar suas extensões, usaremos o método de string **split()**.
O método **split()** separa a strig por um parâmetro que for passado. Como nos arquivos o delimitador é **“.”** usamos o seguinte código:
````python
Texto.txt.split(“.”)
````

A função **SET** transforma a lista em um conjunto. Conjunto é uma lista de dados onde seus elementos são desordenados. Ou seja, não tem índice.
````python
set(tipo.spit())
````

Com o método **mkdir()** vamos criar pastas para que cada tipo de arquivo seja armazenado na pasta referente à sua extensão
````python
os.mkdir()
````


## 📁 Como utilizar o código:
O arquivo **organizador.py** pode ser usado em um terminal
````python
Python organizador.py
````

## 	:bookmark_tabs: Arquivo Requirements:
É um arquivo de texto formato **.txt**. Neste arquivo está especificado todos os pacotes e bibliotecas que são utilizados no projeto; isso ajuda como garantia que, se o projeto for usado por outro desenvolvedor, não ocorram erros ou problemas causados por alguma atualização na versão do pacote ou descontinuidade na linguagem Python.

Para instalar, entre no terminal **Ctrl + ‘** e instale o requirements para usar todos os pacotes na mesma versão que foi utilizada no projeto. 

````python
pip install -r requirements.txt
````
:film_projector:

<img src=".\Animação03.gif" alt="Código 2 funcionando" width="600px" heidth="400px">

## :computer: Técnicas e Tecnologias utilizadas:
- Método **os**
- Lista Comprehensions
- Tratamento de erros
-  Estrutura condicional if  
    
    - **Python**
   - **Jupter Notebook**
