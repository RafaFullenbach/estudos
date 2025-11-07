- é o atributo lang :
`<Html lang="Pt-br">`

- ele serve é usado para acessibilidade, SEO e tradução automática.

## Acessibilidade

- Na acessibilidade o leitor de tela que pode ser usado por deficientes visuais, vai falar com sotaque e entonação com base nesse atributo, caso você não especifique ele pode ter bugs (tipo"porturgueise")

## SEO (Motores de busca)

- Motores de busca, como o Google, usam lang para entender o idioma do conteúdo e mostrar o site para o público certo.

- Se você define `lang="pt-BR"`, o Google sabe que o conteúdo é português brasileiro e o exibe para usuários que buscam nesse idioma.

## Navegadores e tradução automática

- O `lang` ajuda navegadores (como Chrome ou Edge) a **oferecer traduções automáticas corretas** e também pode afetar **configurações regionais**, como formatação de datas, números e moeda.

## Dica extra

- Você também pode aplicar o `lang` em **elementos específicos** dentro da página, se houver partes em outro idioma:

`<p>Este site é <span lang="en">responsive</span> e rápido!</p>`

## Bibliotecas de internacionalização

- bibliotecas de internacionalização como o i18n, ngx-translate, etc..., devem ao trocar de idioma alterar esse atributo dinamicamente para que o site fique acessível e identificável e traduzível.