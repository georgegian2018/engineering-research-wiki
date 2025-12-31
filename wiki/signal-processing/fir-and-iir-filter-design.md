← Back to [Engineering Research Wiki](../../README.md)

# FIR and IIR Filter Design

**Page ID:** DSP-FILTER-001  
**Author:** [Your Name]  
**Last Updated:** YYYY-MM-DD  
**Status:** Draft  
**Tags:** Signal Processing, Filters, FIR, IIR, DSP, MATLAB

---

## 1. Overview

This page provides an engineering-focused summary of Finite Impulse Response (FIR)
and Infinite Impulse Response (IIR) filters, including design tradeoffs,
stability considerations, and application scenarios.

---

## 2. FIR Filters

- Always stable  
- Linear phase (easy to achieve)  
- Longer length for sharp transitions  
- Implemented via convolution  

---

## 3. IIR Filters

- Recursive implementation  
- Efficient for sharp cutoff  
- Potential stability issues  
- Phase distortion unless corrected  

---

## 4. Design Techniques

- Windowing (FIR)  
- Parks-McClellan (FIR)  
- Butterworth / Chebyshev / Elliptic (IIR)  
- Bilinear transformation (IIR)  

---

## 5. Comparison Table

| Property | FIR | IIR |
|----------|-----|-----|
| Stability | Always stable | May be unstable |
| Phase | Linear (easy) | Nonlinear |
| Efficiency | Lower | Higher |
| Implementation | Non-recursive | Recursive |

---

## 6. References

- A. Oppenheim, *Discrete-Time Signal Processing*  
- MATLAB `fdatool`, `designfilt`  
- IEEE Transactions on Signal Processing  

---

## 7. Notes and Future Work

- Add sample code in Python (scipy.signal)  
- Include frequency response plots  
- Expand to multirate and adaptive filters  
