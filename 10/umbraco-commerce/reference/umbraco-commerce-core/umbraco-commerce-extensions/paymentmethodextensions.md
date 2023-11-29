---
title: PaymentMethodExtensions
description: API reference for PaymentMethodExtensions in Umbraco Commerce
---
## PaymentMethodExtensions

```csharp
public static class PaymentMethodExtensions
```

**Namespace**
* [Umbraco.Commerce.Extensions](README.md)

### Methods

#### CalculatePrice (1 of 2)

```csharp
public static Price CalculatePrice(this PaymentMethodReadOnly paymentMethod)
```

---

#### CalculatePrice (2 of 2)

```csharp
public static Price CalculatePrice(this PaymentMethodReadOnly paymentMethod, 
    SessionManagerAccessor sessionAccessor, IPaymentCalculator calculator, 
    ITaxSourceFactory taxSourceFactory)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->