IMPORTANTE:
No arquivo loginwindow.cpp na linha 14, altere o caminho do arquivo
do banco de dados para o caminho correto na sua m�quina, por exemplo,
"C:/Correcoes/ProjetoSIN143Qt/db_sorveteria.db". N�o utilizar barras
invertidas: "C:\...\...\".

Baixamos a IDE atrav�s do link https://www.qt.io/download vers�o Open Source.

O pacote para compila��o e execu��o utilizado foi o
Desktop Qt 5.12.3 MinGW 64-bit, sendo executado no modo debug.

Para abrir o projeto, basta abrir o arquivo ProjetoSIN143Qt.pro.

Para rod�-lo, lembre-se de escolher o pacote citado. Basta clicar
em run.

------------
UTILIZA��O:
O login e a senha foram previamente preenchidos para teste, sendo
poss�vel acessar o sistema atrav�s dos logins:

username: userjoao
password: 123123

username: atendente
password: 123123

O segundo usu�rio n�o possui acesso aos CRUDs do sistema.

Ap�s o login ser feito, a tela principal do caixa ser� aberta.
Para gerenciar um pedido, coloque o c�digo do produto e a quantidade.
Para que o produto+quantidade sejam adicionados ao pedido, tecle ENTER.
Os c�digos dispon�veis para teste s�o de 1 at� 10.
Para come�ar um novo pedido, o valor total recebido deve ser maior
ou igual ao subtotal do pedido.
As op��es de crud est�o em uma barra de menus.
O restante � bem simples.

------------

COMENT�RIOS:
Caso queira verificar se o programa realmente est� se comunicando
com um banco de dados, instale o SQLiteStudio atrav�s do link

https://sqlitestudio.pl/index.rvt?act=download

Tentamos criar uma aplica��o pra rodar sem precisar da IDE,
at� conseguimos, por�m a aplica��o n�o consegue se comunicar
com o banco de dados corretamente. Acreditamos ser um bug da
pr�pria vers�o da IDE.

Estamos utilizando o Qt Creator 4.9.1 que � baseado no Qt 5.12.3
com �ltima atualiza��o no dia 26 de maio de 2019.






