---
title: ProductPriceFreezerService
description: API reference for ProductPriceFreezerService in Vendr, the eCommerce solution for Umbraco v8+
---
## ProductPriceFreezerService

```csharp
public class ProductPriceFreezerService : IProductPriceFreezerService
```

**Inheritance**

* interface [IProductPriceFreezerService](../iproductpricefreezerservice/)

**Namespace**
* [Vendr.Core.Services](../)

### Constructors

#### ProductPriceFreezerService

```csharp
public ProductPriceFreezerService(IProductService productService, 
    IPriceFreezerService priceFreezerService)
```


### Methods

#### GetOrCreateFrozenProductPrice

```csharp
public ProductPrice GetOrCreateFrozenProductPrice(Guid orderId, string productReference, 
    string key, Guid currencyId)
```


---

#### ThawFrozenProductPrice

```csharp
public void ThawFrozenProductPrice(Guid orderId, string key, Guid currencyId)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->