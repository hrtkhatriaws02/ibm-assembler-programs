# IBM Assembler Programs Collection

This repository contains IBM Assembler (HLASM) programs, along with their **JCL**, **MACROs**, and **PROCs**.  
It is meant for learning, reference, and practice on **Mainframe Assembly Programming**.

---

## 📂 Folder Structure

ASMSRC/
├── ASMSRC/ # Main Assembler source programs
├── ASMJCL/ # JCL jobs to assemble, link, and run programs
├── ASMMAC/ # User-defined macros
└── ASMPROC/ # Cataloged procedures

---

## 📘 Contents

### 🔹 ASM Programs (`ASMSRC/ASMSRC`)
Below is a description of key programs:

- **ADDHPGM.TXT** → Addition program using halfword data.
- **ADDPGM.TXT/ADDRPGM.TXT** → Simple addition programs with register usage.
- **ALIGNPGM.TXT** → Demonstrates data alignment concepts.
- **ASMCALL.TXT/ASMSUB.TXT** → Example of calling and returning from subroutines.
- **ASMLINK.TXT** → Linkage conventions in assembler.
- **ASMXCTL.TXT/XCTL.TXT** → Demonstrates XCTL program transfer.
- **B24MAIN.TXT/B31SUB.TXT** → Examples of 24-bit and 31-bit addressing.
- **CMPRPGM%.TXT** → Series of programs demonstrating compare instructions.
- **CONVPGM.TXT** → Data conversion logic.
- **DIVPGM.TXT/ DIVRPGM.TXT** → Division programs.
- **DTYPES.TXT** → Demonstrates different data types.
- **GETPUT/GETLPUT%.TXT** → File I/O examples using GET and PUT macros.
- **GMAIN1/GMAIN2.TXT** → General main program templates.
- **HRTK0001/2/3.TXT** → Sample programs (likely project-specific).
- **INLMACRO.TXT** → Demonstrates inline macro usage.
- **INSUBR%.TXT** → Subroutine examples.
- **LKSDS/RKSDS%.TXT** → VSAM KSDS file operations.
- **LOADSMRK.TXT** → Example of LOAD and STORE instructions.
- **LOOP1/2/3.TXT** → Looping constructs with BXH/BXLE.
- **MACCALC.TXT/MPCALC.TXT** → Macro-based calculator programs.
- **MAINPGM%.TXT** → Standard main program templates.
- **MULPGM.TXT** → Multiplication program.
- **MYTCB.TXT** → Example involving Task Control Block.
- **PADD2.TXT/PSP%.TXT/PSRL.TXT** → Packed decimal arithmetic and edits.
- **PEDIT/PEDIT1.TXT** → Packed decimal editing examples.
- **PZAP.TXT/ZAPPGM.TXT** → Demonstrates ZAP (zero add packed).
- **RBKSDS/RESDS1.TXT** → More VSAM dataset operations.
- **SELEMP.TXT** → Example of employee selection logic.
- **SPGM.TXT/SRPGM.TXT/MPGM.TXT** → Main-subprogram call examples.
- **STRM3.TXT** → String manipulation using CLI, BXH, MVI.
- **SUBHPGM/SUBPGM/SUBRPGM.TXT** → Subtraction programs (halfword, RR format).
- **SUMC.TXT** → Array sum using ADD and BXLE.
- **TEMPLATE.TXT** → Program template for new assembler coding.
- **TESTSTH.TXT** → Test program for addition using halfword.
- **TPGM.TXT** → Placeholder program.
- **UNBRPGM/UNBRPGM1.TXT** → Examples of unconditional branching.
- **VREC.TXT** → Variable record handling.
- **WELMSG/WELMSG1/WELPGM1.TXT** → Print welcome message to spool.

---

### 🔹 JCL (`ASMSRC/ASMJCL`)
Contains jobs to assemble, link, and execute programs.  
Examples:
- **ASMLINK.TXT** → JCL to assemble and link a program.
- **COMPRUN.TXT** → Run a compare program.
- **DB2%.TXT** → JCL for DB2-related programs.
- **CRKSDS/LKSDS/RKSDS%.TXT** → VSAM dataset creation and run JCL.
- **CALLSUB/XCTL/ATTACH.TXT** → JCL to execute program transfers.

---

### 🔹 Macros (`ASMSRC/ASMMAC`)
Reusable macros to simplify code:
- **ADD.TXT/ADDK.TXT** → Addition macros.
- **CALC.TXT** → General calculation macro.
- **PROLOG/EPILOG.TXT** → Standard entry/exit macros for subroutines.
- **MACCALC.TXT** → Calculator macro.

---

### 🔹 PROCs (`ASMSRC/ASMPROC`)
Cataloged procedures for job execution:
- **ASMACL.TXT** → Assemble and compile procedure.
- **ASMACLG.TXT** → Assemble, compile, link, and go.
- **HLASMCL.TXT** → HLASM compile and link.

---

## 🚀 How to Use
1. Submit the JCL from `ASMJCL` to **compile and run** the assembler programs.
2. Include macros from `ASMMAC` when required.
3. Use `ASMPROC` cataloged procedures for simplified job submission.
4. Explore `ASMSRC` programs for examples of:
   - Arithmetic (ADD, SUB, MUL, DIV)
   - Data handling (alignment, packed decimal, editing)
   - Subroutine calls and linkage
   - VSAM file handling
   - Macros and reusable templates

---

## 🎯 Purpose
This repo is designed for:
- Learning IBM HLASM programming.
- Understanding mainframe program structure (CSECT, linkage).
- Practicing JCL, PROCs, and macro usage.

---
