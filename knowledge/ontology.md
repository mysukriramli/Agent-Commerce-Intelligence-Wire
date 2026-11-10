# Commerce Ontology

Entities

- Product
- Merchant
- Brand
- Recall
- Shipment
- Category
- Procurement Contract
- Inventory Signal

Relationships

Product -> sold_by -> Merchant

Product -> manufactured_by -> Brand

Product -> affected_by -> Recall

Shipment -> affects -> Delivery

Inventory Signal -> affects -> Product

Contract -> purchases -> Product
