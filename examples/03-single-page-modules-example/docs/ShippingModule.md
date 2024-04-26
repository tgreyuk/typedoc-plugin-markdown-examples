**typedoc-plugin-markdown-examples** • [API](README.md)

***

[Home](README.md) / ShippingModule

# ShippingModule

This module contains types and services related to shipping.
It includes definitions for shipping records and services to manage the logistics of shipping orders.

## Classes

### ShippingService

Service for managing shipping records.
Provides methods to handle the logistics of order shipments, including recording and tracking shipments.

#### Constructors

##### new ShippingService()

```ts
new ShippingService(): ShippingService
```

###### Returns

[`ShippingService`](ShippingModule.md#shippingservice)

#### Properties

| Property | Modifier | Type | Default value | Description |
| :------ | :------ | :------ | :------ | :------ |
| `shipments` | `private` | [`ShippingRecord`](ShippingModule.md#shippingrecord)[] | `[]` | Stores all shipment records. This array acts as a database to keep track of all shipments handled by the service. |

#### Methods

##### getAllShipments()

```ts
getAllShipments(): ShippingRecord[]
```

Retrieves all shipping records managed by the service.
Useful for tracking, auditing, and providing customers with updates on their shipment statuses.

###### Returns

[`ShippingRecord`](ShippingModule.md#shippingrecord)[]

An array of all shipping records.

###### Source

shipping.ts:60

##### shipOrder()

```ts
shipOrder(shipment): ShippingRecord
```

Ships an order by creating a shipping record and adding it to the list of shipments.
This method simulates the action of shipping an order in a real-world scenario.

###### Parameters

| Parameter | Type | Description |
| :------ | :------ | :------ |
| `shipment` | [`ShippingRecord`](ShippingModule.md#shippingrecord) | The shipment record to be added. |

###### Returns

[`ShippingRecord`](ShippingModule.md#shippingrecord)

The shipment record that was added to the shipments list.

###### Source

shipping.ts:50

## Interfaces

### ShippingRecord

Interface representing a shipping record.
Defines the structure for storing and tracking information about shipments.

#### Properties

| Property | Type | Description |
| :------ | :------ | :------ |
| `address` | `string` | The destination address where the order should be delivered. This is crucial for logistics and routing. |
| `orderId` | `string` | Identifier for the order being shipped. Links the shipment to a specific customer order. |
| `shipmentId` | `string` | Unique identifier for the shipment. This is used to track and reference the shipment throughout the shipping process. |
| `status` | `string` | Current status of the shipment (e.g., "Pending", "Shipped", "Delivered"). Provides updates on the shipment progress. |