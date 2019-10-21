## Rock Physics
In my view a rock physics package needs to
- have a library of intrinsic rock physics models of varying complexity, for (non-exhaustive) example:
* simple hertzian contact 
* large scale fluid flow
* microscopic scale fluid flow
- understand propagating modes (iso/anisotropic) by solving christoffel eqn
- easily lend itself to seismic modelling via reflectivity/AVO so include zoeppritz and [Schoenberg and Protazio](https://asa.scitation.org/doi/10.1121/1.2029011) implementations
- incorporate data relevant to fluids encountered in field and lab studies: CO$$_2$$, gas, oil, brine, glycerine.
- have the capacity to build on well data like an easy LAS read 

