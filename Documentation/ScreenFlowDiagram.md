```mermaid
flowchart TB
A[Welcome and Login] --> B[Homescreen]
B[Homescreen] --> C[Calender]
B--> D[Last Entry Summary]
D --> Entry[That Entry]
C --> Entry
Entry --> C
C --> E[New Entry]
E --> F[Entry Type Selection]
F --> G[Details/Submit]
G --> C[Calender]
```