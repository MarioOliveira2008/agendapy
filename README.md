 # Agenda em python usando flask

 Este projeto foi elaborado para permitir o aprendizado de conceitos como
 padrão de projeto MVC (Model-View-Controller), famework Flask e seus
 componentes, variaveis de ambiente, paradigma de programação orientado a
 objetos e reforço de fundamentos da linguagem de programação Python.

 Para implementar este projeto localmente, siga os seguintes passos:

 1. Faça um fork deste repositorio, clicando no botão `Fork`
 
 2. Clone este repositorio localmente:

 ~~~bash
 git clone <url_seu_repositorio>
 ~~~

 3. Abra o projeto utilizando seu IDE preferido

 4. Crie preferencialmente, um ambiente virtual utilizando uma versão do 
 Python 3.12.10+

~~~bash
python -m venv .venv
~~~

5. Ative seu ambiente virtual.

    No bash:

    ~~~bash
    source .venv/Sripts/activate
    ~~~

    No powershell:

    ~~~powershell
    .\.venv\Scripts\Activate.ps1
    ~~~

6. Instale todas as dependências constantes no `requeriments.txt`:

    ~~~python
    pip install -r requeriments.txt
    ~~~

7. Copie o arquivo `.env.example`, cole na raiz do projeto e renomeie essa 
copia para `.env`.

8.  Edite o arquivo `.env` para definir o caminho do seu banco de dados na
    constante `DATABASE`. Exemplo:

    ~~~env
    DATABASE='./data/meubanco.db'
    ~~~

9. Rode a aplicação no Python utilizando o comando:

~~~bash
flask run
~~~

10. Acesse a aplicação no endereço e porta indicados no terminal. Exemplo:
`http://127.0.0.1:5000`


