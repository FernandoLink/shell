---------------------------------------------------------------------------------------------------------------------------------
SISTEMA                                                                         
---------------------------------------------------------------------------------------------------------------------------------
logout           -> encerra de uma vez a sessão do usuário;                     
<ctrl>+d         -> também funciona como logout mas nem sempre está habilitado; 
exit             -> encerra somente o shell corrente;                           
---------------------------------------------------------------------------------------------------------------------------------
ARQUIVOS E DIRETÓRIOS
---------------------------------------------------------------------------------------------------------------------------------
pwd              -> exibe o nome do diretório corrente;
cd               -> navegando entre diretórios;
ls               -> listar arquivos;
cp               -> cópia de arquivos;
mv               -> move arquivos e diretórios;
ln               -> estabelece ligação entre arquivos;
mkdir            -> cria um diretório;
rmdir            -> remove um diretório vazio;
rm               -> apaga arquivos e diretórios;
file             -> indicando tipo de arquivo;
grep             -> procura arquivos por conteúdo;
find             -> localiza arquivo por suas características;
basename         -> devolve o nome de um arquivo recebendo o caminho completo;
dirname          -> devolve o nome do diretório recebendo o caminho completo;
dir              -> lista o contéudo do diretório;
. (ponto)        -> diretório atual;
.. (dois pontos) -> diretório anterior;
~ (til)          -> diretório home do usuário;
/ (barra)        -> direório raiz;
- (hífen)        -> último diretório;
---------------------------------------------------------------------------------------------------------------------------------
HELP
---------------------------------------------------------------------------------------------------------------------------------
<command> --help    -> mostra a ajuda do comando;
help                -> mostra informações gerais sobre os built-ins do shell;
man <command>       -> mais completa documentação do Linux;
	h           -> mostra a ajuda do man;
apropos or man -k   -> mostra informações sobre um tópico;
whatis              -> obtém uma breve descrição de um comando do sistema;
<command> --version -> mostra a versão do comando;
<command> --usage   -> ajuda curta do comando (não são todos os comandos); 
---------------------------------------------------------------------------------------------------------------------------------
FILTROS
---------------------------------------------------------------------------------------------------------------------------------
cat   -> exibe conteúdo de arquivos;
wc    -> caont caracteres, palavras e/ou linhas de arquivos;
sort  -> ordena o conteúdo de arquivos;
head  -> exibe o início dos arquivos;
tail  -> exibe o final dos arquivos;
---------------------------------------------------------------------------------------------------------------------------------
SEGURANÇA
---------------------------------------------------------------------------------------------------------------------------------
passwd    -> altera a senha do usuário;                                  |
chown     -> troca o dono do arquivo;
chgrp     -> troca o grupo do arquivo;
dono(u)   -> o usuário dono do grupo;
group(g)  -> o grupo a que pertence o arquivo;
outros(o) -> outros usuários que não sejam o dono e nem pertençam ao grupo dono do arquivo;
---------------------------------------------------------------------------------------------------------------------------------
USUÁRIOS
---------------------------------------------------------------------------------------------------------------------------------
who    -> exibe informações sobre usuários ativos e alguns dados do sistema;
id     -> informa os identificadores dos usuários;
finger -> exibe informações mais detalhadas sobre os usuários;
chfn   -> permite que o usuário altere as suas informações do finger;
groups -> informa os grupos aos quais o usuário pertence;
---------------------------------------------------------------------------------------------------------------------------------
DATA E HORA
---------------------------------------------------------------------------------------------------------------------------------
date -> mostra e acerta data/hora;
cal  -> exibe o calendário;
---------------------------------------------------------------------------------------------------------------------------------
BACKUP
---------------------------------------------------------------------------------------------------------------------------------
tar        -> para agrupar vários arquivos em somente um;
compress   -> é o utilitário de compressão de arquivos padrão do unix;
uncompress -> descomprime arquivos compactados pelo compress;
zcat       -> permite visualizar o contéudo de arquivos compactados com compressos;
gzip       -> é o utilitário de compressão de arquivos padrão do linux;
gunzip     -> descomprime arquivos compactado pelo gzip;
---------------------------------------------------------------------------------------------------------------------------------
CONTROLE DE EXECUÇÃO
---------------------------------------------------------------------------------------------------------------------------------
ps    -> mostra status dos processos em execução;
kill  -> envia sinal a processo;
jobs  -> lista processos em background e suspensos;
bg    -> passa processo para background;
fg    -> traz processo para foreground;
Nohup -> executa processo independente de terminal; TODO: ???
---------------------------------------------------------------------------------------------------------------------------------
AGENDAR TAREFAS
---------------------------------------------------------------------------------------------------------------------------------
crontab -> programa para instalar, desinstalar ou listar as tabelas usadas pelo programa (daemon) cron; TODO: ???
cron    -> agendar a execução de tarefas administrativas; TODO: ???
at      -> este comando permite que se programem datas e horas para execução de tarefas; TODO: ???
batch   -> executar tarefas pesadas em segundo plano (background); TODO: ???

TODO: transformar em markdown
