---
title: Cancelar uma cobrança pendente
api:
  file: Order.json
  operationId: delete_order-order-id
hidden: false
---
**Este serviço realiza o cancelamento de uma cobrança na Shipay em caso de desistência do pagamento.**

**IMPORTANTE:**

* **Solicitar o cancelamento para uma cobrança aprovada, resultará no estorno da mesma.**
* Estornos realizados pelo serviço de cancelamento não serão aceitos na homologação, caso seja necessário estornar o valor, deve ser utilizado o serviço, [Estorno de cobranças](https://shipay-documentation.readme.io/reference/delete_order-order-id-refund-1).
* Todos os status apresentados devem ser tratados de acordo com os nossos **[Fluxos de Cancelamento](https://docs.shipay.com.br/flows-cancellation-reversal).**