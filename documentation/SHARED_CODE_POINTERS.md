# Shared Code Pointers

The paper states that FORTRAN programs created nested trip-chain file structures from the MWCOG trip records. The matching local programs are shared with related MWCOG travel-behavior papers and are staged once at:

`/Users/dlev2617/Documents/Code/Agents/github-packages/_shared_sources/mwcog-trip-chain-fortran`

Included shared source files:

- `code/PROGA.F`
- `code/PROG2A.F`
- `code/PROG6A.F`

The package-local data table can be read without rerunning the FORTRAN code. Rerunning the code would require raw MWCOG survey records from the public source-data record named in `documentation/SOURCE_DATA_POINTERS.md`.
