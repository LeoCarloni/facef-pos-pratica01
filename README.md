# Desenvolvimento de Aplicações Web e Móveis Escaláveis - Práticas e Técnicasa de Desenvolvimento
# Atividade 01 - Exercicio 02

1- Crie um repositório chamado facef-pos-pratica01.

    •	https://github.com/LeoCarloni/facef-pos-pratica01

2- Crie uma branch chamada LOCAIS e crie os seguintes arquivos, e os preencha com conteúdos pertinentes a seus nomes (5 registros):

    o	cidade.txt
    o	pais.txt
    o	bairro.txt

    •	git clone https://github.com/LeoCarloni/facef-pos-pratica01.git
    •	git checkout -b LOCAIS
    •	git add .
  
3- Faça um commit para cada arquivo, INDIVIDUALMENTE: e faça o push para o repositório remoto (upstream).

    •	git commit -m "Commit Bairros" bairro.txt
    •	git commit -m "Commit Cidades" cidade.txt
    •	git commit -m "Commit Paises" pais.txt
    •	git push origin LOCAIS
  
4- Crie um merge-request para a master e faça o merge;

    •	git checkout -b master
    •	git merge LOCAIS
    •	git pull origin master
    
5- Crie uma branch chamada locais-b a partir da master;

    •	git checkout -b locais-b
    
6- Na branch locais-b coloque a palavra alterado na frente de cada registro, faça o commit e envie para o upstream;

    •	git add . 
    •	git commit -m "Adicionar a palavra 'Alterado'"
    •	git push origin locais-b
    
7- Crie merge request para a master;

    •	git checkout master
    •	git merge locais-b
    
8- Faça o merge da master para a branch original locais

    •	git checkout LOCAIS
    •	git merge master

9-	Para cada arquivo criado, edite o conteúdo do mesmo alterando o texto já inserido e inclua mais 2 linhas de texto - faça com que as alterações cheguem ao repositório remoto (github);

    •	git add . 
    •	git commit -m "Alterando os registros"
    •	git push origin LOCAIS

10-	Exclua o arquivo pais.txt e faça com que o mesmo se propague ao repositório remoto (add, commit e push) - valide se o arquivo foi removido do github;

    •	git add . 
    •	git commit -m "Excluir arquivo pais.txt"
    •	git push origin LOCAIS

11-	Inclua um arquivo de imagem no diretório do git em sua máquina, commit e envie-o para o github.

    •	git add . 
    •	git commit -m "Adicionar imagem"
    •	git push origin LOCAIS
