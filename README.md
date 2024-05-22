<br>
<br>
<br>

<p align="center">🤓&nbsp;&nbsp;&nbsp;SEVN: Teste Full Stack 01 &nbsp;&nbsp;&nbsp;💻</p>

<br>
<br>
<br>

<p align="center">
  <img align="center" width="640" alt="Home" src="https://user-images.githubusercontent.com/1953194/153975888-5584321f-a764-4fd6-89ed-614fa9265870.png">
</p>

<br>
<br>
<br>

<p align="center">
  <a href="https://www.figma.com/file/uCtGlzgDqEvSYvqffM6ARJ/Teste-SEVN?node-id=1%3A2">VER DESIGN COMPLETO (2 TELAS)</a>
</p>

<br>
<br>
<br>

## Objetivo

Bem vindo(a) ao teste full stack da SEVN!

O teste consiste em:
1. Criar um projeto frontend com duas telas do **SEVN NEWS**, um portal de notícias hipotético.
2. Criar uma API RESTful Node.js **com dados mock** (não precisa se preocupar com banco de dados) que expõe os 3 endpoints que esse portal consumirá.

Você deve criar as telas com base no design [deste link](https://www.figma.com/file/uCtGlzgDqEvSYvqffM6ARJ/Teste-SEVN?node-id=1%3A2).

## Como entregar o projeto?

Recomendamos que você crie dois repositórios separados, um para o código front-end e outro para o back-end. Mas caso você tenha familiaridade com monorepos a entrega também pode ser feita dessa forma.

Crie os repositórios **antes de começar o desenvolvimento**, realize nosso teste fazendo seus commits normalmente, e ao final do teste, é só compartilhar o repositório + seu currículo (caso ainda não nos tenha enviado) através do email: <a href="mailto:vagas@sevn.technology">vagas@sevn.technology</a>!

## Bora pro teste!

### Telas:
- **Home:** Uma página que simula a "homepage" de um portal, contendo as notícias mais importantes.
- **Notícia:** Uma página interna com a notícia completa, que deve ser aberta sempre que você clicar em uma notícia da home.

### APIs:

Você deverá criar 3 endpoints, sendo 2 para montar a Home, e 1 para a tela de Notícia.

Atentar para os seguintes itens na API:
- Habilitar chamadas CORS.
- Usar endpoints com nomenclatura REST que faça sentido (e.g.: `/recurso/:id` ao invés de `/recurso-:id`, etc.);
- Dados devem ser retornados em JSON.
- Apenas endpoints GET.
- Dados JSON mockados (ou seja, pode escrever direto na no código da API, sem precisar usar banco de dados).

#### APIs - Endpoints

1. O primeiro endpoint deve retornar apenas os artigos principais da Home (marcados em roxo abaixo).
<img width="400" alt="1" src="https://user-images.githubusercontent.com/1953194/177860023-41554706-75fb-44f4-b124-deda1186024c.png">


2. O segundo endpoint deve retornar apenas os artigos secundários da home (marcados em roxo abaixo).
<img width="400" alt="2" src="https://user-images.githubusercontent.com/1953194/177860156-92a3de35-f033-4f10-8ec7-b0403cfa3e35.png">

3. O terceiro endpoint é responsável pelos detalhes de uma notícia, para montar a tela abaixo.
<img width="400" alt="3" src="https://user-images.githubusercontent.com/1953194/177860432-50ecb27d-6c35-490d-9ca2-6af36894763c.png">

<a href="https://www.figma.com/file/uCtGlzgDqEvSYvqffM6ARJ/Teste-SEVN?node-id=1%3A2">VER DESIGN COMPLETO (2 TELAS)</a>

## O que será avaliado


**Front-end:** Sua capacidade de construir um layout responsivo, componentizável (ou seja, reaproveitável quando fizer sentido) com código limpo e legível.

**Back-end:** Sua capacidade de criar um código legível, bem organizado, com endpoints RESTful auto-explicativos e payloads padronizados.

## O que esperamos
- Que o layout seja responsivo *(disponibilizamos apenas a versão desktop, queremos ver sua capacidade de evitar que o layout "quebre" em tela menores)*;
- Que o front-end seja feito com alguma tecnologia moderna (React, Svelte, Astro, Vue, SvelteKit, Next.js, Remix, etc).
- Que o back-end seja feito em JavaScript ou TypeScript rodando em Node.js (Ex.: Hono, Fastify, Express.js, etc);
- Que o código seja limpo e legível;
- Que você crie componentes reutilizáveis onde convém;
- Que seu repositório tenha commits com mensagens **legíveis e que façam sentido**;
- Uso de Flexbox ou Grid Layout.
- Que os dados sejam mockados, para manter o teste simples, não é necessário utilizar banco de dados.

**Lembre-se:** Muitos commits detalhando as atividades são melhores que poucos commits com mensagens genéricas e muito código.

## O que não esperamos
- Que sejam usados frameworks CSS como Bootstrap, Material.css, Tailwind e afins.
- que não seja utilizadas bibliotecas CSS-in-JS ou derivadas.
- Que você entregue um repositório apenas com um commit "gigante" com todo o código. Também gostamos de ler commits! :-)

## Outras dúvidas

**Posso utilizar SASS?**<br>
R: SASS, LESS e PostCSS estão liberados.

**Posso utilizar CSS-in-JS?**<br>
R: Nossos projetos não utilizam CSS-in-JS. Recomendamos que seu teste seja feito utilizando CSS/SASS/PostCSS.

**Por que não posso usar Bootstrap/Tailwind CSS?**<br>
Porque nosso objetivo, dentre outras coisas, é avaliar sua capacidade de construir um layout com seus próprios conhecimentos em CSS. O uso de frameworks pode atrapalhar nisso, e nem todo projeto utiliza esses frameworks.

**Como eu lido com a responsividade se não tem layout mobile?**<br>
Nós buscamos uma responsividade básica, e esse é um layout simples, então estamos curiosos para ver como você faria para tornar as duas telas responsivas!

----

No mais, te desejamos boa sorte e estamos ansiosos para ver como você se saiu! 🥳
