# BEM - Blocos, Elementos e Modificadores

**[ B ] Bloco**: Entidade autônoma que é significativa por si só ('header', 'container', 'menu', 'checkbox', 'input').

**[ E ] Elemento**: Uma parte de um bloco que não tem significado independente e está semanticamente vinculada ao seu bloco ('menu item', 'list item', 'checkbox caption', 'header title').

**[ M ] Modificador**: Uma bandeira em um bloco ou elemento. Use-as para alterar a aparência ou o comportamento ('disabled', 'highlighted', 'checked', 'fixed', 'size big', 'color yellow').


> *"BEM faz alusão a Programação Orientada a Objetos (POO), uma maneira de se descrever a realidade no código, com uma variedade de padrões e uma maneira de pensar nas entidades do programa."*
> 
> Varga Stepanova, desenvolvedora front-end do projeto

- Bloco (Block):
  - Entidade independente (bloco de construção)
  - Elemento pai
  - [BLOCO] (.btn)

- Elemento (Elements)
  - Elemento filho
  - Não independente
  - Vinculado a um bloco
  - [BLOCO]__[ELEMENTO] (.btn__price)

- Modificador (Modifier)
  - Modifica um bloco ou elemento
  - Variante para alterar a aparência
    - Variar uma propriedade
    - Atribuir um estado
  - [BLOCO]__[ELEMENTO]--[MODIFICADOR]
    - .menu--dark
    - .btn--orange
    - .menu__link--disabled