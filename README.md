# Sending_SAEJ1939_CANBUS_Messages

The work of the project:  https://youtu.be/DuKHaN98Y4s

The SAE J1939/16 document outlines the methods used to detect the baud rate of an SAE J1939 network segment by ECUs that can adjust their CAN baud rate while in use. The specified approach provides a reliable method to detect the CAN baud rate of that network segment without interrupting network communications...

All J1939 packets, except for the request packet, contain eight bytes of data and a standard header which contains an index called Parameter Group Number (PGN), which is embedded in the message's 29-bit identifier. A PGN identifies a message's function and associated data. J1939 attempts to define standard PGNs to encompass a wide range of automotive, agricultural, marine and off-road vehicle purposes. A range of PGNs (00FF0016 through 00FFFF16, inclusive) is reserved for proprietary use. PGNs define the data which is made up of a variable number of Suspect Parameter Number (SPN) elements defined for unique data. For example, there exists a predefined SPN for engine RPM...

- Reading CAN messages with different PGNs such as vehicle speed, fuel level, engine_speed etc. in the J1939 standard...

Design by: https://www.linkedin.com/in/musacufalci/



