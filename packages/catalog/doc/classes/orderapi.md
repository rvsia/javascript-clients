[@redhat-cloud-services/catalog-client](../README.md) > [OrderApi](../classes/orderapi.md)

# Class: OrderApi

OrderApi - object-oriented interface

*__export__*: 

*__class__*: OrderApi

*__extends__*: {BaseAPI}

## Hierarchy

 [BaseAPI](baseapi.md)

**↳ OrderApi**

## Index

### Constructors

* [constructor](orderapi.md#constructor)

### Properties

* [axios](orderapi.md#axios)
* [basePath](orderapi.md#basepath)
* [configuration](orderapi.md#configuration)

### Methods

* [addToOrder](orderapi.md#addtoorder)
* [cancelOrder](orderapi.md#cancelorder)
* [createOrder](orderapi.md#createorder)
* [destroyOrder](orderapi.md#destroyorder)
* [listOrderItemsFromOrder](orderapi.md#listorderitemsfromorder)
* [listOrders](orderapi.md#listorders)
* [restoreOrder](orderapi.md#restoreorder)
* [showOrderItemFromOrder](orderapi.md#showorderitemfromorder)
* [submitOrder](orderapi.md#submitorder)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new OrderApi**(configuration?: *[Configuration](configuration.md)*, basePath?: *`string`*, axios?: *`AxiosInstance`*): [OrderApi](orderapi.md)

*Inherited from [BaseAPI](baseapi.md).[constructor](baseapi.md#constructor)*

*Defined in [api.ts:49](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L49)*

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| `Optional` configuration | [Configuration](configuration.md) | - |
| `Default value` basePath | `string` |  BASE_PATH |
| `Default value` axios | `AxiosInstance` |  globalAxios |

**Returns:** [OrderApi](orderapi.md)

___

## Properties

<a id="axios"></a>

### `<Protected>` axios

**● axios**: *`AxiosInstance`*

*Inherited from [BaseAPI](baseapi.md).[axios](baseapi.md#axios)*

*Defined in [api.ts:51](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L51)*

___
<a id="basepath"></a>

### `<Protected>` basePath

**● basePath**: *`string`*

*Inherited from [BaseAPI](baseapi.md).[basePath](baseapi.md#basepath)*

*Defined in [api.ts:51](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L51)*

___
<a id="configuration"></a>

### `<Protected>` configuration

**● configuration**: *[Configuration](configuration.md) \| `undefined`*

*Inherited from [BaseAPI](baseapi.md).[configuration](baseapi.md#configuration)*

*Defined in [api.ts:49](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L49)*

___

## Methods

<a id="addtoorder"></a>

###  addToOrder

▸ **addToOrder**(orderId: *`string`*, orderItem: *[OrderItem](../modules/orderitem.md)*, options?: *`any`*): `AxiosPromise`<`Response`>

*Defined in [api.ts:2423](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L2423)*

Adds an order item to an order in pending state

*__summary__*: Add an order item to an order in pending state

*__throws__*: {RequiredError}

*__memberof__*: OrderApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| orderId | `string` |  The Order ID |
| orderItem | [OrderItem](../modules/orderitem.md) |  \- |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<`Response`>

___
<a id="cancelorder"></a>

###  cancelOrder

▸ **cancelOrder**(orderId: *`string`*, options?: *`any`*): `AxiosPromise`<[Order](../modules/order.md)>

*Defined in [api.ts:2435](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L2435)*

Returns an updated order.

*__summary__*: Cancels a given order

*__throws__*: {RequiredError}

*__memberof__*: OrderApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| orderId | `string` |  The Order ID |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<[Order](../modules/order.md)>

___
<a id="createorder"></a>

###  createOrder

▸ **createOrder**(options?: *`any`*): `AxiosPromise`<[Order](../modules/order.md)>

*Defined in [api.ts:2446](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L2446)*

Creates a new order.

*__summary__*: Create a new order

*__throws__*: {RequiredError}

*__memberof__*: OrderApi

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<[Order](../modules/order.md)>

___
<a id="destroyorder"></a>

###  destroyOrder

▸ **destroyOrder**(id: *`string`*, options?: *`any`*): `AxiosPromise`<[RestoreKey](../interfaces/restorekey.md)>

*Defined in [api.ts:2458](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L2458)*

Deletes the Order based on order ID passed

*__summary__*: Delete an existing Order

*__throws__*: {RequiredError}

*__memberof__*: OrderApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| id | `string` |  ID of the resource |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<[RestoreKey](../interfaces/restorekey.md)>

___
<a id="listorderitemsfromorder"></a>

###  listOrderItemsFromOrder

▸ **listOrderItemsFromOrder**(orderId: *`string`*, limit?: *`number`*, offset?: *`number`*, filter?: *`any`*, options?: *`any`*): `AxiosPromise`<[OrderItemsCollection](../interfaces/orderitemscollection.md)>

*Defined in [api.ts:2473](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L2473)*

Gets a list of items associated with an order.

*__summary__*: Gets a list of items in a given order

*__throws__*: {RequiredError}

*__memberof__*: OrderApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| orderId | `string` |  The Order ID |
| `Optional` limit | `number` |
| `Optional` offset | `number` |
| `Optional` filter | `any` |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<[OrderItemsCollection](../interfaces/orderitemscollection.md)>

___
<a id="listorders"></a>

###  listOrders

▸ **listOrders**(limit?: *`number`*, offset?: *`number`*, filter?: *`any`*, options?: *`any`*): `AxiosPromise`<[OrdersCollection](../interfaces/orderscollection.md)>

*Defined in [api.ts:2487](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L2487)*

Gets a list of orders associated with the logged in user.

*__summary__*: Get a list of orders

*__throws__*: {RequiredError}

*__memberof__*: OrderApi

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` limit | `number` |
| `Optional` offset | `number` |
| `Optional` filter | `any` |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<[OrdersCollection](../interfaces/orderscollection.md)>

___
<a id="restoreorder"></a>

###  restoreOrder

▸ **restoreOrder**(id: *`string`*, restoreKey: *[RestoreKey](../interfaces/restorekey.md)*, options?: *`any`*): `AxiosPromise`<[Order](../modules/order.md)>

*Defined in [api.ts:2500](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L2500)*

Restores the order specified by the order ID.

*__summary__*: Restore specific Order

*__throws__*: {RequiredError}

*__memberof__*: OrderApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| id | `string` |  ID of the resource |
| restoreKey | [RestoreKey](../interfaces/restorekey.md) |  \- |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<[Order](../modules/order.md)>

___
<a id="showorderitemfromorder"></a>

###  showOrderItemFromOrder

▸ **showOrderItemFromOrder**(orderId: *`string`*, id: *`string`*, options?: *`any`*): `AxiosPromise`<[OrderItem](../modules/orderitem.md)>

*Defined in [api.ts:2513](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L2513)*

Gets an order item associated with an order.

*__summary__*: Gets an individual order item from a given order

*__throws__*: {RequiredError}

*__memberof__*: OrderApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| orderId | `string` |  The Order ID |
| id | `string` |  ID of the resource |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<[OrderItem](../modules/orderitem.md)>

___
<a id="submitorder"></a>

###  submitOrder

▸ **submitOrder**(orderId: *`string`*, options?: *`any`*): `AxiosPromise`<[Order](../modules/order.md)>

*Defined in [api.ts:2525](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L2525)*

Returns an updated order.

*__summary__*: Submit a given order

*__throws__*: {RequiredError}

*__memberof__*: OrderApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| orderId | `string` |  The Order ID |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<[Order](../modules/order.md)>

___

