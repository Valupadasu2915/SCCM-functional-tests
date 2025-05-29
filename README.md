# SCCM-functional-tests
This repository contains CAPL scripts and test cases for validating the Steering Column Control Module (SCCM) in an automotive HIL environment. It includes:

- Button function validation
- Signal monitoring
- Basic UDS diagnostic tests

Tool Used: Vector CANoe  
Protocols: CAN, UDS (ISO 14229)  
Author: [Manikantta Valupadasu]

SCCM_HIL_Testing/
├── README.md
├── TestCases/
│   ├── TC_SCCM_Button_Validation.xlsx
│   ├── TC_SCCM_Signal_Monitoring.xlsx
│   └── TC_SCCM_Diagnostics.xlsx
├── CAPL_Scripts/
│   ├── Init_SCCM.can
│   ├── Button_Test.can
│   ├── Signal_Monitor.can
│   └── UDS_Diagnostics.can
└── Docs/
    └── SCCM_Test_Strategy.md

