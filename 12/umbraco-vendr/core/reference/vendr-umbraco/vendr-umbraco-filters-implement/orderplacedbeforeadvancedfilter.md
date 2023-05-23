---
title: OrderPlacedBeforeAdvancedFilter
description: API reference for OrderPlacedBeforeAdvancedFilter in Vendr, the eCommerce solution for Umbraco
---
## OrderPlacedBeforeAdvancedFilter

```csharp
public class OrderPlacedBeforeAdvancedFilter : OrderAdvancedFilterBase
```

**Inheritance**

* class [OrderAdvancedFilterBase](../../vendr-umbraco-filters/orderadvancedfilterbase/)

**Namespace**
* [Vendr.Umbraco.Filters.Implement](../)

### Constructors

#### OrderPlacedBeforeAdvancedFilter

The default constructor.

```csharp
public OrderPlacedBeforeAdvancedFilter()
```


### Methods

#### Apply

```csharp
public override IQuerySpecification<OrderReadOnly> Apply(IQuerySpecification<OrderReadOnly> query, 
    IOrderQuerySpecificationFactory where, string value)
```


---

#### CanApply

```csharp
public override bool CanApply(string value)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Umbraco.dll -->