# Artifact Appendix

Paper title: **SoK: Offline Finding Protocols for Lightweight Location Tracking**

Requested Badge(s):
  - [X] **Available**
  - [ ] **Functional**
  - [ ] **Reproduced**

## Description

This repository contains the corpus of papers used for the paper "SoK: Offline
Finding Protocols for Lightweight Location Tracking", by Akshaya Kumar, Carolina
Ortega Pérez, Joseph Jaeger, Thomas Ristenpart, and Michael A. Specter, accepted
in PETS 2026.

To assemble the corpus, the authors followed two methods: a snowball search (method 1)
and a keyword search (method 2). The authors filtered relevant outputs of each method
separately, creating two separate corpuses, and finally combined them.
The full methodology is available in Appendix A of the paper:
https://eprint.iacr.org/2026/488.

The files contain the following information:
- `method1-snowball.csv` -- contains the initial corpus of papers gathered from method 1.
- `method2-keywords.csv` -- contains the initial corpus of papers gathered from method 2.
- `keywords.csv` -- contains the keywords used during method 2.
- `final-corpus.csv `-- contains the final corpus of papers used in the SoK, along with their categorizations.

### Security/Privacy Issues and Ethical Concerns

Our artifact is a collection of publicly available papers and documentation,
therefore we do not have privacy or ethical concerns.

## Environment

Our data can be viewed using a csv file viewer.

### Accessibility

Our artifact is available at: 
`https://github.com/cortegap/pets-26-sok-artifact/tree/main`

## Notes on Reusability

Our artifact supports reuse beyond verifying the specific corpus presented in our paper.
The `final-corpus.csv` file, along with the categorization therein (topic and type labels),
provides a starting point for researchers studying offline finding, Bluetooth-based
location tracking, anti-stalking technology, or crowdsourced location tracking systems.
The categorization columns can be filtered or extended to suit a narrower or broader
scope without redoing the full search. Our keyword and snowball search both attained
saturation at the time of writing and may be extended making fresh forward-citation passes
from the papers already included, or by re-running the keyword search against the same
venues for papers published after our cutoff.
