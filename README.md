# Group Members

| Name         | ID Number                | Contribution |
|-----------------|-----------------------|-------------|
| PIYUSH JAJRA       | 2021B4A72969H      | Implementation of Tomita's algorithm, Bron-Kerbosch's algorithm and Arboricity's algorithm |
| PRAKSHAAL VORA     | 2021B3A72967H      |Website building, Data Preprocessing and Report. 
| TANMAY AGARWAL     | 2021B3A73040H      |Implementation of Tomita's algorithm, Bron-Kerbosch's algorithm and Arboricity's algorithm |
| KUSH DESAI         | 2021B4A73158H      |Implementation of Tomita's algorithm, Bron-Kerbosch's algorithm and Arboricity's algorithm |
| JAI GUPTA         | 2021B5A73169H       |Website building, Data Preprocessing and Report. 

---
<br>

# ⚙️ Setup & Compilation

<br>

## Prerequisites
Ensure your system has the following:

- **Windows Operating System**
- **GCC Compiler** (`gcc` installed)

---

<br>

## Compilation and Execution

In all the below commands, make sure to **REPLACE** the `<input_file>` with the file name of the datasets as specified below:

| Dataset         | File Name                 |
|-----------------|---------------------------|
| Wiki-Vote       | `Wiki-Vote_processed.txt` |
| Email_Enron     | `Email-Enron_processed.txt` |
| as-Skitter      | `as-skitter_processed.txt`  |

---

<br>

### 1) For Tomita_et_al Algorithm:

To compile and run the program on Windows CMD:
```bash
g++ Tomita_et_al.cpp -O3 -o Tomita_et_al.exe
Tomita_et_al.exe <input_file>
```

<br>

### 2) For Bron_Kerbosch Algorithm:

To compile and run the program on Windows CMD:
```bash
g++ Bron_Kerbosch.cpp -O3 -o Bron_Kerbosch.exe
Bron_Kerbosch.exe <input_file>
```

<br>

### 3) For Chiba_Nishizeki Algorithm:

To compile and run the program on Windows CMD:
```bash
g++ Chiba_Nishizeki.cpp -O3 -o Chiba_Nishizeki.exe
Chiba_Nishizeki.exe <input_file>
```
