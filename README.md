# AgroFuturo - Tecnologia no Campo

Site desenvolvido para apresentar como a tecnologia pode transformar o agronegocio, com foco em agricultura digital, drones, sensores, inteligencia artificial, produtividade, expansao agricola e contato para atendimento.

## Objetivo do projeto

O objetivo do site e mostrar, de forma visual e organizada, como ferramentas tecnologicas ajudam o produtor rural a tomar decisoes melhores, reduzir desperdicios e aumentar a produtividade no campo.

## Principais secoes

- **Inicio:** apresenta a proposta do projeto AgroFuturo e os principais destaques da tecnologia agricola.
- **Tecnologias:** mostra exemplos como drones agricolas, maquinas autonomas, sensores inteligentes e IoT no campo.
- **Informacoes importantes:** explica pontos essenciais para usar tecnologia agricola com seguranca e resultado.
- **Dicas de produtividade:** lista etapas importantes para melhorar o preparo do solo, o uso de GPS e o periodo de plantio.
- **Expansao:** apresenta um mapa ilustrativo da expansao da tecnologia agricola no Brasil.
- **Producao:** mostra como a tecnologia melhora rastreabilidade, colheita e tomada de decisao.
- **Inteligencia Artificial:** explica como a IA pode prever safras, detectar pragas e otimizar rotas.
- **Beneficios:** resume ganhos como economia de agua, reducao de desperdicios e aumento de produtividade.
- **Contato:** centraliza telefone, e-mail, consulta, agendamento e formulario de mensagem.

## Ajustes realizados

- A secao **Contato** foi centralizada em uma unica parte do site.
- O menu **Contato** foi corrigido para abrir diretamente a secao `#contact`.
- O botao **Solicitar Proposta** da pagina inicial agora leva para a secao de Contato.
- Foram criados arquivos de redirecionamento para evitar erro de "arquivo nao encontrado":
  - `contact.html`
  - `technologies.html`
  - `tecnologies.html`
  - `production.html`
  - `intelligence.html`
- As imagens que estavam quebrando foram substituidas por arquivos locais na pasta `assets`.

## Estrutura de arquivos

```text
tecnologia-no-campo-main/
|-- index.html
|-- style.css
|-- script.js
|-- README.md
|-- contact.html
|-- technologies.html
|-- tecnologies.html
|-- production.html
|-- intelligence.html
`-- assets/
    |-- mapa-expansao-brasil.svg
    `-- produtor-conectado.svg
```

## Como abrir o site

### Opcao 1: abrir direto no navegador

Abra o arquivo:

```text
index.html
```

### Opcao 2: rodar com servidor local

Dentro da pasta do projeto, execute:

```bash
python -m http.server 4174 --bind 127.0.0.1
```

Depois acesse:

```text
http://127.0.0.1:4174/index.html
```

## Tecnologias usadas

- HTML5
- CSS3
- JavaScript
- Imagens SVG locais
- Fontes do Google Fonts

## Observacoes

Este e um site estatico, portanto nao precisa de instalacao de dependencias. O formulario de contato e visual e nao envia dados para um servidor, pois nao ha backend configurado no projeto.
