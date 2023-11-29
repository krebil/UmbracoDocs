---
title: ValidateShippingMethodAliasChange
description: API reference for ValidateShippingMethodAliasChange in Umbraco Commerce
---
## ValidateShippingMethodAliasChange

```csharp
public class ValidateShippingMethodAliasChange : ValidationEventBase
```

**Inheritance**

* Class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateShippingMethodAliasChange

```csharp
public ValidateShippingMethodAliasChange(ShippingMethodReadOnly shippingMethod, 
    ChangingValue<string> alias)
```


### Properties

#### Alias

```csharp
public ChangingValue<string> Alias { get; }
```


---

#### ShippingMethod

```csharp
public ShippingMethodReadOnly ShippingMethod { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->