# Find-S-algorithmin-Python
Implementation of Find-S algorithm in Python

1. Initialize h to the most specific hypothesis in H
2. For each positive training instance x
For each attribute constraint ai in h
IF the constraint ai in h is satisfied by x THEN
do nothing
ELSE
replace ai in h by next more general constraint satisfied by x
3. Output hypothesis h
