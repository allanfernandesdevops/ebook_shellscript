[TOC]



# e-book Arena Shell

![](C:\Users\ferna\Documents\Arena Linux\ebook\Capa ebook.png)

Todos os scripts estão disponíveis em: https://github.com/gitarena/arenashell 

Em caso de dúvidas, os meus canais de contato são: 

💡 instagram.com/fernandesallan 
⚔ allanfernandes.com.br 
📧 [contato@allanfernandes.com.br](mailto:contato@allanfernandes.com.br) 



## Introdução

**“Eu escolho uma pessoa preguiçosa para fazer um trabalho duro. Porque uma pessoa preguiçosa irá encontrar uma forma fácil de o fazer.”**  - Bill Gates 

Gosto muito dessa frase do Gates, só faria uma leve modificação para uma pessoa preguiçosa irá encontrar uma forma fácil de automatizar esse trabalho. Kkk. Brincadeiras a parte, entenda, você não está aqui para ser um robô de repetição. Quantas vezes você precisa fazer o backup? Quantos comandos você precisa para realizar a instalação de um programa? Quantas vezes você realiza a mesma configuração para os equipamentos da sua empresa? Se você respondeu várias para alguma dessas perguntas, então você está perdendo o benefício da automatização. 

Você precisa evoluir, assim como acontece com tudo na vida, você precisa tornar as coisas mais fáceis e precisa entender que quem faz isso se destaca no mercado. 

Esse ebook vai mostrar a você tudo que é necessário para aprender a automatizar a sua rotina através de scripts shell e assim aumentar a sua produtividade e tendo possibilidade de criar soluções e com isso levar a sua carreira a um próximo nível. 

Apesar de ser um ebook, o conhecimento aqui é voltado para a prática, então você verá muitos scripts, muitos mesmo, creio que mais de xxxxxx, você vai aprender a criar um script desde o zero que serão úteis para qualquer administrador de sistemas ou analista de sistemas Linux. 

O ebook está divido em seções, e irei abordar:

- **Revisão de comandos no Linux**: Vamos rever os comandos mais usados no terminal Linux e que serão usados para fazer os scripts no dia a dia, variáveis do shell, redicionamentos, pipes, entrada e saída. 
- **Instruções condicionais e loop:** Aqui vamos ver como fazer uma instrução se determinada condição for satisfeita ou não e aprender como repetir a tarefa até quando for necessário.
- **Funções:** Nesse item vamos aprender como usar o mesmo código em várias partes sem precisar ficar copiando e colando. O nome disso é função!
- **Logs:** Aqui vamos aprender a como criar logs para os nossos scripts.
- **“Debugando” o script:** Nesse último módulo vamos aprender a corrigir os erros caso apareçam em nossos scripts.

Para quem é esse ebook? 

\- Profissionais de TI 
\- Usuários de sistemas Linux e Unix 
\- Alunos da área de TI 
\- Curiosos 

### O que é um Shell e o shell script?

O shell é uma interface entre o usuário e o Linux, onde o usuário executa os comandos, seja para acessar os arquivos, ter informações de *CPU*, memória, etc.

Resumidamente é um programa de computador que roda embaixo do shell unix que é basicamente um interpretador de comandos. Além da execução de comandos, o script permite a interação com o usuário, o uso de variáveis, uso de condicionais, loop e muito mais. 

Como funciona de forma prática? Vamos imaginar que você precisa fazer o backup de uma determinada pasta todo dia a meia noite. Já imaginou você ter que ficar acordado até essa hora para copiar a pasta, compactar a pasta e armazenar esse conteúdo em algum lugar? O script basicamente faz isso tudo. Basta agendar ele na cron e “montar” o seu passo a passo para a geração do backup. Como fazer isso? Você vai aprender aqui nesse ebook. 

 #### Tipos de shell

**sh**: Shell original e padrão do Unix.

**bash**: Shell padrão do Linux, compatível com o sh, mas com muitas melhorias.

**ksh**: 