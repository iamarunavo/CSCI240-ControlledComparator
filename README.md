## Project: 4-Bit Controlled Comparator  

### Overview
This project implements a **4-bit Controlled Comparator** in Logisim. The circuit compares two 4-bit binary numbers, `A` and `B`, and adjusts its interpretation of the numbers depending on the control signal `C`. The output indicates whether `A` is less than, equal to, or greater than `B`.

---

### Specifications

#### Inputs
- **A**: 4-bit binary number  
- **B**: 4-bit binary number  
- **C**: Control signal  
  - `C = 0`: Treats `A` and `B` as **unsigned binary**  
  - `C = 1`: Treats `A` and `B` as **2’s complement signed binary**  

Example:  
- `101` = 5 (unsigned)  
- `101` = -3 (signed, 2’s complement)  

#### Outputs
The comparator produces one active output at a time:  
- `<` : 1 if `A < B`  
- `=` : 1 if `A = B`  
- `>` : 1 if `A > B`  
