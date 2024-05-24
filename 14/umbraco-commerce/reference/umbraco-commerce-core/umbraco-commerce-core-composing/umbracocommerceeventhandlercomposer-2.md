---
title: UmbracoCommerceEventHandlerComposer<TEvent,TInterface>
description: API reference for UmbracoCommerceEventHandlerComposer<TEvent,TInterface> in Umbraco Commerce
---
## UmbracoCommerceEventHandlerComposer&lt;TEvent,TInterface&gt;

```csharp
public class UmbracoCommerceEventHandlerComposer<TEvent, TInterface>
    where TEvent : TInterface
    where TInterface : IEvent
```

**Namespace**
* [Umbraco.Commerce.Core.Composing](README.md)

### Methods

#### RegisterHandler&lt;THandler&gt;

```csharp
public UmbracoCommerceEventHandlerComposer<TEvent, TInterface> RegisterHandler<THandler>()
    where THandler : IEventHandlerFor<TEvent>
```


---

#### RegisterHandlerAfter&lt;TAfterHandler,THandler&gt;

```csharp
public UmbracoCommerceEventHandlerComposer<TEvent, TInterface> 
    RegisterHandlerAfter<TAfterHandler, THandler>()
    where TAfterHandler : IEventHandlerFor<TEvent>
    where THandler : IEventHandlerFor<TEvent>
```


---

#### RegisterHandlerBefore&lt;TBeforeHandler,THandler&gt;

```csharp
public UmbracoCommerceEventHandlerComposer<TEvent, TInterface> 
    RegisterHandlerBefore<TBeforeHandler, THandler>()
    where TBeforeHandler : IEventHandlerFor<TEvent>
    where THandler : IEventHandlerFor<TEvent>
```


---

#### RemoveHandler&lt;THandler&gt;

```csharp
public UmbracoCommerceEventHandlerComposer<TEvent, TInterface> RemoveHandler<THandler>()
    where THandler : IEventHandlerFor<TEvent>
```


---

#### ReplaceHandler&lt;TReplacedHandler,THandler&gt;

```csharp
public UmbracoCommerceEventHandlerComposer<TEvent, TInterface> 
    ReplaceHandler<TReplacedHandler, THandler>()
    where TReplacedHandler : IEventHandlerFor<TEvent>
    where THandler : IEventHandlerFor<TEvent>
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->