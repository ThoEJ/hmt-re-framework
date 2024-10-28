The following table lists three scenarios for the outlined logistics use case. Used abbreviations for actors and systems: LCW &ndash; Logistics Center Worker, ATS &ndash; Autonomous Transport System, SCMS &ndash; Supply Chain Management System, ILSS &ndash; Inbound Location Sensor System, OLSS &ndash; Outbound Location Sensor System, TCSS &ndash; Transport Container Smart Shelf, SMSS &ndash; Sensor Module Smart Shelf. Performed actions and possible end states are denoted by  an Ax or Ex, respectively:

| Scenario 1 | Scenario 2 | Scenario 3 |
| -------- | ------- | ------- |
| Trigger: Package arrival at inbound location. | Trigger: Package arrival at inbound location. | Trigger: Package arrival at inbound location. |
| A1: The LCW moves to the inbound location. | A1: The ILSS detects the package arrival. | A1: The ILSS detects the package arrival. |
| A2: The LCW uses a scanner to read good and transport assignment information through a QR-code attached to the package. | A2: The ILSS reads good and transport assignment information through a QR-code attached to the package.| A2: The ILSS reads good and transport assignment information through a QR-code attached to the package. |
| A3: The LCW transports the package to the preparation area. | A3: The ILSS creates a new transport preparation task in the SCMS and marks it as "in progress". | A3: The ILSS creates a new transport preparation task in the SCMS and marks it as "in progress". |
| A4: The LCW moves to the shelf containing the transport containers. | A4: The ILSS sends good and transport assignment information to the TCSS. | A4: The ILSS sends good and transport assignment information to the ATS. |
| A5: The LCW picks out the correct container for the good and assignment. | A5: The ILSS sends good and transport assignment information to the SMSS. | A5: The ATS moves to the inbound location. |
| A6: The LCW transports the selected container to the preparation area. | A6: The ILSS sends a notification to the LCW's smartphone. | A6: The ATS transports the package to the preparation area. |
| A7: The LCW moves to the shelf containing the sensor modules. | A7: The LCW reads the notification and moves to the inbound location. | A7: The ATS moves to the TCSS. |
| A8: The LCW picks out the correct sensor modules for the good and assignment. | A8: The LCW transports the package to the preparation area. | A8: The ATS requests the position of the correct container from the TCSS. |
| A9: The LCW transports the selected sensor modules to the preparation area. | A9: The LCW moves to the TCSS. | A9: The TCSS provides the correct position to the ATS. |
| A10: The LCW installs the sensor modules in the container. | A10: The TCSS displays the correct container for the good and assignment using Pick-by-Light. | A10: The ATS uses an attached arm unit to pick up the correct container. |
| A11: The LCW places the package in the container and closes it. | A11: The LCW picks up the highlighted container. | A11: The TCSS detects the removal, updates its internal database, and relays the information to the SCMS. |
| A12: The LCW transports the container to the outbound location. | A12: The TCSS detects the removal, updates its internal database, and relays the information to the SCMS. | A12: The ATS transports the container to the preparation area. |
| A13: The LCW updates container and sensor module stock information in the SCMS. | A13: The LCW transports the container to the preparation area. | A13: The ATS moves to the SMSS. |
| A14: The LCW documents the transport preparation task in the SCMS. | A14: The LCW moves to the SMSS. | A14: The ATS requests the positions of the correct sensor modules from the SMSS.|
| | A15: The SMSS displays the correct sensor modules for the good and assignment using Pick-by-Light. | A15: The SMSS provides the correct positions to the ATS.| 
| | A16: The LCW picks out the highlighted sensor modules. | A16: The ATS uses an attached arm unit to pick up the correct sensor modules. |
| | A17: The SMSS detects the removal, updates its internal database, and relays the information to the SCMS. | A17: The SMSS detects the removal, updates its internal database, and relays the information to the SCMS. |
| | A18: The LCW transports the selected sensor modules to the preparation area. | A18: The ATS transports the sensor modules to the preparation area. | 
| | A19: The LCW installs the sensor modules in the container. | A19: The ATS installs the sensor modules in the container.|
| | A20: The LCW places the package in the container and closes it. | A20: The ATS places the package in the container and closes it. |
| | A21: The LCW transports the container to the outbound location. | A21: The ATS transports the container to the outbound location. |
| | A22: The OLSS detects the container and marks the transport preparation task in the SCMS as "finished". | A22: The OLSS detects the container and marks the transport preparation task in the SCMS as "finished". |
| E1: All listed actions were completed successfully and the transport preparation task is finished. | E1: All listed actions were completed successfully and the transport preparation task is finished. | E1: All listed actions were completed successfully and the transport preparation task is finished. |
| E2: One of the listed actions could not be completed successfully, transport preparation had to be halted, and support had to be requested. | E2: One of the listed actions could not be completed successfully, transport preparation had to be halted, and support had to be requested. | E2: One of the listed actions could not be completed successfully, transport preparation had to be halted, and support had to be requested. |
