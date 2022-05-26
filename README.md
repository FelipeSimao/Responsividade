
# Responsividade

Quando fazemos sites/sistemas web queremos que ele seja alcançado pelo maior número de pessoas, certo? Cerca de 58% das pessoas no Brasil acessam a internet por meio de celulares. Então é de extrema importância que seus sites tenham compatibilidade com qualquer dispositivo, seja ele mobile ou desktop.
 

## Referência

 - [developer.mozilla.org](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
 - [medium.com](https://medium.com/@fnandaleite/entendendo-as-diferen%C3%A7as-entre-design-responsivo-adaptativo-e-mobile-first-ea3c61fc9181)
 - [w3schools.com](https://www.w3schools.com/css/css_rwd_mediaqueries.asp)


## Principais tipos de responsividade

### Desktop First:
O termo "Desktop First" significa priorizar o design acessível a dispositivos desktop, e futuramente trabalhar a versão mobile

### Mobile First:
O termo "Mobile First" significa priorizar o design acessível a dispositivos mobile, e futuramente trabalhar a versão desktop.

### Design flexível
O "design flexível" é possível em design mais simples onde é necessário apenas um código que se adapta para os dois dispositivos.
## Uso/Exemplos
#### como usar design responsivos no CSS

```CSS

//medida padrao:

    Container {
      width: 300px;
    }

// medida adaptativa:
//max ou min

  @media(max-width: 600px){ 

      Container {
        width: 600px;
      }

  }

  // Pode ser usado tambem o flexbox ou grid:
  // o flex-wrap permite a quebra de linha.

  Container{
    display: flex;
    flex-wrap: wrap;

  }
```


## Demonstração

![Logo](https://www.kadunew.com/blog/wp-content/uploads/2014/12/mobile-first-ou-desktop-first.gif)


## Mobile First é usado por

Este conceito foi adotado por:

- Facebook 
- Twitter
- Linkedin 
- Microsoft
- Projetos novos do Google

#
## Autores

- [@felipesimao](https://www.github.com/felipesimao)



