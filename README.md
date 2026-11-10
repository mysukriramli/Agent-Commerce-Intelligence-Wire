# Agent Commerce Intelligence Wire

ACIW is an open commerce intelligence layer designed for AI agents.

The project normalizes public commerce data into machine-readable feeds.

Agents can answer:

- What product is this?
- Is the product safe?
- Is this a fair price?
- Can this seller be trusted?
- Will delivery be delayed?
- Is inventory increasing or shrinking?
- How does this compare to historical procurement prices?

## Modules

### Product Identity Wire

Maps:

- GTIN
- UPC
- EAN
- Manufacturer SKU

into a canonical product identity.

### Recall Wire

Tracks official product recalls.

Sources:

- CPSC
- FDA
- Safety Gate
- NHTSA

### Price Reality Wire

Tracks market prices.

### Merchant Trust Wire

Tracks merchant reliability.

### Delivery Reality Wire

Tracks expected logistics delays.

### Procurement Benchmark Wire

Tracks historical procurement price distributions.

### Inventory Signal Wire

Tracks inventory-related supply signals.

## Agent Use Cases

- Shopping agents
- Procurement agents
- Supply chain agents
- Autonomous marketplaces
- Commerce copilots
