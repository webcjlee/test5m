
```mermaid
flowchart TD
    A[Start] --> B[Check Eligibility]
    B -->|Eligible| C[Prepare Required Documents]
    B -->|Not Eligible| Z[End]
    C --> D[Fill Application Form]
    D --> E[Submit Application]
    E --> F[Pay Application Fee]
    F --> G[Take Written Test]
    G -->|Pass| H[Take Driving Test]
    G -->|Fail| Y[Retake Written Test]
    H -->|Pass| I[Receive Driver's License]
    H -->|Fail| X[Retake Driving Test]
    Y --> G
    X --> H
    I --> Z
    Z[End]
