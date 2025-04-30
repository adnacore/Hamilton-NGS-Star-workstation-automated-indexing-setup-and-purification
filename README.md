# Hamilton NGS Star workstation: automated indexing and purification

## About

This repository contains the electronic protocol files for the for the simultaneous amplification and dual-indexing of up to 384 DNA libraries through automated liquid handling using the Hamilton NGS Star workstation. This protocol is optimized specifically for ancient and degraded DNA (i.e., libraries with short inserts) and is compatible with both double- and single-stranded methods for preparing Illumina-type libraries (e.g., Meyer and Kircher 2010, Gansauge et al. 2020).

This repository also includes electronic protocol files for purifying indexed libraries using Solid Phase Reversible Immobilization (SPRI) technology (deAngelis et al. 1995).

## Requirements

To use the protocol, a Hamilton NGS Star workstation is required. Calibration of the instrument for this protocol has to be performed by the user and requires significant expertise in using the platform. 

## Implementation and Documentation

+ Use Hamilton Method Editor to import package file: method, device file, sub-methods, files and liquid classes. (Import Mode: Recovery.)
+ "Liquid_classes" files can be used to overwrite existing liquid classes. (Should be imported by the Hamilton Method Editor while importing the pkg file.)
+ Lid for Trough_V1.0.zip needs to be installed prior to application. It is recommended to use trough lids in the purification but they are optional by setting a specific boolean in the methos.
+ MailAlert.zip can be installed to enable the system to send Mails for errors or other notifications.

Some of the instructions, for example regarding the documentation and location of files, are specific to the environment and workflows of the Ancient DNA Core Unit of the MPI-EVA and have to be amended in other environments. 


## References

Gansauge, M.-T., Aximu-Petri, A., Nagel, S., & Meyer, M. (2020). Manual and automated preparation of single-stranded DNA libraries for the sequencing of DNA from ancient biological remains and other sources of highly degraded DNA. Nature Protocols, 15, 2279-2300.

Kircher, M., Sawyer, S. & Meyer, M. (2012) Double indexing overcomes inaccuracies in multiplex sequencing on the Illumina platform. Nucleic Acids Res., 40(1):e3, doi: 10.1093/nar/gkr771.

Meyer, M., & Kircher, M. (2010). Illumina sequencing library preparation for highly multiplexed target capture and sequencing. Cold Spring Harbor Protocols, 2010(6): prot5448.   

Zavala, E. I., Ayinuer-Petri, A., Richter, J., Nickel, B., Vernot, B., & Meyer, M. (2022). Quantifying and reducing cross‐contamination in single‐ and multiplex hybridization capture of ancient DNA. Molecular Ecology Resources, 22(6), 2196-2207.
