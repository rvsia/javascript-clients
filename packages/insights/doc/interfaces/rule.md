[@redhat-cloud-services/insights-client](../README.md) > [Rule](../interfaces/rule.md)

# Interface: Rule

*__export__*: 

*__interface__*: Rule

## Hierarchy

**Rule**

## Index

### Properties

* [active](rule.md#active)
* [category](rule.md#category)
* [createdAt](rule.md#createdat)
* [deletedAt](rule.md#deletedat)
* [description](rule.md#description)
* [generic](rule.md#generic)
* [impact](rule.md#impact)
* [likelihood](rule.md#likelihood)
* [moreInfo](rule.md#moreinfo)
* [nodeId](rule.md#nodeid)
* [publishDate](rule.md#publishdate)
* [reason](rule.md#reason)
* [rebootRequired](rule.md#rebootrequired)
* [resolutionSet](rule.md#resolutionset)
* [ruleId](rule.md#ruleid)
* [ruleset](rule.md#ruleset)
* [summary](rule.md#summary)
* [tags](rule.md#tags)
* [totalRisk](rule.md#totalrisk)
* [updatedAt](rule.md#updatedat)

---

## Properties

<a id="active"></a>

### `<Optional>` active

**● active**: *`boolean`*

*Defined in [api.ts:359](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L359)*

*__type__*: {boolean}

*__memberof__*: Rule

___
<a id="category"></a>

###  category

**● category**: *[RuleCategory](rulecategory.md)*

*Defined in [api.ts:365](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L365)*

*__type__*: {RuleCategory}

*__memberof__*: Rule

___
<a id="createdat"></a>

### `<Optional>` createdAt

**● createdAt**: *`Date`*

*Defined in [api.ts:329](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L329)*

*__type__*: {Date}

*__memberof__*: Rule

___
<a id="deletedat"></a>

### `<Optional>` deletedAt

**● deletedAt**: *`Date`*

*Defined in [api.ts:341](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L341)*

*__type__*: {Date}

*__memberof__*: Rule

___
<a id="description"></a>

###  description

**● description**: *`string`*

*Defined in [api.ts:353](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L353)*

*__type__*: {string}

*__memberof__*: Rule

___
<a id="generic"></a>

###  generic

**● generic**: *`string`*

*Defined in [api.ts:413](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L413)*

*__type__*: {string}

*__memberof__*: Rule

___
<a id="impact"></a>

###  impact

**● impact**: *[RuleImpact](ruleimpact.md)*

*Defined in [api.ts:371](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L371)*

*__type__*: {RuleImpact}

*__memberof__*: Rule

___
<a id="likelihood"></a>

### `<Optional>` likelihood

**● likelihood**: *`number`*

*Defined in [api.ts:377](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L377)*

*__type__*: {number}

*__memberof__*: Rule

___
<a id="moreinfo"></a>

### `<Optional>` moreInfo

**● moreInfo**: *`string`*

*Defined in [api.ts:425](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L425)*

*__type__*: {string}

*__memberof__*: Rule

___
<a id="nodeid"></a>

### `<Optional>` nodeId

**● nodeId**: *`string`*

*Defined in [api.ts:383](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L383)*

*__type__*: {string}

*__memberof__*: Rule

___
<a id="publishdate"></a>

### `<Optional>` publishDate

**● publishDate**: *`Date` \| `null`*

*Defined in [api.ts:401](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L401)*

*__type__*: {Date}

*__memberof__*: Rule

___
<a id="reason"></a>

###  reason

**● reason**: *`string`*

*Defined in [api.ts:419](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L419)*

*__type__*: {string}

*__memberof__*: Rule

___
<a id="rebootrequired"></a>

### `<Optional>` rebootRequired

**● rebootRequired**: *`boolean`*

*Defined in [api.ts:395](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L395)*

*__type__*: {boolean}

*__memberof__*: Rule

___
<a id="resolutionset"></a>

###  resolutionSet

**● resolutionSet**: *`Array`<[Resolution](resolution.md)>*

*Defined in [api.ts:431](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L431)*

*__type__*: {Array}

*__memberof__*: Rule

___
<a id="ruleid"></a>

###  ruleId

**● ruleId**: *`string`*

*Defined in [api.ts:323](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L323)*

Rule ID from Insights

*__type__*: {string}

*__memberof__*: Rule

___
<a id="ruleset"></a>

###  ruleset

**● ruleset**: *[RuleSet](ruleset.md)*

*Defined in [api.ts:347](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L347)*

*__type__*: {RuleSet}

*__memberof__*: Rule

___
<a id="summary"></a>

###  summary

**● summary**: *`string`*

*Defined in [api.ts:407](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L407)*

*__type__*: {string}

*__memberof__*: Rule

___
<a id="tags"></a>

### `<Optional>` tags

**● tags**: *`string`*

*Defined in [api.ts:389](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L389)*

*__type__*: {string}

*__memberof__*: Rule

___
<a id="totalrisk"></a>

### `<Optional>` totalRisk

**● totalRisk**: *`number`*

*Defined in [api.ts:437](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L437)*

*__type__*: {number}

*__memberof__*: Rule

___
<a id="updatedat"></a>

### `<Optional>` updatedAt

**● updatedAt**: *`Date`*

*Defined in [api.ts:335](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L335)*

*__type__*: {Date}

*__memberof__*: Rule

___

