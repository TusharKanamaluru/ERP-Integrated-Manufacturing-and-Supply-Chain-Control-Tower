# Inventory Optimization

## Objective

The objective of this module is to determine inventory policies that balance material availability and inventory carrying costs within a high-precision machining environment.

The analysis was conducted using the material master data and supplier lead-time information contained in the `data` folder.

---

## Methodology

Inventory parameters were estimated using:

- Economic Order Quantity (EOQ)
- Safety Stock
- Reorder Point Planning

These methods were used to support replenishment decisions for raw materials, bought-out components, consumables, and tooling.

---

## Analysis Results

| Material | EOQ | Safety Stock | Reorder Point |
|-----------|-----------:|-----------:|-----------:|
| EN8 Round Bar | 180 | 35 | 70 |
| EN24 Steel Rod | 140 | 30 | 60 |
| Bearing Assembly | 320 | 45 | 90 |
| Carbide Inserts | 700 | 80 | 150 |
| Linear Guideways | 25 | 8 | 15 |
| Pneumatic Fittings | 120 | 25 | 50 |
| Solid Carbide End Mill | 45 | 10 | 20 |
| Fasteners | 1500 | 100 | 200 |
| Coolant Fluid | 80 | 15 | 30 |
| Inspection Gauges | 15 | 4 | 8 |

---

## Key Findings

### High Consumption Materials

Fasteners and Carbide Inserts account for the highest annual consumption volumes and therefore require tighter inventory control policies.

### Long Lead-Time Components

Linear Guideways and Bearing Assemblies exhibit longer supplier lead times, increasing inventory planning risk.

### Critical Production Inputs

Steel stock, tooling, and bearings are identified as critical production inputs due to their direct impact on machining operations.

---

## Recommendations

- Maintain safety stock policies for imported components.
- Review reorder points quarterly based on demand fluctuations.
- Monitor supplier lead-time performance to reduce inventory buffers.
- Prioritize inventory visibility for critical production materials.

---

## Conclusion

The inventory optimization framework provides a structured approach for balancing service levels, inventory investment, and supply risk within a manufacturing environment.
