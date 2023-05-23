---
title: VisitContext<TValue>
description: API reference for VisitContext<TValue> in Vendr, the eCommerce solution for Umbraco
---
## VisitContext&lt;TValue&gt;

```csharp
public sealed class VisitContext<TValue> : IVisitContext
```

**Inheritance**

* interface [IVisitContext](../ivisitcontext/)

**Namespace**
* [Vendr.Common.Visitors](../)

### Methods

#### Get&lt;TState&gt;

```csharp
public TState Get<TState>()
```


---

#### Set&lt;TState&gt;

```csharp
public void Set<TState>(TState newState)
```


---

#### TryGet&lt;TState&gt;

```csharp
public bool TryGet<TState>(out TState state)
```


---

#### TrySet&lt;TState&gt;

```csharp
public bool TrySet<TState>(TState state)
```


---

#### Create

```csharp
public static IVisitContext Create(TValue value)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Common.dll -->