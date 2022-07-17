## Posicionando elementos com Flexbox em CSS

Criação de layout responsivo, sem a necessidade de setar cada um dos valores 

### 1. Introdução ao Flexbox

- Estrutura básica
  - É composta por containers e filhos 
  
  - Container serve para você guardar algo dentro. É o elemento inicial
  
  - Dentro desse container, você pode guardar filhos 
  
  - Os filhos são qualquer coisa dentro do container 
  
    

### 2. Fundamentos do Flexbox

- Display Flex

  

- Flex-direction

  - Horizontal:

    1. Row (padrão): da esquerda para a direita
    2. Row-reverse: é o oposto do anterior

  - Vertical:

    1. Column: ordenado de cima pra baixo

    2. Column-reverse: é o oposto do anterior

       

- Flex-wrap

  - define se os itens devem ou não quebrar as linhas

    - nowrap: padrão, não permite a quebra de linha 

    - wrap: permite a quebra de linha assim que o item não couber no container, jogando o item para a linha abaixo

    - wrap-reverse: permite a quebra de linha, mas no sentido contrário, ou seja, joga o item para a linha acima

      

- Flex-flow

  - é um atalho para flex-direction e flex-wrap

    

- Estrutura básica do justify content

  - alinha os itens dentro do container de acordo com a direção pretendida
  - Variações:
    1. flex-start: início do container
    2. flex-end: final do container
    3. center: centro do container
    4. Space-between:espaçamento igual entre os elementos
    5. Space-around:espaçamentos do meio são maiores do que o inicial e o final 

  

- Align-itens

  - alinhamento dos flex itens de acordo com o eixo do container

  - permite o alinhamento central no eixo vertical 
  
  - Tipos:
    1. center
    
    2. stretch: padrão
    
    3. flex-start: alinhamento no início
    
    4. flex-end: alinhamento no final 
    
    5. baseline: alinhamento de acordo com a linha base da tipografia dos itens
    
       

- Align-content
  - faz o tratamento do eixo vertical.
  - trabalha as linhas do container
  - faz a quebra de linhas
  - Tipos:
    - center
    - stretch: é o padrão e os flex itens crescem igualmente
    - flex-start: alinhamento dos itens no início
    - flex-end: alinhamento no final
    - space-between: cria um espaço igual entre os elementos
    - space-around: espaços do meio são duas vezes maiores que o inicial e o final 





