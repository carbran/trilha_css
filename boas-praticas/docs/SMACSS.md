# SMACSS

**[ S ] Scalable and**

**[ M ] Modular**

**[ A ] Archtecture for**

**[ C ]**

**[ S ]**

**[ S ]**

## Base

Aqui você não irá colocar nenhuma classe ou id, apenas seletores e pseudo-classes. Sabe aquele reset maroto que costumamos usar? Pra remover margin, padding pois cada navegador possui um valor diferente? Aqui é o local ideal para você colocar! Você também pode estilizar todas as suas listas de forma global, veja alguns exemplos:

```css
* { box-sizing: border-box; }
ul { list-style: none; }
a { text-decoration: none; }
```

## Layout

Para o layout devemos pensar nos principais componentes como cabeçalho, rodapé, entre outros.

```css
.header, .article, .footer { 
   width: 1160px;    
   margin: auto; 
} 
```

## Module

Podemos entender a camada Module como componentes, por exemplo, botões ou alertas, partes realmente reutilizáveis dentro do seu app e que poderão ser usadas em mais de um lugar.

## State

Todo elemento que será modificado ou terá alguma alteração no seu estado inicial, ficará na camada State. Veja alguns exemplos:

```css
.hidden
.visible
.selected
.active
```

## Theme

Essa camada não é muito utilizada, mas o seu objetivo é definir temas específicos, vamos imaginar o seguinte cenário: um sistema possui 3 tipos de usuários: bronze, prata e ouro. Cada perfil terá uma estilização diferente.. Essa atribuição de cores, tipografia e etc deverá ser feito na camada Theme.