# Elaboração de Dissertações e Teses em LaTeX

Este template foi elaborado para facilitar a elaboração de Teses e Dissertações de acordo com as normas de trabalhos acadêmicos da ABNT.
O objetivo desse template é proporcionar um design limpo, sem distrações, onde todo o foco pode ser colocado diretamente no conteúdo. O autor precisa dominar apenas alguns conceitos básicos sobre a sintaxe do Latex.

Demontração
============

A presente demonstração apresenta o básico da utilização desse template. Recomenda-se uma leitura atenciosa deste documento antes de seu uso. O uso do LATEX é relativamente complexa para inciantes e requer alguma prática. Caso você não esteja familiarizado com a ferramenta, não é uma boa ideia aprender a usa-lo próximo do final do prazo para entrega da dissertação/tese. Entretanto, se você já tem alguma familiaridade com a ferramenta, poderá observar a adequação de qualquer texto já escrito ao formato desse template é muito simples.

Uma demonstração completa está disponível. Busque por `main.tex` e `main.pdf`.

Pré-requisitos
============
Ao utilizar este template assume-se que o leitor já esteja familiarizado com o uso do Latex. Isto inclui:
* Saber instalar o LATEX e seus pacotes no seu sistema operacional, seja ele Windows ou Linux
* Conseguir compilar um arquivo .tex de forma apropriada
* Entender o que é arquivo BibTex e como inserir referências nele
* Interpretar as inevitáveis mensagens de erro que surgem no momento da compilação
* Saber como indicar no arquivo na localização de figuras, arquivos a inserir, etc

Estrutura de Arquivos
============

O template inclui arquivos distribuídos em vários diretórios. São eles:

1. ./anexos: local para armazenar os anexos que serão inseridos no texto
1. ./apendices: local para armazenar os apêndices que serão inseridos no texto


2. ./referencias: diretório que contém o arquivo BibTex com as referências
bibliograficas
3. ./template: diretório que contém o arquivo Template_Tese.sty. Este é o
arquivo com as configurações de formato seguindo as normas da ESALQ.


4. ./prefiles: contém os arquivos para redação da parte pré-textual como: capa, resumo, agradecimentos, listas, etc.
5. ./capX: Pastas que contém os capítulos do texto como: Introdução, Metodologia, Resultados, etc.
    - ./figs: Pasta criada dentro de cada pasta de capítulo com o intuito de armazenar as figuras que serão inseridas no texto
6. ./pos-textual: para anexos e apêndices
7. ./: diretório raiz, com os arquivos `main.tex` (arquivo principal a ser compilado), Tese.pdf (o resultado da compilação) e Makefile (conjunto de
instruções para compilação, para o ambiente Linux).
Navegue nos diretórios para se familiarizar com seu conteúdo, mas não altere os
arquivos antes de terminar a leitura do tutorial.



<!--Compilando o documento
O principal arquivo, que está no diretório raiz, é chamado Tese.tex. Abra-o. Seu
conteúdo é auto-explicativo. Este é o arquivo que deverá ser compilado. Não altere
suas configurações, exceto onde explicitamente indicado.
O template faz uso da classe memoir1, que apresenta diversas facilidades para

obtenção de documentos em capítulos, como é o caso das Dissertações e Te-
ses. Além disso, ele importa diversas configurações específicas do arquivo Tem-
plate_Tese.sty (arquivo que deve ser alterado apenas em pontos específicos).
Em seguida, são inseridos vários arquivos com configuracões e conteúdo. Muitos
deles apresentam pequenos trechos de textos fictícios para exemplificar como o
texto deve ser digitado.

Será produzido um arquivo Tese.pdf-->



Download
========
Faça o download da versão mais recente através [deste link](https://github.com/gusirosx/TexTemplate/releases).

Licença
=======
Seu software é lançado sob a licença [GNU GPL v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).

Contribuidores
============
Esse tema foi baseado em diversas compilações da [comunidade LaTeX](https://latex.org/forum/). A presente versão, foi compilada por [Gustavo Rodrigues](https://github.com/gusirosx).
