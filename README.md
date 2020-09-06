# Bônus do Bootcamp GoStack

## Divido em três partes:  

**Conceito** - Onde é abordada a arquitetura flux. O estado (state) da aplicação é centralizado em uma loja (store) onde, a cada ação é criado um histórico. Sendo assim, o estado posterior não sobrescreve o anterior. Além disso, essa loja pode ser lida (read) e atualizada (updated) de qualquer componente da aplicação, deixando os mesmos mais independentes e desacopladas de outros componentes. Spoiler Alert: É como o superpoder que Goku desenvolve: viajar para outro lugar apenas colocando o dedo na testa. Onde Goku nesse caso é a informação do estado, torna-se capaz de viajar para um componente distante sem precisar passar por todos os outros.

**Redux na prática** - É configurado a estrutura básica para do redux.

**Redux Saga** - É possível criar middlewares capazes de interceptar cada alteração no state pelo redux normal.