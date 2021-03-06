[@redhat-cloud-services/remediations-client](../README.md) > [RemediationsApi](../classes/remediationsapi.md)

# Class: RemediationsApi

RemediationsApi - object-oriented interface

*__export__*: 

*__class__*: RemediationsApi

*__extends__*: {BaseAPI}

## Hierarchy

 [BaseAPI](baseapi.md)

**↳ RemediationsApi**

## Index

### Constructors

* [constructor](remediationsapi.md#constructor)

### Properties

* [axios](remediationsapi.md#axios)
* [basePath](remediationsapi.md#basepath)
* [configuration](remediationsapi.md#configuration)

### Methods

* [createRemediation](remediationsapi.md#createremediation)
* [deleteRemediation](remediationsapi.md#deleteremediation)
* [deleteRemediationIssue](remediationsapi.md#deleteremediationissue)
* [deleteRemediationIssueSystem](remediationsapi.md#deleteremediationissuesystem)
* [getRemediation](remediationsapi.md#getremediation)
* [getRemediationPlaybook](remediationsapi.md#getremediationplaybook)
* [getRemediations](remediationsapi.md#getremediations)
* [updateRemediation](remediationsapi.md#updateremediation)
* [updateRemediationIssue](remediationsapi.md#updateremediationissue)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new RemediationsApi**(configuration?: *[Configuration](configuration.md)*, basePath?: *`string`*, axios?: *`AxiosInstance`*): [RemediationsApi](remediationsapi.md)

*Inherited from [BaseAPI](baseapi.md).[constructor](baseapi.md#constructor)*

*Defined in [api.ts:49](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L49)*

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| `Optional` configuration | [Configuration](configuration.md) | - |
| `Default value` basePath | `string` |  BASE_PATH |
| `Default value` axios | `AxiosInstance` |  globalAxios |

**Returns:** [RemediationsApi](remediationsapi.md)

___

## Properties

<a id="axios"></a>

### `<Protected>` axios

**● axios**: *`AxiosInstance`*

*Inherited from [BaseAPI](baseapi.md).[axios](baseapi.md#axios)*

*Defined in [api.ts:51](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L51)*

___
<a id="basepath"></a>

### `<Protected>` basePath

**● basePath**: *`string`*

*Inherited from [BaseAPI](baseapi.md).[basePath](baseapi.md#basepath)*

*Defined in [api.ts:51](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L51)*

___
<a id="configuration"></a>

### `<Protected>` configuration

**● configuration**: *[Configuration](configuration.md) \| `undefined`*

*Inherited from [BaseAPI](baseapi.md).[configuration](baseapi.md#configuration)*

*Defined in [api.ts:49](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L49)*

___

## Methods

<a id="createremediation"></a>

###  createRemediation

▸ **createRemediation**(remediationInput: *[RemediationInput](../interfaces/remediationinput.md)*, options?: *`any`*): `AxiosPromise`<[RemediationCreated](../interfaces/remediationcreated.md)>

*Defined in [api.ts:1586](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L1586)*

Creates a new Remediation based on given information

*__summary__*: Create Remediation

*__throws__*: {RequiredError}

*__memberof__*: RemediationsApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| remediationInput | [RemediationInput](../interfaces/remediationinput.md) |  \- |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<[RemediationCreated](../interfaces/remediationcreated.md)>

___
<a id="deleteremediation"></a>

###  deleteRemediation

▸ **deleteRemediation**(id: *`string`*, options?: *`any`*): `AxiosPromise`<`Response`>

*Defined in [api.ts:1598](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L1598)*

Removes the given Remediation

*__summary__*: Remove Remediation

*__throws__*: {RequiredError}

*__memberof__*: RemediationsApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| id | `string` |  Remediation identifier |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<`Response`>

___
<a id="deleteremediationissue"></a>

###  deleteRemediationIssue

▸ **deleteRemediationIssue**(id: *`string`*, issue: *`string`*, options?: *`any`*): `AxiosPromise`<`Response`>

*Defined in [api.ts:1611](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L1611)*

Removes the given Issue from the Remediation

*__summary__*: Remove Remediation Issue

*__throws__*: {RequiredError}

*__memberof__*: RemediationsApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| id | `string` |  Remediation identifier |
| issue | `string` |  Issue identifier (e.g. &#x60;advisor:CVE\_2017\_6074\_kernel\|KERNEL\_CVE\_2017\_6074&#x60;) |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<`Response`>

___
<a id="deleteremediationissuesystem"></a>

###  deleteRemediationIssueSystem

▸ **deleteRemediationIssueSystem**(id: *`string`*, issue: *`string`*, system: *`string`*, options?: *`any`*): `AxiosPromise`<`Response`>

*Defined in [api.ts:1625](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L1625)*

Removes the given System from the Issue Remediation

*__summary__*: Remove Remediation Issue System

*__throws__*: {RequiredError}

*__memberof__*: RemediationsApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| id | `string` |  Remediation identifier |
| issue | `string` |  Issue identifier (e.g. &#x60;advisor:CVE\_2017\_6074\_kernel\|KERNEL\_CVE\_2017\_6074&#x60;) |
| system | `string` |  System identifier |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<`Response`>

___
<a id="getremediation"></a>

###  getRemediation

▸ **getRemediation**(id: *`string`*, options?: *`any`*): `AxiosPromise`<[RemediationDetails](../interfaces/remediationdetails.md)>

*Defined in [api.ts:1637](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L1637)*

Provides information about the given Remediation

*__summary__*: Get Remediation

*__throws__*: {RequiredError}

*__memberof__*: RemediationsApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| id | `string` |  Remediation identifier |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<[RemediationDetails](../interfaces/remediationdetails.md)>

___
<a id="getremediationplaybook"></a>

###  getRemediationPlaybook

▸ **getRemediationPlaybook**(id: *`string`*, options?: *`any`*): `AxiosPromise`<`string`>

*Defined in [api.ts:1649](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L1649)*

Provides Ansible Playbook

*__summary__*: Get Remediation Playbook

*__throws__*: {RequiredError}

*__memberof__*: RemediationsApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| id | `string` |  Remediation identifier |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<`string`>

___
<a id="getremediations"></a>

###  getRemediations

▸ **getRemediations**(sort?: *"updated_at" \| "-updated_at" \| "name" \| "-name" \| "system_count" \| "-system_count" \| "issue_count" \| "-issue_count"*, filter?: *`string`*, limit?: *`number`*, offset?: *`number`*, system?: *`string`*, options?: *`any`*): `AxiosPromise`<[RemediationList](../interfaces/remediationlist.md)>

*Defined in [api.ts:1665](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L1665)*

Provides information about Remediations

*__summary__*: List Remediations

*__throws__*: {RequiredError}

*__memberof__*: RemediationsApi

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` sort | "updated_at" \| "-updated_at" \| "name" \| "-name" \| "system_count" \| "-system_count" \| "issue_count" \| "-issue_count" |
| `Optional` filter | `string` |
| `Optional` limit | `number` |
| `Optional` offset | `number` |
| `Optional` system | `string` |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<[RemediationList](../interfaces/remediationlist.md)>

___
<a id="updateremediation"></a>

###  updateRemediation

▸ **updateRemediation**(id: *`string`*, remediationInput: *[RemediationInput](../interfaces/remediationinput.md)*, options?: *`any`*): `AxiosPromise`<`Response`>

*Defined in [api.ts:1678](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L1678)*

Updates the given Remediation

*__summary__*: Update Remediation

*__throws__*: {RequiredError}

*__memberof__*: RemediationsApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| id | `string` |  Remediation identifier |
| remediationInput | [RemediationInput](../interfaces/remediationinput.md) |  \- |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<`Response`>

___
<a id="updateremediationissue"></a>

###  updateRemediationIssue

▸ **updateRemediationIssue**(id: *`string`*, issue: *`string`*, remediationIssueIn: *[RemediationIssueIn](../interfaces/remediationissuein.md)*, options?: *`any`*): `AxiosPromise`<`Response`>

*Defined in [api.ts:1692](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L1692)*

Updates the given Remediation Issue

*__summary__*: Update Remediation Issue

*__throws__*: {RequiredError}

*__memberof__*: RemediationsApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| id | `string` |  Remediation identifier |
| issue | `string` |  Issue identifier (e.g. &#x60;advisor:CVE\_2017\_6074\_kernel\|KERNEL\_CVE\_2017\_6074&#x60;) |
| remediationIssueIn | [RemediationIssueIn](../interfaces/remediationissuein.md) |  \- |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<`Response`>

___

