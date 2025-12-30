# Shipping and Chartering in Physical Commodity Trading

This document explains the **shipping and chartering fundamentals** relevant to physical commodity trading.  
It focuses on **economic exposure, operational control points, and failure modes**, rather than maritime law.

For many desks, shipping is the **largest non-price risk** in a physical trade.

---

## 1. Why Shipping Matters More Than Most Traders Expect

Shipping affects:
- Delivered cost
- Timing of risk transfer
- Cash flow and working capital
- Demurrage and operational PnL volatility
- Hedge effectiveness

A profitable trade can become a loss **purely due to shipping execution**.

---

## 2. Shipping Responsibility by Incoterm (Context)

Before discussing chartering, always clarify:
- Who controls freight
- Who pays freight
- Who bears delay risk

Typical patterns:
- **FOB**: Buyer controls and pays freight
- **CFR / CIF**: Seller controls and pays freight
- **DAP / DDP**: Seller controls end-to-end logistics

Control over shipping usually implies **exposure to operational risk**.

---

## 3. Main Shipping Modes in Commodity Trading

### Bulk Shipping
Used for:
- Crude oil, products
- Coal
- Grain
- Ores and concentrates

Characteristics:
- Large parcel sizes
- Exposure to weather, congestion, draft restrictions
- Demurrage risk is material

---

### Containerized Shipping
Used for:
- Refined or packaged commodities
- Specialty chemicals
- Metals in smaller lots

Characteristics:
- Fixed schedules
- Lower volume per shipment
- Less demurrage risk, more schedule risk

---

### Inland Transport
Includes:
- Truck
- Rail
- Barge

Often underestimated but critical for:
- FOB positioning
- Delivered trades
- Last-mile bottlenecks

---

## 4. Chartering Basics: How Vessels Are Hired

Chartering is the process of **renting a vessel** to transport cargo.

There are two dominant charter types in commodity trading.

---

## 5. Voyage Charter

### What It Is
- Vessel hired for a **single voyage**
- Freight paid per ton or lump sum
- Owner retains operational control of the vessel

### Who Uses It
- Spot traders
- Desks with occasional freight exposure

### Cost Structure
- Freight
- Port costs (depending on terms)
- Demurrage / despatch

### Risk Profile
- Exposure to port delays
- Demurrage risk sits with charterer
- Limited upside from faster operations

```mermaid
flowchart LR
  T[Trader] -->|Voyage Charter| O[Ship Owner]
  O --> V[Vessel]
  V --> L[Load Port]
  V --> D[Discharge Port]

