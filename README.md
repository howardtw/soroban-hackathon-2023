## Stellar Gateway

### Introduction
Stellar Gateway is a tool to receive payments from crypto-savvy buyers. From the tool, users can select a product, select purchase, and confirm purchase with Freighter. After that, the payment processor will receive USDC, take a 1% hosting fee, and send the rest of the balance to the merchant. 

Once that occurs, the merchant can send a product to the user.


### Interface

```
initialize(e: Env, admin: Identifier)
collect_processing_fee(e: Env, seller: Identifier, product_price_tag: u32, percentage: f32)
refund (buyer: Identifier)
update_price_tag (???)
```
