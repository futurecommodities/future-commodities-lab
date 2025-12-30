# Physical Commodity Trade Lifecycle (End-to-End)

This document explains the **standard lifecycle of a physical commodity trade**, from first contact to final settlement and claims.  
It is written to be **product-agnostic** (energy, metals, agriculture) and focuses on **process, control points, and risks**, not legal advice.

---

## 1. Market Initiation and Deal Origination

### Objective  
Identify a commercial opportunity and validate that a deal is feasible.

### Typical Triggers
- Buyer inquiry (spot or term)
- Seller offer / indication
- Arbitrage opportunity (location, time, quality)
- Physical exposure created by upstream/downstream commitments

### Key Actions
- Confirm product availability and specifications
- Check preliminary price reference (index, futures curve, assessments)
- Validate logistics feasibility (ports, storage, transport)
- Conduct **initial counterparty screening** (sanctions, reputation)

### Key Risks
- Trading with non-viable counterparties
- Quoting before logistics or quality constraints are understood
- Price exposure before hedge is in place

---

## 2. Commercial Negotiation

### Objective  
Agree on economic and operational terms.

### Core Commercial Terms
- Product and quality specification
- Quantity and tolerance
- Pricing mechanism (fixed, index-linked, formula)
- Delivery terms (Incoterms)
- Delivery window or laycan
- Payment terms

### Supporting Discussions
- Inspection and sampling method
- Title and risk transfer point
- Demurrage/despatch responsibility
- Governing law and arbitration

### Key Risks
- Ambiguous specifications
- Misaligned Incoterms and payment terms
- Hidden optionality (delivery windows, pricing periods)

---

## 3. Contract Formation

### Objective  
Convert negotiated terms into a legally binding agreement.

### Common Contract Types
- Master agreement + confirmation
- Standalone spot contract
- Term contract with lifting schedules

### Key Documents
- Contract / confirmation
- Annexes (specs, pricing formula, delivery terms)

### Control Checks
- Legal approval (where applicable)
- Credit approval and limits
- Alignment with internal trading policy

### Key Risks
- Inconsistent clauses across documents
- Missing force majeure or quality clauses
- Mismatch between commercial intent and legal wording

---

## 4. Pre-Shipment Execution

### Objective  
Prepare the cargo for physical delivery.

### Typical Activities
- Nomination of load/discharge ports
- Vessel nomination or booking
- Storage and inventory allocation
- Pre-shipment inspection scheduling
- Issuance of shipping instructions

### Documentation Preparation
- Commercial invoice
- Packing list
- Certificate of origin (if required)
- Inspection instructions

### Key Risks
- Late nominations
- Incorrect shipping instructions
- Misalignment between physical schedule and hedge timing

---

## 5. Shipment and Delivery

### Objective  
Physically move the commodity and transfer risk/title as agreed.

### During Shipment
- Cargo loading and quantity determination
- Issuance of transport documents (e.g., Bill of Lading)
- Monitoring delays, weather, congestion
- Managing laytime and demurrage exposure

### Delivery Completion
- Discharge confirmation
- Final quantity and quality determination
- Risk and title transfer (per contract)

### Key Risks
- Quantity loss or contamination
- Demurrage disputes
- Force majeure events

---

## 6. Pricing Finalization

### Objective  
Determine final contract price.

### Pricing Scenarios
- Fixed price: known at contract signing
- Index-linked: finalized after pricing period
- Formula pricing: dependent on multiple inputs

### Key Inputs
- Price index or futures settlement
- FX rate (if applicable)
- Quality adjustments or penalties

### Key Risks
- Incorrect pricing period
- Data source disputes
- Hedge mismatch vs pricing exposure

---

## 7. Invoicing and Payment

### Objective  
Settle the transaction financially.

### Invoicing
- Provisional invoice (if applicable)
- Final invoice after pricing and inspection
- Supporting documents submission

### Payment Methods
- Letter of Credit
- Documentary collection (DP/DA)
- Open account
- Prepayment

### Key Risks
- Documentation discrepancies
- Delayed payment
- Bank or country risk

---

## 8. Post-Delivery Claims and Reconciliation

### Objective  
Resolve discrepancies and close the trade.

### Typical Claims
- Quantity shortage
- Quality deviation
- Demurrage/despatch
- Late delivery

### Process
- Claim notification within contract time bar
- Evidence collection (inspection reports, logs)
- Commercial negotiation or arbitration

### Key Risks
- Missed claim deadlines
- Insufficient documentation
- Prolonged disputes tying up capital

---

## 9. Hedge Close-Out and PnL Attribution

### Objective  
Finalize economic outcome of the trade.

### Activities
- Close futures or OTC hedges
- Reconcile physical vs paper PnL
- Attribute PnL to:
  - Flat price
  - Basis
  - Timing
  - Logistics
  - Operational effects

### Key Risks
- Unrecognized basis loss
- Misattributed PnL masking operational issues

---

## 10. Trade Close and Review

### Objective  
Formally close the transaction and capture lessons learned.

### Final Steps
- Trade status closed in systems
- Credit exposure released
- Documentation archived

### Post-Trade Review
- What worked as expected?
- What risks materialized?
- What should be changed next time?

This step is critical for **organizational learning** and continuous improvement.

---

## Summary

A physical commodity trade is not a single decision but a **chain of tightly coupled steps**.  
Risk is rarely concentrated in price alone. It accumulates across **logistics, documentation, credit, timing, and execution**.

Understanding the full lifecycle is essential before attempting to optimize or automate any single component.

---

## Next Documents
- `01_incoterms_payment.md`
- `02_shipping_chartering.md`
- `04_hedging_basics.md`

