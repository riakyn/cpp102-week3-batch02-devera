```mermaid 
flowchart TD
A([Start]) --> B[/Input number/]
B --> C{Is number MOD 2 = 0}
C -- Yes --> D[/Display Even/]
C -- No --> E[/Display odd/]
D --> F([End])
E --> F
```