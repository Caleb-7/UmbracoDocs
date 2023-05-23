---
title: ValidateTaxClassAliasChange
description: API reference for ValidateTaxClassAliasChange in Vendr, the eCommerce solution for Umbraco
---
## ValidateTaxClassAliasChange

```csharp
public class ValidateTaxClassAliasChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../../vendr-common/vendr-common-events/validationeventbase/)

**Namespace**
* [Vendr.Core.Events.Validation](../)

### Constructors

#### ValidateTaxClassAliasChange

```csharp
public ValidateTaxClassAliasChange(TaxClassReadOnly taxClass, ChangingValue<string> alias)
```


### Properties

#### Alias

```csharp
public ChangingValue<string> Alias { get; }
```


---

#### TaxClass

```csharp
public TaxClassReadOnly TaxClass { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->