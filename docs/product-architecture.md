# Arquitetura inicial do catalogo AuraThings

## Objetivo

Transformar a landing page numa pagina principal com ligacao para paginas de produto, mantendo o projeto simples, estatico e preparado para migracao futura.

## Estrutura

```text
index.html
data/products.json
products/
  product.css
  lumina.html
  solsticio.html
  ambar.html
  vortex.html
  coral.html
  aura-pendant.html
aurathings/
  foto1.jpg
  foto2.jpg
  foto3.png
  foto4.png
  foto5.png
  foto6.png
  foto7.png
```

## Regras de conteudo

- A home apresenta a marca, beneficios, colecao e fluxo de encomenda.
- Cada foto de produto na home deve ligar diretamente a uma pagina em `products/`.
- Cada pagina de produto deve ter imagem, categoria, preco desde, prazo, materiais, acabamentos e CTA de orcamento.
- O CTA principal e sempre pedido/orcamento/contacto, nao carrinho.
- Pagamentos devem ser descritos como processo manual: MB WAY, transferencia ou outro metodo definido pelo proprietario.

## Fluxo AIOX aplicado

- Analisar: confirmar estado do repo e conteudo existente antes de alterar.
- Implementar: fazer uma fatia pequena e funcional.
- Observar: validar links, imagens e estado Git.
- Expandir: so depois evoluir para stack moderna ou Shopify.

## Quando migrar para Vite ou Next.js

Manter estatico enquanto houver poucas paginas e baixa necessidade de logica. Migrar quando houver:

- Mais produtos e filtros.
- Componentes repetidos demais para manter manualmente.
- Necessidade de rotas dinamicas.
- Integracao com CMS, Shopify ou formulario estruturado.
