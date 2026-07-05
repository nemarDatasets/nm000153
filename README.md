[![DOI](https://img.shields.io/badge/DOI-10.1038%2Fsdata.2017.40-blue)](https://doi.org/10.1038/sdata.2017.40)

# The Multimodal Resource for Studying Information Processing in the Developing Brain (MIPDB)

## Summary
High-density EEG recorded (with accompanying eye-tracking and behavioural data in `sourcedata/`)
while children, adolescents, and adults (ages ~6–44) performed a battery of cognitive paradigms.
The resource was created by the Child Mind Institute to support the study of the development of
information processing across the lifespan. Released by Langer et al. (2017, *Scientific Data*).

## Participants
Typically-developing and community participants spanning childhood to adulthood (developmental
sample). See `participants.tsv` for per-subject information.

## Recording
- **EEG:** 128-channel EGI HydroCel Geodesic Sensor Net, recorded with NetStation at **500 Hz**.
- **Eye-tracking** and **behavioural** responses were collected simultaneously (preserved in `sourcedata/`).

## Task / paradigms
Each session comprises a fixed sequence of paradigms (identical order across subjects per the
original paper): **Resting-state → Surround suppression → Naturalistic viewing → Contrast change
detection → Sequence learning → Symbol search**. Because the per-block paradigm mapping is not
enumerated in Langer et al. (2017), each recording block is published here as `task-blockNN`; the
block→paradigm mapping should be confirmed against the CMI MIPDB documentation before analysis.

## How to cite
> Langer, N., Ho, E. J., Alexander, L. M., Xu, H. Y., Jozanovic, R. K., Henin, S., Petroni, A.,
> Cohen, S., Marcelle, E. T., Parra, L. C., Milham, M. P., & Kelly, S. P. (2017). A resource for
> assessing information processing in the developing brain using EEG and eye tracking.
> *Scientific Data*, 4, 170040. https://doi.org/10.1038/sdata.2017.40

## Source and license
Derived from the Child Mind Institute EEG/Eye-tracking resource
(https://fcon_1000.projects.nitrc.org/indi/cmi_eeg/). License: **CC-BY-NC-SA-3.0**.
