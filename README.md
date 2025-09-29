# DeltaLactam-ChemicalSpace

[![Powered by RDKit](https://img.shields.io/badge/Powered%20by-RDKit-3838ff.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQBAMAAADt3eJSAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAAFVBMVEXc3NwUFP8UPP9kZP+MjP+0tP////9ZXZotAAAAAXRSTlMAQObYZgAAAAFiS0dEBmFmuH0AAAAHdElNRQfmAwsPGi+MyC9RAAAAQElEQVQI12NgQABGQUEBMENISUkRLKBsbGwEEhIyBgJFsICLC0iIUdnExcUZwnANQWfApKCK4doRBsKtQFgKAQC5Ww1JEHSEkAAAACV0RVh0ZGF0ZTpjcmVhdGUAMjAyMi0wMy0xMVQxNToyNjo0NyswMDowMDzr2J4AAAAldEVYdGRhdGU6bW9kaWZ5ADIwMjItMDMtMTFUMTU6MjY6NDcrMDA6MDBNtmAiAAAAAElFTkSuQmCC)](https://www.rdkit.org/)

Scripts for the generation and analysis of the chemical space for the manuscript entitled: _"Scalable Photocatalytic Annulation of Primary Amines to δ Lactams: Access to Privileged (Spiro)Piperidine Space"_

Descriptors and chemcial space data can be found in the `./data` directory.

## Description of Jupyter notebooks:
- **generate-fingerprints.ipynb**: Generation of Morgan fingerprints using RDKit.
- **generate-adme-descriptors.ipynb**: Generation of ADME-type features using RDKit.
- **fingerprint-chemicalspace.ipynb**: Chemical space generated using Morgan fingerprints.
- **adme_chemicalspace.ipynb**: Chemcial space generated using RDKit ADME descriptors.
- **merged_chemspaces.ipynb**: Chemical space generated from Morgan fingerprints and ADME descriptors.