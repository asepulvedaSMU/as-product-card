# as-product-card

Este es un paquete de de pruebas de despliegues npm

## Ejemplo

```
import {ProductCard, ProductImage, ProductTitle,ProductButtons } from 'do-product-cards';
```

```
      <ProductCard
        product={product}
        initialValues={{
          count: 4,
          // maxCount: 10,
        }}
      >
        {({ count, increaseBy, reset, maxCount, isMaxCountReached }) => (
          <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
          </>
        )}
      </ProductCard>
```
