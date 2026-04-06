# Tunneling Effect
> **Status:** Operational Engineering Protocol

---

## 🔗 Causal Chain (Minimal)
`2. Event` → `9. Process` → `8. System State` → `21. Measurement`

**Logic:** Cause → Mechanism → Effect → Practical Conclusion

---

## ⚡ Cause
**9. Process**

---

## ⚙️ Mechanism
* **`2. Event` → `9. Process`**
* **`7. System` → `8. System State`**
* **`20. Information` + `7. System` → `21. Measurement`**

Process defines a chain of possible events within a system state.
System State defines the set of admissible changes but does not fix a single realization.
Measurement fixes a realized event as information.

---

## 📡 Effect
* Between measurements, the process can realize an event not fixed by an intermediate measurement.
* **`21. Measurement`** fixes an already realized system state and does not constrain the process itself.



---

## 🛠 Practical Conclusion
**“Tunneling effect”** is realization of an event within **`9. Process`** outside intermediate **`21. Measurement`**.

**Engineering:**
* control is achieved through modification of **`8. System State`**
* increase of realization probability requires tuning of system state parameters
* suppression is achieved by introducing additional **`21. Measurement`**
* control is implemented through configuration of **`9. Process`** and conditions of state fixation
