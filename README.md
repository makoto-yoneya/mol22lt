# mol22lt

Perl script translating mol2 to lt.

## Functions

This Perl script translates [sybyl-mol2 format][1] file (\*.mol2) to [LAMMPS template format][2] file (\*.lt).

## Usage

`mol22lt.pl < molecule.mol2 > molecule.lt`

Input \*.mol2 file is assumed to be generated with [antechamber][3] with proper force field (e.g. GAFF) atom types and charges.

Resultant \*.lt file can be input for [moltemplate][2].

An example can be found in [this tutorial][4] (in Japanese).

## Prerequisites

Perl interpleater.

## Authors

Makoto Yoneya.

[1]: http://www.csb.yale.edu/userguides/datamanip/dock/DOCK_4.0.1/html/Manual.41.html
[2]: https://www.moltemplate.org/visual_examples.html 
[3]: http://ambermd.org/antechamber/antechamber.html 
[5]: https://makoto-yoneya.github.io/LAMMPS-organics/
