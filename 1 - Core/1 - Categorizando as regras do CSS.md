**Categorizando as regras do CSS**

Todo projeto precisa de alguma organização. Acrescentar cada estilo novo que você cria ao final de um arquivo único vai tornar bem difícil de encontrar coisas e será bem confuso para qualquer pessoa trabalhando no projeto. É claro que você já deve ter algum tipo de organização. Eu espero que o que você irá ler nessas páginas irá destacar o que já funciona com o seu projeto, e se eu tiver sorte você irá aprender novas maneiras de melhorar o seu processo.

Como você decide se vai usar IDs, classes ou qualquer outro seletor que você tem à disposição? Como você decide quais elementos devem receber o estilo que você irá criar? Como você faz para facilitar a compreensão de como o seu site e seu CSS está organizado?

O ponto central do SMACSS é a categorização. Ao categorizar as regras do CSS, nós começamos a perceber padrões e definir boas práticas para cada um desses padrões.

Há cinco tipos de categorias:
1. Base
2. Layout
3. Modulo
4. Estado
5. Tema

Nós muitas vezes misturamos os estilos de cada uma dessas categorias. Se estivermos mais cientes de 'o quê' iremos estilizar, poderemos evitar a complexidade que se cria ao entrelaçar essa regras. 

Para cada categoria existem algumas orientações que devem ser aplicadas. Essas separações, de certa forma sucintas, nos permitem fazer alguns questionamentos durante o processo de desenvolvimento. Como iremos codar determinada coisa e porquê iremos codá-la desse jeito?

Uma boa parte do propósito de categorizar as coisas é identificar padrões que se repetem no nosso design. Repetição resulta em menos código, manutenção mais fácil, e maior consistência na experiência do usuário. Você só tem a ganhar. Algumas exceções à regra até podem trazer vantagem mas devem ser justificadas.

**Regras de base** são os padrões. Elas são quase que exclusivamente seletores de elementos únicos mas podem incluir seletores de atributo, pseudo-seletores, child-selectors ou sibling selectors. Essencialmente, o que um estilo de base quer dizer é que não importa onde esse elemento apareça ele irá parecer da mesma forma.

<img src="images/Base.PNG">

**Regras de layout** dividem a página em seções. Um Layout engloba um ou mais módulos.

**Módulos** são as partes reutilizáveis e modulares do seu design. São as seções de links, a barra lateral, a lista de produtos e assim por diante.

**Regras de estado** são maneiras de descrever como os seus módulos ou layouts irão parecer em um determinado estado. O item está escondido ou expandido? Está ativo ou inativo? Regras de estado descrevem como o seu módulo irá parecer em telas pequenas ou grandes. Elas também são formas de descrever como o seu módulo irá parecer em views diferentes como a Home ou uma página interna.