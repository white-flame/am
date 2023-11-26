# Douglas Lenat's AM from SAIL archives circa 1977

These files are extracted from the SAILDART archive maintained by Bruce Baumgart, in Douglas Lenat's AM section here: https://www.saildart.org/[AM,DBL]/ 

The accompanying PhD thesis can be found here: https://apps.dtic.mil/sti/pdfs/ADA155378.pdf

## Execution environment
Quoted from the thesis, page 124:
```
Machine: SUMEX, PDP-10, KI-10 uniprocessor, 256k core memory.

Language: Interlisp, January '75 release, which occupies 140k of the total 256k, but which
provides a surplus "shadow space" of 256k additional words available for holding compiled
code.
```

## Notes
`LT` is the initial loader file, which will load the others. While the thesis notes that the file `TOP6` will be loaded, at some point this was split into loading `TA` and `TB`.

The `CON6` file is much newer than the others. While I grabbed the newest version, older versions still exist on the archive above and might be required instead.

Any other applicable files found in the SAILDART archive such as documentation or demonstration logs should be added here as well.

This should be in the public domain, or international equivalent, as it was funded by the USA government through ARPA. The thesis additionally encourages others to copy, modify, and use the software.

Discord: https://discord.gg/vhsmVCwgvK
