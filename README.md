# Methods
Local correlation methods. These are local, pair natural orbital based correlation methods. They must be used together with auxiliary correlation fitting basis sets. Open-shell variants are available for some of the methods, for full list please see section 8.1.3. We
recommend n = 1 for the CEPA methods.
## NOTE
SCF calculations doesn't account for SCS and SOS and just PBE separately. Also in TDDFT, only excited state calculates is possible


The simplest way to perform a DLPNO based STEOM calculation is via the usage of the STEOM-DLPNO-CCSD
keyword, together with the specification of the desired number of roots. The specification of an auxiliary
basis set is also required, just as for ground state DLPNO-CCSD calculations.
