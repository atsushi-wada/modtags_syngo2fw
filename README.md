# modtags_syngo2fw
An Orthanc server-side script to modify DICOM headers to become compliant to Flywheel system.

Contains a set of functions to acheive on-the-fly DICOM tag
modification on Orthanc DICOM server, which enables to:
(1) Fix DICOM tag inconsistency across scanners and console OS verions
(2) Generate Flywheel identification string to specify the location
    where the data should be stored to.
    
