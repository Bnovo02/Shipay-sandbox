---
title: Inativar intenção de conciliação
api:
  file: Conciliação.json
  operationId: delete_reconciliation-v1-pix-any-bank-intention
hidden: false
---
**Este serviço é responsável por cancelar o interesse de conciliação de uma conta cadastrada na modalidade Pix qualquer banco.**

**Para realizar a desativação é possível utilizar duas formas de autenticação:**

* [Autenticação para acesso aos serviços transacionais](https://shipay-documentation.readme.io/reference/post_pdvauthth)
* [Autenticação por sistema para acesso aos serviços](https://shipay-documentation.readme.io/reference/post_pdvsysauth-1).

**De acordo com o tipo de autenticação é necessário enviar os seguintes parâmetros na requisição:**

* type
* store\_pos\_id (Autenticação por sistema)
* customer\_id (Autenticação por sistema)