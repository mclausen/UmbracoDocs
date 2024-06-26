---
title: IStoreService
description: API reference for IStoreService in Umbraco Commerce
---
## IStoreService

Define the Store service

```csharp
public interface IStoreService : ICachedEntityService<StoreReadOnly>, IService
```

**Inheritance**

* interface [ICachedEntityService&lt;TEntityType&gt;](icachedentityservice-1.md)
* interface [IService](iservice.md)

**Namespace**
* [Umbraco.Commerce.Core.Services](README.md)

### Methods

#### DeleteStore (1 of 2)

Deletes an [`Store`](../umbraco-commerce-core-models/store.md)

```csharp
public void DeleteStore(Guid id)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| id | The ID of the [`Store`](../umbraco-commerce-core-models/store.md) to delete |

---

#### DeleteStore (2 of 2)

Deletes an [`Store`](../umbraco-commerce-core-models/store.md)

```csharp
public void DeleteStore(Store entity)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| entity | The [`Store`](../umbraco-commerce-core-models/store.md) to delete |


---

#### GetStore (1 of 2)

Get an [`StoreReadOnly`](../umbraco-commerce-core-models/storereadonly.md) entity by ID

```csharp
public StoreReadOnly GetStore(Guid id)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| id | The ID of the [`StoreReadOnly`](../umbraco-commerce-core-models/storereadonly.md) entity to fetch |

**Returns**

An [`StoreReadOnly`](../umbraco-commerce-core-models/storereadonly.md) entity

---

#### GetStore (2 of 2)

Get an [`StoreReadOnly`](../umbraco-commerce-core-models/storereadonly.md) entity by Alias

```csharp
public StoreReadOnly GetStore(string alias)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| alias | The Alias of the [`StoreReadOnly`](../umbraco-commerce-core-models/storereadonly.md) entity to fetch |

**Returns**

An [`StoreReadOnly`](../umbraco-commerce-core-models/storereadonly.md) entity


---

#### GetStores

Get a list of all [`StoreReadOnly`](../umbraco-commerce-core-models/storereadonly.md) entities

```csharp
public IEnumerable<StoreReadOnly> GetStores()
```

**Returns**

A list of [`StoreReadOnly`](../umbraco-commerce-core-models/storereadonly.md) entities


---

#### GetStores

Get a list of [`StoreReadOnly`](../umbraco-commerce-core-models/storereadonly.md) entities with the given IDs

```csharp
public IEnumerable<StoreReadOnly> GetStores(Guid[] ids)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| ids | The IDs of the [`StoreReadOnly`](../umbraco-commerce-core-models/storereadonly.md) entities to fetch |

**Returns**

A list of [`StoreReadOnly`](../umbraco-commerce-core-models/storereadonly.md) entities


---

#### SaveStore

Saves an [`Store`](../umbraco-commerce-core-models/store.md)

```csharp
public void SaveStore(Store entity)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| entity | The [`Store`](../umbraco-commerce-core-models/store.md) to save |


---

#### SortStores

Sorts a list of [`Store`](../umbraco-commerce-core-models/store.md) entities by ID according to the order of those IDs

```csharp
public void SortStores(Guid[] sortedIds)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| sortedIds | The IDs of the [`Store`](../umbraco-commerce-core-models/store.md) entities to sort, in the order by which to sort them |


---

#### StoreExists

Check to see if a [`StoreReadOnly`](../umbraco-commerce-core-models/storereadonly.md) exists with the given Alias

```csharp
public bool StoreExists(string alias)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| alias | The Alias of the [`StoreReadOnly`](../umbraco-commerce-core-models/storereadonly.md) entity to check |

**Returns**

Returns `true` if the [`StoreReadOnly`](../umbraco-commerce-core-models/storereadonly.md) exists, otherwise returns `false`.


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
