# Iceland - Test files

---

This directory contains test files produced by the Directorate of Health Iceland. 
The software used to produce the QR-codes can be found at https://github.com/ehn-digital-green-development/hcert-dotnet.

## Test files

### 1

[1.json](2DCode/raw/1.json) - Basic DGC with one vaccination entry. 

All tests should be successful.
Public key uploaded in the test environment

![1](2DCode/png/1.png)

### 2

[2.json](2DCode/raw/2.json) - Basic DGC with one test entry. 

All tests should be successful.
Public key uploaded in the test environment

![2](2DCode/png/2.png)

### 3

[3.json](2DCode/raw/3.json) -Negative PCR signed with RSA, no extened key usage

All tests should be successful.

![3](2DCode/png/3.png)

### 4

[4.json](2DCode/raw/4.json) -Negative PCR signed with RSA, no extened key usage

All tests should be successful.
Public key uploaded in the ACC environment

![4](2DCode/png/4.png)