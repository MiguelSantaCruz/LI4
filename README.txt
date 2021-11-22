No ficheiro cover.tex estão definidos campos para serem modificados de acordo com constituição de cada equipa e do tema do projeto em questão.

EXEMPLO 1: Mudar o título do projeto na capa

No preâmbulo desse ficheiro é possível ver:

\title{$\mathbf{<<}$Título do Trabalho$\mathbf{>>}$}

Se p.e., o título do nosso trabalho for "Titulo", então pode-se escrever assim: 


\title{Titulo}

Após compilação, o relatório gerado ficará com o título desejado.

EXEMPLO 2: Mudar os autores do projeto

Analogamente, podemos mudar os autores do projeto. No preâmbulo é possível ver:

\author{
    Author$($1$)$
  \quad
    Author$($2$)$
  \quad
    Author$($3$)$
  \quad
    Author$($4$)$
}

Se p.e., os autores do nosso trabalho forem a Ana, o João e a Mariana, então pode-se escrever assim: 

\author{
    Ana
  \quad
    João
  \quad
    Mariana
}

Se ainda quisermos adicionar o número dos alunos, podemos fazer: 

\author{
    Ana aXXXXX
  \quad
    João aYYYYY
  \quad
    Mariana aZZZZZ
}

INFORMAÇÕES ADICIONAIS:

    As secções/capítulos que estão definidas no main.tex são necessárias para a elaboração completa do relatório. Convém não se retirar nenhuma, estando estas devidamente separadas para facilitar a leitura do código e estruturação do trabalho.

    Na pasta imagens tem o logotipo da universidade que convém não ser eliminado para que a capa do projeto seja bem produzida.

    Por último e MUITO IMPORTANTE, dado que se utiliza o package "fontspec" para carregar a font arial, não é possível compilar os ficheiros com pdflatex. Poderá se usar xelatex, lualatex ou outros que consigam carregar o package. 
    No overleaf é possível mudar o compilador padrão: 
    https://www.overleaf.com/learn/how-to/Changing_compiler