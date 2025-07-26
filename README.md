# Social links profile

Este é um desafio do [Frontend Mentor](https://www.frontendmentor.io?ref=challenge) que visa construir um perfil de links sociais.

## Índice

- [Visão Geral](#visão-geral)
  - [O Desafio](#o-desafio)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [O Meu Processo](#o-meu-processo)
  - [Construído Com](#construído-com)
  - [O Que Aprendi](#o-que-aprendi)
  - [Desenvolvimento Contínuo](#desenvolvimento-contínuo)
- [Autor](#autor)
- [Agradecimentos](#agradecimentos)

## Visão Geral

### O Desafio

Os utilizadores devem ser capazes de:

- Ver o layout ideal para o site, dependendo do tamanho do ecrã do dispositivo.
- Ver os estados de `hover` e `focus` para todos os elementos interativos na página.

### Screenshot

![Screenshot do projeto Social Links Profile](./design/destkop-design.jpg)

### Links

- URL da Solução: 
https://github.com/alex-coder27/social-links-profile-main

- URL do Site Ativo: 
https://alex-coder27.github.io/social-links-profile-main

## O Meu Processo

### Construído Com

- Marcação Semântica HTML5
- CSS Personalizado (com variáveis CSS e Flexbox)
- Media Queries para Responsividade
- Unidades Relativas (rem/em) para escalabilidade e acessibilidade

### O Que Aprendi

Este projeto foi uma excelente oportunidade para praticar e aprimorar as seguintes habilidades:

- Estruturação de conteúdo HTML de forma semântica e acessível.
- Utilização avançada de Flexbox para layout e alinhamento de elementos.
- Criação e organização de folhas de estilo CSS utilizando variáveis para cores e tipografia.
- Implementação de um fluxo de trabalho CSS modular, separando estilos em ficheiros específicos (reset, variáveis, globais, estilo principal, responsivo).
- Desenvolvimento de layouts responsivos usando `media queries` para garantir uma experiência consistente em diferentes tamanhos de ecrã.
- Conversão de unidades `px` para `rem` e `em` para melhorar a escalabilidade e acessibilidade do design.

Exemplo de CSS que utilizei para converter `px` para `rem` / `em`:

```css
/* Antes */
.profile-card {
    width: 384px;
    padding: 40px;
}

/* Depois */

`rem`
.profile-card {
    width: 24rem; /* 384px / 16px (base do navegador) = 24rem */
    padding: 2.5rem; /* 40px / 16px = 2.5rem */
}


/* Exemplo de media query com em */
@media(max-width: 25em) { /* 400px / 16px = 25em */
    .profile-card {
        width: 100%;
    }
}
```

## Autor
- **GitHub:** [alex-coder27](https://github.com/alex-coder27)

## Agradecimentos
Ao [Frontend Mentor](https://www.frontendmentor.io) pelo desafio que me ajudou a praticar e aprimorar minhas habilidades em desenvolvimento web front-end.