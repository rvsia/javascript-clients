[@redhat-cloud-services/sources-client](../README.md) > [InlineObject](../interfaces/inlineobject.md)

# Interface: InlineObject

*__export__*: 

*__interface__*: InlineObject

## Hierarchy

**InlineObject**

## Index

### Properties

* [operationName](inlineobject.md#operationname)
* [query](inlineobject.md#query)
* [variables](inlineobject.md#variables)

---

## Properties

<a id="operationname"></a>

### `<Optional>` operationName

**● operationName**: *`string`*

*Defined in [api.ts:501](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/sources/api.ts#L501)*

If the Query contains several named operations, the operationName controls which one should be executed

*__type__*: {string}

*__memberof__*: InlineObject

___
<a id="query"></a>

###  query

**● query**: *`string`*

*Defined in [api.ts:495](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/sources/api.ts#L495)*

The GraphQL query

*__type__*: {string}

*__memberof__*: InlineObject

___
<a id="variables"></a>

### `<Optional>` variables

**● variables**: *`any`*

*Defined in [api.ts:507](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/sources/api.ts#L507)*

Optional Query variables

*__type__*: {any}

*__memberof__*: InlineObject

___
