---
title: Realizar Devolução de Saque
api:
  file: Pix Saque e troco.json
  operationId: delete_order-order-id-refund-withdraw
hidden: false
---
**Este serviço solicita a devolução de um Pix saque.**

É possível realizar devolução parcial e total dos valores utilizados como saque na frente do caixa.

**Casos de uso:**

* Valor de saque solicitado maior que o valor disponível no ponto de venda no momento da transação.
* Cliente não aceitar a cédula por estar danificada ou manchada.
* Desistência de saque ou valor solicitado incorretamente.