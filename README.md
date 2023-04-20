This repository contains the complementary files referred to in the paper "**An Automated Multi-Layered Methodology to Assist the Secure and Risk-Aware Design of Multi-Factor Authentication Protocols**", submitted to the *IEEE Transactions on Dependable and Secure Computing* Journal.

In the paper, we have applied our methodology to a concrete authentication protocol. In particular, for the symbolic analysis, we have modelled the protocol through the specification language **ASLan++**, a high-level language that formalizes the interactions between the different protocol roles. The model has then been given in input to **SATMC** (SAT-based Model Checker), an open and flexible platform for model-checking security protocols via reduction to SAT.

For our analyses, we used SATMC (Version 3.5.7) launched within Eclipse using the STIATE Plugin (Version 1.0.0.1).

ASLan++ file and analyses outputs are available in this repository.

SATMC + STIATE Plugin + instructions to add STIATE Plugin in Eclipse are available [here](https://drive.google.com/a/fbk.eu/file/d/1Qc5T_VxXYPLh6i4IbEmuZlh_vM5cKu3_/view?usp=sharing).

The AVANTSSAR deliverable D2.3 “ASLan++ specification and tutorial” is available [here](https://drive.google.com/a/fbk.eu/file/d/1TsPxkw09ziDaY21ytgIZyg7m9I9lpBMb/view?usp=sharing).
