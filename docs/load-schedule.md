# DB-01 Load Schedule

The table below transcribes the circuit loads and preliminary selections shown on the project's final drawing sheet (E-01).

| Circuit | Description | Connected load (W) | Current (A) on drawing | Cable on drawing | Breaker on drawing | Protection reference |
| --- | --- | ---: | ---: | --- | --- | --- |
| C1 | Lighting 1 | 36 | 0.16 | 3 × 2.5 mm² Cu | B10 A MCB | 30 mA RCBO |
| C2 | Lighting 2 | 36 | 0.16 | 3 × 2.5 mm² Cu | B10 A MCB | 30 mA RCBO |
| C3 | Bedroom sockets | 1,800 | 7.83 | 3 × 2.5 mm² Cu | B16 A MCB | 30 mA RCBO |
| C4 | Living room sockets | 1,200 | 5.22 | 3 × 2.5 mm² Cu | B16 A MCB | 30 mA RCBO |
| C5 | Kitchen worktop sockets | 600 | 2.61 | 3 × 2.5 mm² Cu | B16 A MCB | 30 mA RCBO |
| C6 | Refrigerator | 300 | 1.30 | 3 × 2.5 mm² Cu | B16 A MCB | 30 mA RCBO |
| C7 | Oven / hob | 3,500 | 15.22 | 3 × 4 mm² Cu | B20 A MCB | 30 mA RCBO |
| C8 | Extractor hood | 200 | 0.87 | 3 × 2.5 mm² Cu | B10 A MCB | 30 mA RCBO |
| **Total** | **Connected load** | **7,672** | **33.36 (unrounded calculation)** | — | — | — |

## Method

For the learning exercise, the nominal current was calculated as:

```text
I = P / V        (assuming single-phase, 230 V and power factor = 1)

I_total = 7,672 W / 230 V = 33.3565 A ≈ 33.36 A
I_C7    = 3,500 W / 230 V = 15.2174 A ≈ 15.22 A
```

Adding the **displayed two-decimal per-circuit currents** gives approximately **33.37 A** because of rounding, while dividing the total connected load by 230 V gives **33.36 A**. Neither is a demand-adjusted feeder design current.

## Interpretation of protection notation

The drawing includes both an **MCB rating** column and a **30 mA RCBO** column. This documentation retains those descriptions exactly as shown; the final intended protective-device assembly and RCD characteristics need to be verified before any real installation. A B-curve MCB characteristic must not be confused with the RCD residual-current **Type B** classification.

## Scope limitations

- Cable cross-sections are preliminary selections, not verified ampacity calculations.
- Installation method, current-carrying capacity, ambient temperature and grouping are unspecified.
- Voltage drop, earth-fault loop impedance, disconnection time, fault level and discrimination are not established.
- The supplied drawings are conceptual and not issued for construction.

[Return to project overview](../README.md)
