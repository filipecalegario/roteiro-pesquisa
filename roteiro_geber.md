# Roteiro básico de uma tese

Esta é uma reprodução em Markdown de um arquivo do Word escrito por Geber Ramalho.

## Processo

1)  Escrever um \"esqueleto comentado/estendido\"

2)  Escrever a tese em 30 páginas no máximo

3)  Escrever a tese inteira

Isso dá foco e evita escrever demais. Lembre que a tese do nobel John Nash tem 21 páginas. Em um mestrado, dá para escrever algo entre 50-70 páginas e um doutorado entre 70-100. Não encha linguiça.

## O que é um \"esqueleto comentado/estendido\"?

É um texto em que constam todos os títulos de capítulos e sub-capítulos (um nível apenas de profundidade da árvore de sumário), onde para cada um deles é escrito um parágrafo explicando **o que** vai ser escrito e **por que.** Tipo \"aqui eu vou falar disto para que o leitor se convença daquilo\"

## Roteiro básico de uma tese/dissertação em "ciências do artificial"[^1]

1\) introdução (curtinha. é o trailer do filme. versão final escrita só depois de terminar tudo)

-   por que? motivação do trabalho. contexto.

-   o que? objetivo do trabalho (questão de pesquisa quando for o caso)

-   como? abordagem seguida

-   resumo do que vai rolar nas próximas seções

2\) Conceitos básicos

-   Estamos falando de que área? O trabalho afunila uma área como e porque?

-   Quais são os conceitos que o leitor precisa conhecer para ler a tese?

3\) Caracterização do problema

-   qual o problema que vai ser tratado? Por que ele é complexo? Por que ele é relevante?

-   O que se espera de uma solução para o problema? quais são os critérios de avaliação de uma solução? escalabilidade, corretude, facilidade de uso, etc.?

4\) Validação do problema (pode se fundir com o capítulo anterior)

-   Quais são as evidências de que esse problema existe de fato, de que é relvante? Se a literatura já justifica o problema, ok, senão tem de entrevistar, fazer survey, etc.

5\) estado da arte (é uma análise crítica da concorrência)

-   quais são as soluções atuais para o problema (análise de concorrentes)? Em que medida elas atendem ou não os \"critérios de avaliaçao\"?

-   no caso raro de problema/solução original, faz um estado da arte mais amplo (ex. em um sistema de gestão de risco para transporte de cargas, pode falar de gestão de risco em geral)

6\) Método de construção da solução

-   Que método vou adotar para propor uma solução? Por que vou adotar esse método? Vou me basear em quem para propor algo? Eu vou subir nos ombros de quem?

-   Não confundir com o método de validação da solução

7\) Proposta de solução

-   Descrição detalhada da solução

-   implementação (arquitetura, tecnologias, etc.)

8\) Avaliação

-   Metodologia adotada para validar -- (em alguns casos: prova de conceitos e testes de usabilidade)

-   Resultados obtidos

-   Análise: discussão dos resultados

9\) Conclusões

-   Contribuições: o que voce trouxe de novo?

-   trabalhos futuros

## Variações

-   antes do capitulo 4 \"proposta de solução\", pode haver um \"metodologia\" para incluir a explicação de como a solução foi gerada

-   Adotando uma visão MVP/prototipagem de desenvolvimento de soluções, pode haver fusão dos capítulos 4 \"proposta de solução\" e 5 \"avaliação\", em algo como \"solução, avaliação e evolução\", em que versões da solução são apresentadas, avaliadas e evoluídas em ciclos.

## Recomendações gerais

-   Na dúvida entre escrever muito ou pouco, escreva pouco, entre escrever pouco ou nada, opte por nada. Melhor adicionar depois. Se em 80 páginas você não conseguir disser o essencial, é porque ainda não entendeu o que é essencial.

-   Sugiro adotar o seguinte padrão para os textos introdutórios da cada capítulo: 1 a 2 parágrafos onde você simplesmente anuncia o que vai ser discutido no capitulo fazendo um encadeamento lógico das seções. É similar ao que você faz na introdução da tese onde você escreve um parágrafo anunciando os capítulos. Aqui você escreve um anunciando as seções.

-   Não faça um texto abstrato e só compreensível por você mesmo. Use e abuse dos exemplos concretos para deixar tudo mais claro e/ou embasar a argumentação. Exemplo é como caldo de galinha: não faz mal!!!!

-   Escreva em 1a pessoa do plural, onde nós = você e seu orientador. Nunca nós = você e o leitor. A utilização da 1a pessoa deixa mais clara quando a afirmação é nossa (e precisa ser justificada) e quando é da literatura (já está justificada). Pela mesma razão, evite coisas como \"imagine\", \"suponha\". O leitor não é seu amigo intimo.

-   Citação não pode ser objeto ou sujeito de frase. A regra básica é: eu devopoder tirara a citação e a frase ainda fazer sentido. Logo, não é bom usar \"Em \[Galstyan et al. 2003\]\" ou \"\[Galstyan et al. 2003\] disse\", por exemplo. Escreva com suas palavras o que o cara disse e coloque a citação no final da frase. Se precisar ser mais explícito, escreva \"A pesquisa de Galstyan \[Galstyan et al. 2003\] indica\...\"

-   Em um trabalho científico, \"por que\" é tão importante quanto \"o que\". Justifique suas escolhas, e não apenas descreva-as.

-   Tese não é um romance policial. Você deve revelar quem matou já na introdução, o problema tem de ficar claro desde o início e sua solução também.

-   Palavras em inglês devem estar em itálico

-   A introdução é o trailer do filme. Reescreva-a no final. O leitor tem de saber superficialmente de tudo que você fez ao ler a introdução

-   Não seja linear na ordem de escrever os capítulos!! Escreva na ordem que lhe parecer mais fácil

-   Para cada capítulo, escreva

    -   um parágrafo enxuto de introdução, que deve motivar o leitor dizendo (a) *o que ele vai ler* e (b) *porque ele vai ler*. Nada mais além disso!

    -   uma seção de conclusão resumindo o que de importante foi dito, resumindo a mensagem a ser memorizada.

## Capítulo de fundamentação teórica é uma maluquice!

Há uma tendência crescente na computação de se ter um capítulo denominado \"fundamentação teórica\", imitando as ciências humanas. Acontece que como a computação é uma \"ciência do artificial\", ela é guidada por um problema a ser resolvido. Esta \"fundamentação teórica\" vira um "saco de gatos" muito desconexo porque mistura coisas diferentes como

\- estado da arte: definições básicas

\- apresentação do problema, seus desafios, e o que se espera de uma solução

\- estado da arte concorrentes: analise dos concorrentes /similares

\- estado da arte inspirações: técnicas básicas existentes que utilizei para construir minha solução

É bom falar de tudo isto, mas não tudo misturado. Melhora fazê-lo cada um separadamente, no momento certo, dentro de uma narrativa que faça sentido.

[^1]: Do livro "The sciences of the artificial" de Herbert Simon. Enquanto as ciências naturais (física, biologia, sociologia,\...) procuram descrever o mundo, desvendando padrões na sua complexidade, as ciências do artificial (engenharias, design, economia, medicina,\...) procuram intervir no mundo construindo artefatos, processos, etc.
