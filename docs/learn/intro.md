---
sidebar_position: 1
title: 'Overview'
---

:::info
🚧 **Work in progress**
The current Ark implementation requires [Elements introspection opcodes](https://github.com/ElementsProject/elements/blob/master/doc/tapscript_opcodes.md).
For the covenant-less version, code-named **clArk**, please check out the [clArk GitHub repository](https://github.com/ark-network/clArk).
:::

### 👶🏼 ELI5: Ark in Simple Terms

Consider the early private banks that issued banknotes in exchange for gold deposits. These banknotes were redeemable for gold at any time. The banknotes were more convenient to use than gold, but they were only as good as the bank that issued them. If the bank went bankrupt, the banknotes would become worthless.

When Alice **deposits Bitcoin with a server** (akin to a digital bank), she receives a digital check, similar to a banknote but with a crucial difference. This check is akin to **a cheque with an expiration date**.

The digital cheque Alice receives comes with an expiration date. To keep her funds secure and the cheque valid, she **must interact with the server at least once every month**. If Alice fails to do this, the server reserves the right to **claim the Bitcoin backing the cheque upon its maturity**.

She can use this check for payment with anyone else using the same digital bank, bypassing the need to use the Bitcoin blockchain. Before expiration, the check can be **redeemed** for Bitcoin, or it can be **refreshed** by interacting with the server.

Should the digital bank cease to exist, **users can still retrieve their digital gold without the bank's assistance**. This is similar to withdrawing gold from a defunct traditional bank, but in Ark's case, the process is enforced and automated by the Bitcoin blockchain. This ensures that your digital gold remains safe and accessible.

### 📜 How Does Ark Work?

Start by exploring the [Nomenclature](./nomenclature.md) to familiarize yourself with key concepts and terminology. Then, learn how to [Board the Ark](./boarding.md), [Send Payments](./payments.md), and eventually [Leave the Ark](./leaving.md) to withdraw your funds back to the Bitcoin blockchain in case of server unresponsiveness.
