---
title: ValidateShippingMethodSkuChange
description: API reference for ValidateShippingMethodSkuChange in Umbraco Commerce
---
## ValidateShippingMethodSkuChange

```csharp
public class ValidateShippingMethodSkuChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateShippingMethodSkuChange

```csharp
public ValidateShippingMethodSkuChange(ShippingMethodReadOnly shippingMethod, 
    ChangingValue<string> sku)
```


### Properties

#### ShippingMethod

```csharp
public ShippingMethodReadOnly ShippingMethod { get; }
```


---

#### Sku

```csharp
public ChangingValue<string> Sku { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
