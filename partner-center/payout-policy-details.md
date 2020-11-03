---
title: Detalhes da política de pagamento - Mercado comercial da Microsoft
description: Saiba mais sobre detalhes relacionados com as políticas de pagamento de mercado comercial, incluindo horários e recuperação.
ms.service: marketplace
ms.subservice: partnercenter-marketplace-publisher
ms.topic: conceptual
author: mingshen-ms
ms.author: mingshen
ms.date: 09/28/2020
ms.openlocfilehash: eec5f85f38280757bc1e5d5c36a4dd1ac5ce8d22
ms.sourcegitcommit: 3c45a181ef86b3a4866e97fb50efeae8714ab3f7
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 10/19/2020
ms.locfileid: "92530479"
---
# <a name="payout-policy-details"></a>Detalhes da política de dividendos

Este artigo discute o processo de pagamento da Microsoft, o calendário de pagamentos, onde encontrar o estado de um pagamento, e a política de recuperação.

## <a name="payment-schedules"></a>Horários de pagamento

As seguintes secções descrevem o nosso processo de pagamentos.

### <a name="enterprise-agreement-transactions-after-may-1-2020"></a>Transações do Acordo de Empresa após 1 de maio de 2020

#### <a name="update-to-our-commercial-marketplace-publisher-payout-model"></a>Atualização para o nosso modelo de pagamento de editor de marketplace comercial

A partir de 1 de maio de 2020, estamos a atualizar a nossa política de pagamentos relativa a produtos adquiridos no Azure Marketplace ou AppSource por clientes com um Acordo Empresarial da Microsoft. Quando um cliente comprar um produto da Azure Marketplace ou appSource utilizando o seu atual Microsoft Enterprise Agreement para transações após 1 de maio de 2020, começaremos a emitir pagamentos no próximo ciclo de pagamentos de 30 dias após a fatura do cliente. As transações em que um cliente utiliza um cartão de crédito são inalteradas e continuarão a ter um período de detenção de 30 dias antes do pagamento. Esta tabela mostra detalhes sobre o calendário de pagamentos.

> [!NOTE]
> Consulte [o Processo de não pagamento do cliente](#process-for-customer-non-payment) abaixo para as ações que tomamos se o cliente não pagar, mas já lhe emitimos um pagamento.

| Evento  | Data (UTC) | Visibilidade do parceiro: Relatório de pagamento do Partner Center  |  Visibilidade do parceiro: Partner Center analytics\* |
| --- | --- | --- | --- |
| Transação ou mês de utilização | 8/1/2020 – 8/31/2020 | N/D | **Relatório de utilização** : novo consumo mostrado (refrescado a cada quatro horas)<br>**Relatório de** encomendas : N/A |
| Fim do prazo (mês) | 8/31/2020 | N/D | **Relatório de utilização** : consumo final de mês mostrado<br>**Relatório de** encomendas : N/A |
| Ordem gerada | 9/3/2020 – 9/7/2020 | N/D | **Relatório de utilização** : consumo mostrado com OrderID/OrderLineItemID<br>**Relatório do pedido** : encomendas de clientes mostradas como ATIVE |
| Calcular o ganho de pagamento | 9/4/2020 – 9/10/2020 | Marcado como **não processado** no histórico de transações no painel de pagamento | **Relatório de utilização** : consumo mostrado com OrderID/OrderLineItemID<br>**Relatório do pedido** : encomendas de clientes mostradas como ATIVE |
| Pagamento mensal | 10/5/2020 | Marcado como Próximo na história **da** transação no painel de pagamento | **Relatório de utilização** : consumo mostrado com OrderID/OrderLineItemID<br>**Relatório do pedido** : encomendas de clientes mostradas como ATIVE |
| Data de pagamento\** | 10/15/2020 | Marcado como **Enviado** no Histórico de Transações e na secção de Pagamentos do Painel de Pagamentos | **Relatório de utilização** : consumo mostrado com OrderID/OrderLineItemID<br>**Relatório do pedido** : encomendas de clientes mostradas como ATIVE |
| Fatura do cliente recolhida | 12/1/2020 | Marcado como **Enviado** no Histórico de Transações e na secção de Pagamentos do Painel de Pagamentos | **Relatório de utilização** : consumo mostrado com OrderID/OrderLineItemID<br>**Relatório do pedido** : encomendas de clientes mostradas como ATIVE  |
|  |  |  |  |

\* Os relatórios de utilização e ordem estão acessíveis na secção Analisar no Centro parceiro. \* *. A data de pagamento é na Hora Padrão do Pacífico (PST).

### <a name="customers-who-pay-using-credit-card-or-invoice"></a>Clientes que pagam com cartão de crédito ou fatura

Todas as compras com cartão de crédito ou fatura mensal têm um período de detenção de 30 dias para garantir que os fundos são apurados e não há cobranças ou suspeitas de fraude.

| Evento  | Data (UTC) | Visibilidade do parceiro: Relatório de pagamento do Partner Center  |  Visibilidade do parceiro: Partner Center analytics\*  |
| --- | --- | --- | --- |
| Transação ou mês de utilização | 8/1/2019 - 8/31/2019 | N/D | **Relatório de utilização** : novo consumo mostrado (refrescado a cada quatro horas)<br>**Relatório de** encomendas : N/A |
| Fim do prazo (mês) | 8/31/2019 | N/D | **Relatório de utilização** : consumo final de mês mostrado<br>**Relatório de** encomendas : N/A |
| Ordem gerada | 9/3/2019 – 9/7/2019 | N/D | **Relatório de utilização** : consumo mostrado com OrderID/OrderLineItemID<br>**Relatório do pedido** : encomendas de clientes mostradas como ATIVE |
| Fatura do cliente recolhida | 9/7/2019 – 9/10/2019 | N/D | **Relatório de utilização** : consumo mostrado com OrderID/OrderLineItemID<br>**Relatório do pedido** : encomendas de clientes mostradas como ATIVE |
| Calcular o pagamento | 9/8/2019 -9/12/2019 | Marcado como **não processado** no histórico de transações no painel de pagamento | **Relatório de utilização** : consumo mostrado com OrderID/OrderLineItemID<br>**Relatório do pedido** : encomendas de clientes mostradas como ATIVE |
| Pagamento mensal | 11/5/2019\* | Marcado como **O Próximo** no Histórico de Transações no Painel de Pagamentos | **Relatório de utilização** : consumo mostrado com OrderID/OrderLineItemID<br>**Relatório do pedido** : encomendas de clientes mostradas como ATIVE |
| Data de pagamento\** | 11/15/2019 | Marcado como **Enviado** no Histórico de Transações e na secção Pagamentos no Painel de Pagamentos | **Relatório de utilização** : consumo mostrado com OrderID/OrderLineItemID<br>**Relatório do pedido** : encomendas de clientes mostradas como ATIVE |
|  |  |  |  |

\* Os relatórios de utilização e ordem estão acessíveis na secção Analisar no Centro parceiro.</br>\** A data de pagamento é na Hora Padrão do Pacífico (PST).

### <a name="enterprise-agreement-transactions-prior-to-may-1-2020"></a>Transações do Contrato de Empresa antes de 1 de maio de 2020

Todas as compras que ocorrem antes desta data são processadas e pagas de acordo com o calendário abaixo, depois de a Microsoft ter recolhido o pagamento dos clientes e processado a taxa de mercado.

| Evento  | Data (UTC)  | Visibilidade do parceiro: Relatório de pagamento do Partner Center  |  Visibilidade do parceiro: Partner Center analytics\*  |
| --- | --- | --- | --- |
| Transação ou mês de utilização | 8/1/2019 – 8/31/2019 | N/D | **Relatório de utilização** : novo consumo mostrado (refrescado a cada quatro horas)<br>**Relatório de** encomendas : N/A |
| Fim do prazo (mês) | 8/31/2019 | N/D | **Relatório de utilização** : consumo final de mês mostrado<br>**Relatório de** encomendas : N/A |
| Ordem gerada | 9/3/2019 – 9/7/2019 | N/D | **Relatório de utilização** : consumo mostrado com OrderID/OrderLineItemID<br>**Relatório do pedido** : encomendas de clientes mostradas como ATIVE |
| Fatura do cliente recolhida | 12/1/2019 | N/D | **Relatório de utilização** : consumo mostrado com OrderID/OrderLineItemID<br>**Relatório do pedido** : encomendas de clientes mostradas como ATIVE |
| Calcular o pagamento | 12/5/2019 –12/7/2019 | Marcado como **não processado** no histórico de transações no painel de pagamento | **Relatório de utilização** : consumo mostrado com OrderID/OrderLineItemID<br>**Relatório do pedido** : encomendas de clientes mostradas como ATIVE |
| Pagamento mensal | 1/5/2019 | Marcado como **O Próximo** na história da transação no painel de pagamentos | **Relatório de utilização** : consumo mostrado com OrderID/OrderLineItemID<br>**Relatório do pedido** : encomendas de clientes mostradas como ATIVE |
| Data de pagamento\** | 1/15/2019 | Marcado como **Enviado** no Histórico de Transações e na secção pagamentos no Painel de Pagamentos | **Relatório de utilização** : consumo mostrado com OrderID/OrderLineItemID<br>**Relatório do pedido** : encomendas de clientes mostradas como ATIVE |
|  |  |  |  |

\* Os relatórios de utilização e ordem estão acessíveis na secção Analisar no Centro parceiro.</br>\** A data de pagamento é na Hora Padrão do Pacífico (PST).

## <a name="process-for-customer-non-payment"></a>Processo de não pagamento de clientes

Em raras ocasiões, a Microsoft não consegue cobrar pagamentos aos clientes pelas suas compras no mercado comercial. Quando um cliente não paga à Microsoft de acordo com o seu calendário de faturação, iniciamos o processo de cobranças. Este processo demora aproximadamente quatro meses e envolve uma comunicação persistente da Microsoft. Se o pagamento não for recebido até ao final deste processo, a Microsoft anula os fundos como incobráveis.

De acordo com o processo de pagamento aqui articulado, a Microsoft pode já ter pago fundos a editores (você) que são, em última análise, incobráveis. Portanto, temos um processo de conciliação destes montantes. Para garantir que tem avisado que o seu (já recebido) pagamento pode ser reconciliado, será notificado quando um cliente estiver no processo de cobranças e as compras são suscetíveis de ser amortizadas.

A Microsoft recuperará quaisquer pagamentos já pagos utilizando um dos seguintes métodos: (1) A Microsoft pode subtrair os montantes não pagos de pagamentos futuros; por exemplo, se $1.000 em pagamentos forem considerados incobráveis e anulados, os seus pagamentos futuros serão retidos até que os $1.000 sejam recuperados, ou (2) a Microsoft pode solicitar um reembolso ou editores de fatura para quaisquer valores não cobrados.

Segue-se um exemplo de calendário:

| Evento | Data aproximada | Visibilidade do parceiro |
| --- | --- | --- |
| Data de pagamento de exemplo | 10/15/2020 | Marcado como **Enviado** no Histórico de Transações e na secção de Pagamentos no Painel de Pagamentos |
| <font color="red">Se o cliente não pagar à Microsoft</font> | 12/2/2020 – 12/5/2020 | Sem mudanças, como acima |
| Cliente recebe primeiro e-mail de pagamento em atraso | 12/6/2020 | Nenhum |
| Cliente recebe e-mails regulares de urgência crescente | 12/7/2020 – 1/31/2021 | Nenhum |
| Editor é notificado write-off é provável | 1/7/2021 | E-mail notificação enviada ao editor que o seu cliente ainda não enviou o pagamento. O ID de transação e o valor em dólares estão incluídos. |
| Cliente recebe aviso de rescisão | 2/1/2021 | Nenhum |
| Fim do processo de recolha / os fundos são anulados | 2/15/2021 | E-mail notificação enviada ao editor de que os fundos foram anulados. O ID de transação e o valor em dólares estão incluídos. |
| O pagamento é deduzido | 3/1/2021 | Editor verá transação negativa em Declaração de Pagamento do Partner Center |
| O pagamento é retido | 3/15/2021 | Os pagamentos futuros serão mostrados na Declaração de Pagamento do Centro Parceiro. A editora não receberá o pagamento até que o saldo não seja mais negativo.  |
|||

## <a name="number-of-days-for-payments-to-reach-a-payout-account"></a>Número de dias para pagamentos chegarem a uma conta de pagamento

Normalmente enviamos qualquer pagamento devido num dado mês no 15º dia desse mês, mas leva tempo adicional para o pagamento chegar à sua conta. O número de dias depende do método de pagamento que utilizamos para a sua conta, conforme descrito abaixo.

> [!NOTE]
> Os dias abaixo apresentados são aproximados; qualquer pagamento pode demorar um tempo maior ou mais curto para chegar à sua conta.

| Método de pagamento     | Número de dias para chegar à conta de pagamento     |
|--------------------|--------------------------------------------|
| PayPal             | 1 dia útil                             |
| ACH/SEPA           | 2-3 dias úteis                          |
| Transferência bancária      | 7-10 dias úteis                         |
|

## <a name="next-steps"></a>Passos seguintes

- [Detalhes fiscais](tax-details-marketplace.md)
