# Constela

Landing page de uma trilha fictícia de front-end para quem está trocando de área, feita com **HTML5 semântico e CSS3 puro**, sem frameworks e sem JavaScript.

> Projeto de estudo. A Constela e as turmas citadas na página não existem. O layout foi desenvolvido a partir de uma referência visual, e todo o código foi escrito por mim.

🔗 Demo: https://biancabarcaa.github.io/Constela/

## O que o projeto pratica

**HTML**
- Estrutura semântica com `header`, `nav`, `main`, `section`, `article`, `aside` e `footer`
- Formulário acessível com `label`, `fieldset` e `legend`
- Validação nativa (`required`, `type="email"`)

**CSS**
- Variáveis CSS (`:root`) para cores, fontes, espaçamentos e bordas
- Nomenclatura **BEM** nas classes (`bloco__elemento--modificador`)
- Flexbox no cabeçalho, no menu e nos botões
- Abordagem **mobile-first** com media query em `min-width`
- Menu hambúrguer **sem JavaScript**, usando `input[type="checkbox"]` + `:checked` + `~`
- Checkbox customizado com a mesma técnica
- Estados do formulário com `:focus`, `:invalid:not(:placeholder-shown)` e `:focus-visible`
- Cabeçalho fixo com `position: sticky` e rolagem suave (`scroll-behavior`)
- Constelação do hero feita só com `div`s e `position: absolute`
- Respeito a `prefers-reduced-motion` para quem desativa animações no sistema

## Estrutura

```
constela/
├── style.css
├── index.html
├── README.md
└── constela-logo.png
```

## Como rodar

1. Baixe ou clone o repositório
2. Abra o `index.html` no navegador

Não precisa instalar nada.

## Próximos passos

- Organizar os módulos e os depoimentos com CSS Grid
- Adicionar JavaScript para mensagens de erro personalizadas no formulário
- Testar com leitor de tela

## Autora

**Bianca Barca**
LinkedIn = https://www.linkedin.com/in/bianca-barca-/ · GitHub = https://github.com/BiancaBarcaa
