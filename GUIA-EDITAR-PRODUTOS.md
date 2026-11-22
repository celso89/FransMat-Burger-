# Guia rápido — gerir o menu FransMat Burger pelo GitHub

## Alterar o preço de um produto

Abre `data/produtos.json`, clica no lápis e procura o produto. Por exemplo:

```json
{
  "id": "cachorro",
  "name": "Cachorro",
  "category": "cachorro",
  "description": "Cachorro especial com 1 dose de batata incluída.",
  "price": 3000,
  "tag": "Com batata",
  "image": "3000.PNG"
}
```

Para mudar de 3.000 Kz para 3.500 Kz, altera apenas:

```json
"price": 3500
```

Depois clica **Commit changes**.

## Adicionar um produto

Acrescenta um novo objecto dentro da lista, separando-o do anterior com uma vírgula. Exemplo:

```json
{
  "id": "hamburguer-duplo",
  "name": "Hambúrguer Duplo",
  "category": "hamburguer",
  "description": "Hambúrguer com duas carnes e batata.",
  "price": 6500,
  "tag": "Novo",
  "image": "hamburguer-duplo.jpg"
}
```

Regras:
- `id`: identificador único, sem espaços. Não repitas IDs.
- `category`: usa `hamburguer`, `combo` ou `cachorro` para aparecer nos filtros existentes.
- `price`: número inteiro, sem `Kz` e sem pontos.
- `image`: nome exacto do ficheiro de imagem carregado na raiz do repositório.

## Remover um produto

Apaga o objecto completo desse produto, incluindo a vírgula que o separa dos outros. Tem cuidado para manter o JSON válido.

## Alterar WhatsApp, entrega ou contas bancárias

Abre `data/config-site.json`. Exemplo:

```json
{
  "whatsapp": "244951643511",
  "delivery_fee": 1500,
  "delivery_free_from_orders": 2,
  "owner": "Hélio Pedro",
  "bankAccounts": {
    "bfa": "000600005364702530114",
    "bai": "004000005111011410193",
    "atlantico": "005500006095825410158",
    "express": "945942660"
  }
}
```

Guarda sempre com **Commit changes**. A publicação pode demorar alguns minutos.
