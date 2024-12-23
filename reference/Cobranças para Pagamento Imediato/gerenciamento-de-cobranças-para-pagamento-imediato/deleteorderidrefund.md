---
title: Realizar devolução do pagamento de uma cobrança
api:
  file: Order.json
  operationId: delete_order-order-id-refund
hidden: false
---
**Este serviço realiza o estorno do pagamento de uma determinada cobrança.**

**É possível relizar dois tipos de estorno:**

**1) Estorno total:** Devolve o total do valor pago.

**2) Estorno parcial:** Devolve parcialmente o valor do pagamento efetuado, conforme informado na requisição.