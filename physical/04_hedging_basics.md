# Hedging Basics in Physical Commodity Trading

This document explains the **purpose, mechanics, and limitations of hedging** in physical commodity trading.

Hedging is not about eliminating risk. It is about **transforming risk into a form the desk can survive and manage**.

---

## 1. Why Physical Trades Need Hedging

A physical trade creates **price exposure over time**:
- Between contract signing and delivery
- Between delivery and pricing finalization
- Between inventory receipt and sale

During this time, market prices can move materially.

Without hedging, a trader is implicitly betting that:
- Market prices will not move against the position, or
- Operational execution will be perfect

Both assumptions are unsafe.

---

## 2. What Hedging Does (and Does Not Do)

### What Hedging Does
- Offsets **flat price risk**
- Reduces PnL volatility
- Protects margin and working capital

### What Hedging Does NOT Do
- Eliminate basis risk
- Protect against operational failures
- Guarantee profit
- Replace commercial judgment

Hedging converts **market risk** into **basis and execution risk**.

---

## 3. Identifying the Physical Exposure

Before hedging, the exposure must be defined precisely.

Key questions:
- Are you **long or short** the commodity?
- What is the **volume**?
- Over what **time window** does exposure exist?
- At what **pricing reference** will the trade be settled?

A hedge without a clearly defined exposure is speculation.

---

## 4. Common Hedging Instruments

### Exchange-Traded Futures
- Standardized contracts
- Transparent pricing
- Daily margining

Used when:
- Physical product closely matches futures contract
- Liquidity is sufficient

---

### OTC Swaps
- Customized pricing and tenors
- Settled financially

Used when:
- Physical exposure does not align perfectly with futures
- Credit relationships allow bilateral trading

---

### Options
- Provide asymmetric protection
- Require upfront premium

Used when:
- Downside protection is needed
- Upside participation is desired

---

## 5. Basic Hedge Structures

### Flat Price Hedge

The simplest hedge:
- Buy physical → sell futures
- Sell physical → buy futures

Objective:
Neutralize outright price movements.

```mermaid
flowchart LR
  P[Physical Position] -->|Price Exposure| M[Market Price]
  H[Paper Hedge] -->|Offset| M
