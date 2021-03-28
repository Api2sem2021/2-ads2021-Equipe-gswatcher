A nossa solu��o unifica e trata os dados utilizando o node.js, e importa esses dados no SGDB Postegresql para que posteriomente possamos integrar esse banco ao nosso dashboard.


PREPARANDO A M�QUINA:
Para conseguir rodar a solu��o � necess�rio possuir o NODE.JS e o POSTEGRESQL intalados em sua m�quina.

Baixe os arquivos contidos nesse diret�rio

Instale os m�dulos necess�rios:
atrav�s do prompt de comando v� at� a pasta em que os arquivos baixados est�o salvos e digite:
npm install express
npm install pg 


Criar um usu�rio e banco de dados no Postegresql que ser� aplicado no projeto:
atrav�s do shell do postgresql, digite os seguinte comando.

Para criar um usu�rio "me" com a senha "password"
postgres=# CREATE ROLE me WITH LOGIN PASSWORD 'password';

Alterar as permi��es desse usu�rio para conseguir criar um database.
postgres=# ALTER ROLE me CREATEDB;

Ent�o conecte-se ao usu�rio criado e crie o database atrav�s do comando:
CREATE DATABASE api;

Por fim, para se conectar a esse database criado, utilize o comando:
\c


CRIANDO AS TABELAS NO BANCO DE DADOS:
V� at� a pasta em que salvou os arquivos deste diret�rio pelo prompt de comandos e rode o arquivo: 01_app.js, atrav�s do seguinte comando no prompt:
node 01_app.js


POPULANDO AS TABELAS NO POSTEGRESQL:
Nesta mesma pasta do prompt de comandos rode o comando:
node 02_app.js


EXPORTANDO ARQUIVOS *.csv do POSTEGRESQL:

Inicialemnet deve-se criar os arquivos tbl_dev.csv tbl_projeto.csv, tbl_sistema.csv, tbl_git.csv, tbl_status.csv, tbl_task.csv, tbl_task_detalhes.csv no caminho "C:/temp/"

Ent�o executar os seguinte comandos no psql:

\COPY ( SELECT * FROM tbl_dev)  to 'C:/temp/tbl_dev.csv'  WITH DELIMITER AS ';' CSV HEADER

\COPY ( SELECT * FROM tbl_projeto)  to 'C:/temp/tbl_projeto.csv'  WITH DELIMITER AS ';' CSV HEADER

\COPY ( SELECT * FROM tbl_sistema)  to 'C:/temp/tbl_sistema.csv'  WITH DELIMITER AS ';' CSV HEADER

\COPY ( SELECT * FROM tbl_git)  to 'C:/temp/tbl_git.csv'  WITH DELIMITER AS ';' CSV HEADER

\COPY ( SELECT * FROM tbl_status)  to 'C:/temp/tbl_status.csv'  WITH DELIMITER AS ';' CSV HEADER

\COPY ( SELECT * FROM tbl_task)  to 'C:/temp/tbl_task.csv'  WITH DELIMITER AS ';' CSV HEADER

\COPY ( SELECT * FROM tbl_task_detalhes)  to 'C:/temp/tbl_task_detalhes.csv'  WITH DELIMITER AS ';' CSV HEADER


Os arquivos podem ser salvos em outro caminho desde que o camando \copy seja alterado para esse mesmo caminho tamb�m.

Esses arquivos salvos est�o dentro da pasta "CSV export".



Na nossa modelagem de dados te�rica foram dimensionadas e relacionadas tamb�m tabelas de recarga de dados e de usu�rios, que ainda n�o foram implementadas, pois em um primeiro momento, com apenas dois arquivos para a recarga dos dados n�o seria interessante, mas com a evolu��o do projeto e alimenta��o de mais dados a equipe ir� implementar tamb�m essas tabelas no banco de dados, bem como otimizar o c�digo utilizado nas tabelas j� existentes. 


