# Binary Search Tree (BST) & Graphviz Implementation

## Core Features
- **Dynamic CRUD:** Node insertion and deletion handling leaf, single, and double-child cases.
- **Branch Deep Purge:** Complete memory deallocation of specific sub-trees without leaking data.
- **Data Analytics:** Real-time branch stats (sum of values, leaf count, total node count).
- **Graphviz Pipeline:** Exports structural states to `.dot` files for architectural mapping.
- **Fisher-Yates Algorithm:** Native randomized array generation for balanced stress tests.

## Tree Architecture

### Initial State (`grafo_antes.dot`)
![Tree Before]
<img width="1383" height="1595" alt="antes" src="https://github.com/user-attachments/assets/a8f8395a-93ba-4cb5-b3df-c57f8a4b9e02" />


---

### Post Batch Deletion (`grafo_depois.dot`)
![Tree After]
<img width="1527" height="1307" alt="depois" src="https://github.com/user-attachments/assets/f8da6ac4-fd49-443a-bbd8-df0b4b5cae74" />


---

## Quick Start & Compilation

### Environment Setup
```bash
sudo apt update && sudo apt install gcc graphviz -y
