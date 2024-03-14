# shopify-multipass

[Shopify Multipass](https://shopify.dev/docs/api/multipass) module for Node.js.

## Installation

```
npm install shopify-multipass
```

## Usage

```js
const shopifyMultipass = new ShopifyMultipass(
	'your-multipass-secret',
	'https://your-store.myshopify.com/'
);

const url = shopifyMultipass.generateUrl({
	email: 'name@example.com',
});
```
