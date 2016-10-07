# abap-trmanager
SAP Alternative Transport Manager (similar to SE01/SE09)

Available functions:
  - Mass transport download to ZIP file
  - Mass transport upload from ZIP file
  - Mass transport release

## Installation
- Install [SAPLINK](https://app.assembla.com/spaces/saplink/wiki/)
- SE38 -> Run ZSAPLINK report
- Choose Import Nugget
  - under options choose 
    - Package Name ($TMP),
    - Nugget file name (choose NUGG_ZTRMANAGER.nugg file),
    - Check Overwrite Originals 
- Run report (F8)
- Have fun!

## Usage
- For better usability:
  - Create new transaction (SE93) name ZSE01
  - type Program with selection screen (report transaction)
  - Short text - Transport Organizer
  - Program - ZTRMANAGER
  - GUI support - check all
  - save to package $TMP
- Run via transaction ZSE01

## [License](https://github.com/ghostxwheel/abap-trmanager/blob/master/LICENSE)
