# Manual do Usuário - GitHub

Olá! Bem-vindo ao Manual do Usuário para aprender a subir seus diretórios para o seu repositório no GitHub. Este manual foi criado para fornecer instruções claras e detalhadas, especialmente para iniciantes no mundo da programação. Siga os passos abaixo para entender como realizar esse processo. Espero que aproveite e que o manual auxilie em sua jornada.


# Guia para Subir Alterações para o GitHub

Se você ainda não configurou seu nome de usuário e e-mail no Git, pode fazê-lo utilizando os comandos a seguir.

## Configuração inicial (apenas se necessário)
`git config --global user.name "Seu Nome"`

`git config --global user.email "seuemail@example.com"`

## Clonar o repositório remoto (se ainda não tiver feito)

Caso ainda não tenha clonado o repositório para o seu computador, você pode fazer isso usando o comando `git clone` seguido do URL do repositório no GitHub.

`git clone https://github.com/seu_usuario/seu_repositorio.git`

## Navegar até o diretório do projeto

Use o comando `cd` para navegar até o diretório do projeto clonado.

cd seu_repositorio

## Verificar o status do repositório

Antes de fazer alterações, é uma boa prática verificar o status do repositório para saber quais arquivos foram modificados, adicionados ou excluídos.

Utilize o comando: `git status`para analisar se há modificações em seus arquivos.


## Fazer as alterações necessárias

Faça as alterações nos arquivos do projeto usando um editor de texto ou IDE.



## Adicionar as alterações ao índice

Adicione as alterações ao índice do Git usando o comando `git add`. Se desejar adicionar todas as alterações, você pode usar `git add .` para adicionar todos os arquivos modificados, novos e excluídos. OBS: Repare que um espaço entre `add` e o `.`

## Fazer o commit das alterações

Faça um commit das alterações adicionadas ao índice com uma mensagem descritiva usando o comando `git commit`.

`git  commit  -m  "Descrição das alterações"`

Por exemplo `git commit -m "Efetuado alteração no arquivo de teste para commitar".
`
## Fazer o push das alterações para o repositório remoto

Finalmente, faça o push das alterações para o repositório remoto no GitHub usando o comando `git push`. Se você está na branch `main`, o comando será:

`git push origin main`

Após executar esses passos, suas alterações serão enviadas para o repositório remoto no GitHub. Certifique-se de substituir `seu_usuario` e `seu_repositorio` pelo seu nome de usuário e nome do repositório, respectivamente.

