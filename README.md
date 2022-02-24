# DST-Product-Card

Paquete de pruebas de despliegue en NPM 

### Alexis Guerrero

## Ejemplo 

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'dst-product-card'
```

```
<ProductCard 
  product={ product }
  initialValues={{
    count: 4,
    maxCount: 10
  }} 
>
  {
    ( {reset, count, increaseBy, isMaxCountReached, maxCount } ) => (
      <>
        <ProductImage />
        <ProductTitle />
        <ProductButtons />
      </>
    )
  }
</ProductCard >
```