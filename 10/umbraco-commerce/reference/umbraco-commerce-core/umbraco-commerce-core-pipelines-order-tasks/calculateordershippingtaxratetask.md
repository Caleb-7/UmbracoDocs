---
title: CalculateOrderShippingTaxRateTask
description: API reference for CalculateOrderShippingTaxRateTask in Umbraco Commerce
---
## CalculateOrderShippingTaxRateTask

```csharp
public class CalculateOrderShippingTaxRateTask : 
    PipelineTaskWithTypedArgsBase<OrderCalculationPipelineArgs, OrderCalculation>
```

**Inheritance**

* class [PipelineTaskWithTypedArgsBase&lt;!0,!1&gt;](../../umbraco-commerce-common/umbraco-commerce-common-pipelines/pipelinetaskwithtypedargsbase-2.md)

**Namespace**
* [Umbraco.Commerce.Core.Pipelines.Order.Tasks](README.md)

### Constructors

#### CalculateOrderShippingTaxRateTask

```csharp
public CalculateOrderShippingTaxRateTask(IShippingCalculator shippingCalculator)
```


### Methods

#### Execute

```csharp
public override PipelineResult<OrderCalculation> Execute(OrderCalculationPipelineArgs args)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
