## dnnf_go_ions

Deep Neural Network Force-field (DNNF) for simulating the graphene oxide (GO)–water interface with hydrated excess proton (H₃O⁺).

## Overview

This repository contains scripts, input files, and trained models for training and evaluating a DNNF model using DeePMD-kit. The force field is developed to accurately capture the behavior of hydrated proton at GO interfaces, derived from ab initio molecular dynamics (AIMD) data. It also include input script for AIMD simulation.


## Requirements

- DeePMD-kit
- LAMMPS 
- CP2K


## Systems

- `go2_h3ocl`: Oxidized GO (C/O ratio 2) with hydrated excess proton
- `go4_h3ocl`: Reduced GO (C/O ratio 4) with hydrated excess proton
