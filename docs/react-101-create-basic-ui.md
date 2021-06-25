# React 101

## Step 1: Create basic UI with hardcoded data

![](../public/logo-devcamp-2021.png)

### Goal

Create basic UI using React.js with hardcoded data.
Pages need to be created are:

- Catalog page
- Product detail page

## Data specs

Catalog

```js
[
  {
    product_id: 1,
    product_price: 10000
    product_price_format: 'Rp50.000',
    product_name: 'Payung Tokopedia',
    rating: 5.0,
    seo: {
      ... // tbd
      ... // tbd
      ... // tbd
    },
    product_image: 's3.com',
    product_slug: 'payung tokopedia detail',
  },
  ...hasNext,
]
```

Product detail

```js
{
  product_id: 1,
  product_image_preview: '',
  product_image_high_quality: '',
  product_price: 10000
  product_price_format: 'Rp50.000',
  product_name: 'Payung Tokopedia',
  product_description: '',
}
```

## Figma link

https://www.figma.com/file/GhhUlr2AR3nTUsicx9sOno/DevCamp-2021?node-id=0%3A1

![](../screenshots/02-figma-ui.png)
