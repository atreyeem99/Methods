# Methods
Local correlation methods. These are local, pair natural orbital based correlation methods. They must be used together with auxiliary correlation fitting basis sets. Open-shell variants are available for some of the methods, for full list please see section 8.1.3. We
recommend n = 1 for the CEPA methods.
## NOTE
SCF calculations doesn't account for SCS and SOS and just PBE separately. Also in TDDFT, only excited state calculates is possible


The simplest way to perform a DLPNO based STEOM calculation is via the usage of the STEOM-DLPNO-CCSD
keyword, together with the specification of the desired number of roots. The specification of an auxiliary
basis set is also required, just as for ground state DLPNO-CCSD calculations.
## Double hybrid functional
examples: B2PLYP
mPW2PLYP
B2GP-PLYP
PWPB95
PBE-QIDH
PBE0-DH
PBE0-2
DSD-BLYP
DSD-PBEP86
DSD-PBEB95
wB2PLYP
wB2GP-PLYP
RSX-QIDH
RSX-0DH
wB88PP86
wPBEPP86
wB97X-2
SCS_SOS-B2PLYP21
SCS-PBE-QIDH
SOS-PBE-QIDH
SCS-B2GP-PLYP21
SOS-B2GP-PLYP21
SCS_SOS-wB2PLYP
SCS-wB2GP-PLYP
SOS-wB2GP-PLYP
SCS-RSX-QIDH
SOS-RSX-QIDH
SCS-wB88PP86
SOS-wB88PP86
SCS-wPBEPP86
SOS-wPBEPP86


## Normal dft methods
CAM-B3LYP
Examples
## wave function correlation method
## ADC2 and PBE-QIDH
## ADC2 takes a lot of time
## adc2 with svp less time
