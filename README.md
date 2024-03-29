# MO-NanoDatabase
A database of metal-oxide nanocompounds with properties, 3D structure and NanoFingerprint.

DATA DESCRIPTION
The database on metal-oxide nanocompounds with its toxicity or global properties is composed of one Excel document and three folders.

- MO-NanoDatabase.xlsx is an Excel document that describes in the first sheet, which nanocompounds have been collected, which properties have been collected and from which paper have been extracted. In the rest of the sheets, there is the data extracted from each paper per sheet. In these sheets, there is exactly all data that we have per all nanocompounds.

- Folder XYZ contains the 3D structure of all the nanocompounds, which we have the data in MO-NanoDatabase.xlsx.

- Folders NanoFingerprint and NanoFingerprint_reduced contain the Fingerprint information of all the nanocompounds, which we have the data in MO-NanoDatabase.xlsx. The difference between them is that folder NanoFingerprint exactly contains the NanoFingerprint in the original format. Contrarily, folder NanoFingerprint_reduced contains the NanoFingerprints but the empty cells of the NanoFingerprint have been eliminated

DATA COLLECTION:
- Global properties:
Extracted from the supporting material of the papers mentioned in References section in MO-NanoDatabase.xlsx. Then, a process of curation and standardisation was applied. Samples in these papers that properties were missing or incongruent were discarded.

- 3D structure (XYZ file):
Generated by the public crystallographic tool in: https://nanocrystal.vi-seem.eu

- NanoFingerprints:
Generated by https://atena.urv.cat/model/
