# 🧪 Simulations in Engineering

Overview of common simulation tools and environments used in engineering: signal processing, antennas, EM, thermal, and system modeling.

---

## 🧠 Tools by Domain

| Tool | Domain |
|------|--------|
| **MATLAB/Simulink** | Signals, systems, control |
| **CST Studio Suite** | Antennas, RF EM fields |
| **ANSYS HFSS** | High-frequency 3D EM |
| **LTspice** | Analog circuits |
| **COMSOL Multiphysics** | Multidomain physics |

---

## ✅ Example: MATLAB Signal Filter

```matlab
Fs = 1000;
t = 0:1/Fs:1;
x = sin(2*pi*50*t) + sin(2*pi*120*t);
y = lowpass(x, 80, Fs);
plot(t, y)
```
