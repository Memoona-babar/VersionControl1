# Task 2: Mission Control Sends Change Requests

## CR-01 — Emergency Safety

### Original Requirement

FR-04:

The rover shall enter Safe Mode when a critical battery or thermal condition is detected.

### Updated Requirement

FR-04:

The rover shall enter Safe Mode within 3 seconds when battery temperature exceeds the critical threshold or battery capacity falls below the defined emergency level.

## CR-02 — Mission Expansion

### Original Requirement

NFR-04:

The system shall support communication with multiple rovers simultaneously.

### Updated Requirement

NFR-04:

The system shall support at least 20 simultaneously connected rovers.

## CR-03 — Security Upgrade

### Original Requirement

NFR-02:

Only authenticated Mission Control operators shall be permitted to issue rover commands.

### Updated Requirement

NFR-02:

The system shall require authenticated and role-authorized operators before accepting rover commands.
