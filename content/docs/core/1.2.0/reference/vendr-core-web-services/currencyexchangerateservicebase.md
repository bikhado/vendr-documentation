---
title: CurrencyExchangeRateServiceBase
description: API reference for CurrencyExchangeRateServiceBase in Vendr, the eCommerce solution for Umbraco v8+
---
## CurrencyExchangeRateServiceBase

```csharp
public abstract class CurrencyExchangeRateServiceBase : ICurrencyExchangeRateService
```

**Inheritance**

* interface [ICurrencyExchangeRateService](../../vendr-core-services/icurrencyexchangerateservice/)

**Namespace**
* [Vendr.Core.Web.Services](../)

### Methods

#### GetLatestExchangeRates

```csharp
public abstract IDictionary<string, decimal> GetLatestExchangeRates(string baseCurrencyIsoCode, 
    string[] targetCurrencyIsoCodes)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.Web.dll -->