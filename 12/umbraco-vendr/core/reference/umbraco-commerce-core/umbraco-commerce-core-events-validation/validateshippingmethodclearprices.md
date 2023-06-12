---
title: ValidateShippingMethodClearPrices
description: API reference for ValidateShippingMethodClearPrices in Umbraco Commerce
---
## ValidateShippingMethodClearPrices

```csharp
public class ValidateShippingMethodClearPrices : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateShippingMethodClearPrices

```csharp
public ValidateShippingMethodClearPrices(ShippingMethodReadOnly shippingMethod, Guid? currencyId, 
    Guid? countryId, Guid? regionId)
```


### Properties

#### CountryId

```csharp
public Guid? CountryId { get; }
```


---

#### CurrencyId

```csharp
public Guid? CurrencyId { get; }
```


---

#### RegionId

```csharp
public Guid? RegionId { get; }
```


---

#### ShippingMethod

```csharp
public ShippingMethodReadOnly ShippingMethod { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->