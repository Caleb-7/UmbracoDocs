---
title: ValidateTaxClassTaxRateChange
description: API reference for ValidateTaxClassTaxRateChange in Umbraco Commerce
---
## ValidateTaxClassTaxRateChange

```csharp
public class ValidateTaxClassTaxRateChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateTaxClassTaxRateChange

```csharp
public ValidateTaxClassTaxRateChange(TaxClassReadOnly taxClass, ChangingValue<TaxRate> taxRate, 
    Guid? countryId, Guid? regionId)
```


### Properties

#### CountryId

```csharp
public Guid? CountryId { get; }
```


---

#### RegionId

```csharp
public Guid? RegionId { get; }
```


---

#### TaxClass

```csharp
public TaxClassReadOnly TaxClass { get; }
```


---

#### TaxRate

```csharp
public ChangingValue<TaxRate> TaxRate { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
