[@redhat-cloud-services/catalog-client](../README.md) > [ApprovalRequest](../modules/approvalrequest.md)

# Module: ApprovalRequest

*__export__*: 

*__namespace__*: ApprovalRequest

## Index

### Enumerations

* [StateEnum](../enums/approvalrequest.stateenum.md)

### Properties

* [approvalRequestRef](approvalrequest.md#approvalrequestref)
* [id](approvalrequest.md#id)
* [orderItemId](approvalrequest.md#orderitemid)
* [reason](approvalrequest.md#reason)
* [state](approvalrequest.md#state)
* [workflowRef](approvalrequest.md#workflowref)

---

## Properties

<a id="approvalrequestref"></a>

### `<Optional>` approvalRequestRef

**● approvalRequestRef**: *`string`*

*Defined in [api.ts:117](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L117)*

The id of the approval submitted to approval-api

*__type__*: {string}

*__memberof__*: ApprovalRequest

___
<a id="id"></a>

### `<Optional>` id

**● id**: *`string`*

*Defined in [api.ts:111](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L111)*

The unique identifier for this approval request.

*__type__*: {string}

*__memberof__*: ApprovalRequest

___
<a id="orderitemid"></a>

### `<Optional>` orderItemId

**● orderItemId**: *`string`*

*Defined in [api.ts:123](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L123)*

The Order Item which the approval request belongs to

*__type__*: {string}

*__memberof__*: ApprovalRequest

___
<a id="reason"></a>

### `<Optional>` reason

**● reason**: *`string`*

*Defined in [api.ts:129](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L129)*

The reason for the current state.

*__type__*: {string}

*__memberof__*: ApprovalRequest

___
<a id="state"></a>

### `<Optional>` state

**● state**: *[StateEnum](../enums/approvalrequest.stateenum.md)*

*Defined in [api.ts:135](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L135)*

The state of the approval request (approved, denied, undecided, canceled)

*__type__*: {string}

*__memberof__*: ApprovalRequest

___
<a id="workflowref"></a>

### `<Optional>` workflowRef

**● workflowRef**: *`string`*

*Defined in [api.ts:141](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L141)*

The workflow that was requested

*__type__*: {string}

*__memberof__*: ApprovalRequest

___

