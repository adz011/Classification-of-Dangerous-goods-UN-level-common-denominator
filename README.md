  # IMO/UN Dangerous Goods Classification Data

  Compilation of IMO hazard class and UN number classifications
  for use in freight calculation systems.

  ## Data Source
  Classification data based on facts published in:
  - IMDG Code (IMO)
  - UN Recommendations on the Transport of Dangerous Goods
    (Model Regulations / "Orange Book")
  - ADR 2025 — ECE/TRANS/352, UNECE, 2024
    https://unece.org/transport/standards/transport/dangerous-goods/adr-2025

  This dataset contains only factual classification data
  (class numbers, UN numbers, official names) which are not
  subject to copyright. Original UNECE/IMO publications remain
  © United Nations.

  ## License
  This compilation is released under CC0 1.0 (Public Domain).
  You may use, modify, and redistribute freely, with or without attribution.

## JSON structure
```json
{
    "un": "",
    "name": "",
    "class": "",
    "classificationCode": "",
    "packingGroup": "",
    "labels": "",
    "specialProvisions": "",
    "limitedQuantities": "",
    "exceptedQuantities": "",
    "packingInstructions": "",
    "specialPackingProvisions": "",
    "mixedPackingProvisions": "",
    "portableTankInstructionsAndSpecialProvisions": "",
    "adrTankCodeAndSpecialProvisions": "",
    "vehicleForTankCarriage": "",
    "transportCategoryTunnelCodeAndPackages": "",
    "bulkSpecialProvisions": "",
    "loadingUnloadingHandlingAndOperation": "",
    "hazardIdentificationNo": ""
  }
```
File contains 3485 records of which 2352 are different UN codes.
  
