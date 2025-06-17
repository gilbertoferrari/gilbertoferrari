• GIT CLONE URL -> Clona um código já existente;

• MKRDIR -> Cria um diretório;

• CD "NOME DA PASTA" -> Entra na pasta;

• CD .. ->  Retorna um nível na pasta;

• GIT INIT -> Cria repositório local;

• CAT CONFIG -> Ver as configurações do repositório;

• GIT REMOTE ADD ORIGIN URL -> Adiciona repositório local ao remoto;

• CD .GET -> Entra na pasta e mostra o arquivo GIT;

• GIT STATUS ->  Vê o status da nossa área de preparação ou árvore de preparação;

• TOUCH READ.ME -> Cria o arquivo Read.me;

• GIT ADD . -> Insere todos os arquivos da pasta no commit;

• GIT ADD "NOME DO ARQUIVO" -> Insere o documento especificado no commit;

• GIT COMMIT -M "mensagem para subir no commit" -> Insere a mensagem no commit;

• GIT LOG ->  Mostra o status do commit;

• RM -RF .GIT -> Sai do projeto caso iniciarmos o init na pasta incorreta;

• GIT RESTORE "NOME DO ARQUIVO" -> Restaura o último estado do arquivo;

• GIT COMMIT --AMEND -> Edita a mensagem do último commit;

• GIT RESET --* + CÓDIGO DO COMMIT (OBTIDO NO GIT LOG) -> Restaura estado do commit

    • SOFT -> Pega os arquivos que estavam posteriores ao último commit informado;

    • MIXED (vem por padrão) -> Adiciona os arquivos na árvore de trabalho como untracked files;

    • HARD - Ignora os arquivos contidos na último commit (apaga os arquivos que estavam na pasta, restaura para o estado anterior)

• GIT REFLOG -> Mostra o status detalhado dos commits;

• GIT RM "NOME DO ARQUIVO" -> Exclui um arquivo da pasta;

• GIT RM -R "NOME DA PASTA -> Exclui uma pasta inteira

• GIT PUSH -U ORIGIN MAIN -> Faz o upload do diretório do local fisico para o remoto

• GIT PULL -> Puxa as alterações feitas online para o reposositorio local mesclando as alteracoes;
