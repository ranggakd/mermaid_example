## Basic Node

```mermaid
---
title: Node
---

flowchart LR
    id
```

Basic Node (instead of `flowchart`, we can use `graph`)

```mermaid
---
title: Node
---

graph LR
    id
```

## Node with Text

```mermaid
---
title: Node with text
---

graph LR
    id1[This is the text in the box]
```

Use `"` to enclose the unicode text

```mermaid
---
title: Unicode
---

graph LR
    id["This is 🍉 Unicode"]
```

Markdown formatting 

> Per 10 November 2023, only work for **Mermaid Live Editor** & **Markdown Preview Mermaid Support VSCode Extension**

```mermaid
---
title: Markdown Formatting
---

flowchart LR
    markdown["`This **is** _Markdown_`"]
    newLines["`Line1
    Line 2
    Line 3`"]
    markdown --> newLines
```

## Direction

```mermaid
---
title: TD - Top-Down
---

graph TD
    Start --> Stop
```

```mermaid
---
title: TB - Top-Bottom (same as TD)
---

graph TB
    Start --> Stop
```

```mermaid
---
title: BT - Bottom-Top
---

graph BT
    Start --> Stop
```

```mermaid
---
title: RL - Right-Left
---

graph RL
    Start --> Stop
```

```mermaid
---
title: LR - Left-Right
---

graph LR
    Start --> Stop
```