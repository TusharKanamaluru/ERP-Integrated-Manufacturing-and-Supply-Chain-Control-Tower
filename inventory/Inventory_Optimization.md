# Inventory Optimization

## Objective

The objective of this module is to determine optimal inventory policies that minimize total inventory cost while maintaining desired service levels.

The analysis focuses on three key inventory management techniques:

- Economic Order Quantity (EOQ)
- Safety Stock
- Reorder Point Planning

---

## Dataset

The analysis was conducted on a sample manufacturing dataset containing ten representative stock-keeping units (SKUs).

| SKU | Category | Annual Demand |
|------|------|------:|
| P001 | Motor | 1200 |
| P002 | Gearbox | 800 |
| P003 | Bearing | 5000 |
| P004 | Shaft | 2000 |
| P005 | Housing | 1000 |
| P006 | Bracket | 3500 |
| P007 | Wheel | 1500 |
| P008 | Sensor | 900 |
| P009 | Controller | 600 |
| P010 | Fastener | 15000 |

---

## Results

| SKU | EOQ | Safety Stock | Reorder Point |
|------|------:|------:|------:|
| P001 | 283 | 55 | 101 |
| P002 | 155 | 48 | 94 |
| P003 | 1224 | 96 | 192 |
| P004 | 529 | 72 | 127 |
| P005 | 258 | 38 | 76 |
| P006 | 935 | 48 | 96 |
| P007 | 274 | 74 | 148 |
| P008 | 235 | 41 | 78 |
| P009 | 130 | 39 | 71 |
| P010 | 6708 | 123 | 246 |

---

## Key Observations

- High-volume items such as Fasteners and Bearings benefit significantly from optimized order quantities.
- Safety stock requirements vary based on demand patterns and supplier lead times.
- Inventory policies can reduce stockout risk while controlling carrying costs.
- Data-driven replenishment policies improve inventory visibility and planning accuracy.

---

## Conclusion

The inventory optimization module demonstrates how structured inventory planning can balance service levels, ordering costs, and inventory holding costs within a manufacturing environment.
