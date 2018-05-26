# TokenPocket Deeplink

This is document of how to use TokenPocket deeplink to connect your Dapps or ICO to TokenPocket.

![dapp](/deeplink/dapp.gif) ![transaction](/deeplink/transaction.gif)

## Dapp Deeplink

1. If user has install TokenPocket. From this link, User can open your dapp in TokenPocket by click this link Directly.
2. If the user have not install TokenPocket. This link will navigate User to the apple store to dowload TokenPocket.

```text
https://tokenpocket.github.io/applink?dappUrl=<your dapp url link>
```

[Sample Dapp Deeplink](https://tokenpocket.github.io/applink?dappUrl=https://www.cryptokitties.co/)

## Transaction Deeplink (Beta)

1. If user has install TokenPocket. From this link, User can open the transaction page with the address.
2. If the user have not install TokenPocket. This link will navigate User to the apple store to dowload TokenPocket.

```text
https://tokenpocket.github.io/applink?toAddress=<your ethereum address>
```

[Sample Transaction Deeplink](https://tokenpocket.github.io/applink?toAddress=0xb786f545a33b47078184a0cd559902f3b1d7926c)
