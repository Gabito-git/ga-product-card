# GA-product-card

Este es un paquete de pruebas de despliegue en NPM

### Luis Gabriel Arevalo

## Ejemplo

```
import {
  ProductCard,
  ProductImage,
  ProductTitle,
  ProductButtons } from 'ga-product-card'
```

```
<ProductCard 
    product={ product }  
    initialValues={{
        count: 6,
        maxCount: 10
    }}             
>
    {   // Se expone toda la información que genera el componente
        ( { reset, increaseBy, isMaxCountReached, count } ) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
    
</ProductCard>
```
