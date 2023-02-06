# Markdown preview mermaid support demo

Flowchart designed with Markdown Preview Mermaid Support VS Code extension.

## Problem statement

---

Visualize the flow to determine whether a number is even or odd.

## Flowchart

---

```mermaid
flowchart TD;
    Start --> IN(Take a number as input) --> R(Divide the number by 2 and store the remainder) --> REZ{Is remainder equal to 0?};
    REZ --> |Yes| PE(Print even) --> Stop;
    REZ --> |No| PO(Print odd) --> Stop;
```

## References

---

Checkout my medium article where I go through the steps of creating the flowchart- 