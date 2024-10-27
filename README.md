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
    C --> C2[Workflow Test]:::sub
    
    A --> D(Hosting):::section
    D --> D1[Evaluate Options]:::sub
    D --> D2[Security & Support]:::sub
    D --> D3[Load Speed]:::sub
    
    A --> E(Documentation):::section
    E --> E1[User Guide]:::sub
    E --> E2[In-Code Comments]:::sub
    E --> E3[Training]:::sub

    classDef main fill:#4C9F70,stroke:#333,stroke-width:2px;
    classDef section fill:#6ABF85,stroke:#333,stroke-width:1px;
    classDef sub fill:#A9D4AB,stroke:#333,stroke-width:1px;
