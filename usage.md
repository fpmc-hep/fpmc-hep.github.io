## FPMC usage

### Datacard parameters

| Parameter | Description                                      | Default value  |
|:---------:|--------------------------------------------------|----------------|
| `TYPEPR`  | Exclusive ’EXC’ or inclusive ’INC’ production    |                |
| `TYPINT`  | Switch between QED and QCD process               | `'QED'`        |
| `NFLUX`   | Intermediate particles flux model                | 15             |
| `IPROC`   | Process number to generate (see [here](processes) ) | 11500          |
| `PBEAM1`  | Type of primary incoming particles               | `E+` (p)       |
| `PBEAM2`  | Type of primary incoming particles               | `E+` (p)       |
| `ECMS`    | Centre of mass energy √s (in GeV)                | 14E3           |
| `HMASS`   | Higgs boson mass (in GeV/c²)                     | 125            |
| `IFITPDF` | Diffractive PDF model (HERA/Tevatron tunings)    | 100            |
| `ISOFTM`  | Soft correction model                            | 1              |

##### Phase space definition

| Parameter | Description                                      | Default value  |
|:---------:|--------------------------------------------------|----------------|
| `PTMIN`   | Minimal pT of the single outgoing particle       | 0              |
| `PTMAX`   | Maximal pT of the single outgoing particle       | 10E8           |
| `YJMIN`   | Minimal rapidity of the single outgoing particle | -6             |
| `YJMAX`   | Maximal rapidity of the single outgoing particle | 6              |
| `Q2WWMN`  | Minimal momentum transfer Q²=\|t\| (in GeV²)     | 0              |
| `Q2WWMX`  | Maximal momentum transfer Q²=\|t\| (in GeV²)     | 4              |
| `YWWMIN`  | Minimal beam momentum loss ξ                     | 0              |
| `YWWMAX`  | Maximal beam momentum loss ξ                     | 0.1            |

##### Heavy ions mode parameters

| Parameter | Description                                      | Default value  |
|:---------:|--------------------------------------------------|----------------|
| `IAION`   | Atomic number of colliding nuclei (A)            | 1              |
| `IZION`   | Proton number of colliding nuclei (Z)            | 1              |

##### Events generation parameters

| Parameter | Description                                      | Default value  |
|:---------:|--------------------------------------------------|----------------|
| `MAXEV`   | Number of events to generate                     | 100            |
| `NRN1`    | Random number generator initial seed             | --             |
| `NRN2`    | Random number generator initial seed             | --             |
| `NTNAME`  | Output file name                                 | `’tmpntuple.ntp’` |
