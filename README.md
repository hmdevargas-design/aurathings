# AuraThings

Catalogo premium para candeeiros impressos em 3D por pedido.

## Estado atual

- Landing page principal em `index.html`.
- Seis paginas estaticas de produto em `products/`.
- Dados base do catalogo em `data/products.json`.
- Modelos 3D mantidos no repositorio inicial, sem remocao ou reorganizacao destrutiva.

## Direcao de produto

AuraThings deve funcionar primeiro como catalogo/orcamento, nao como checkout online.

Fluxo esperado:

1. Cliente entra pela landing page.
2. Abre uma das paginas de produto pelas fotos do catalogo.
3. Escolhe modelo, acabamento, quantidade e contexto do espaco.
4. Pede orcamento por contacto direto.
5. Pagamento e prazo sao confirmados manualmente.

## Decisoes tecnicas

- Manter estatico no curto prazo.
- Usar `data/products.json` como referencia do catalogo para futura migracao para Vite, Next.js ou Shopify.
- Evitar integracoes de pagamento externas ate decisao explicita.
- Google Drive pode continuar como biblioteca de assets/modelos; desenvolvimento ativo fica no Git.

## Proximos passos

- Validar nomes reais dos produtos e precos.
- Validar se `geral@aurathings.pt` sera o contacto definitivo.
- Definir imagens finais por produto.
- Criar politica simples de encomenda, prazos, materiais e cuidados.
- Avaliar Vite apenas quando o catalogo crescer ou quando houver necessidade de componentes reutilizaveis.
