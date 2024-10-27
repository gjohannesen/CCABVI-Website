# CCABVI-Website
### Project Action Items
```mermaid
graph TD
    A[CCABVI Website Overhaul]:::main
    
    A --> B(Accessibility):::section
    B --> B1[Tab Navigation]:::sub
    B --> B2[Contrast]:::sub
    B --> B3[Font Size]:::sub
    
    A --> C(Donations):::section
    C --> C1[PayPal Integration]:::sub
    C --> C2[Test]:::sub
    
    A --> D(Hosting):::section
    D --> D1[Evaluate Options]:::sub
    D --> D2[Security & Support]:::sub
    D --> D3[Price Evaluation]:::sub
    
    A --> E(Documentation):::section
    E --> E1[User Guide]:::sub
    E --> E2[In-Code Comments]:::sub
    E --> E3[Training]:::sub

    classDef main fill:#0044CC,stroke:#333,stroke-width:2px,color:#FFFFFF;
    classDef section fill:#007BFF,stroke:#333,stroke-width:1px,color:#FFFFFF;
    classDef sub fill:#66B2FF,stroke:#333,stroke-width:1px,color:#FFFFFF;

