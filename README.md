# Árvore Binária de Busca (BST) & Implementação com Graphviz

## Funcionalidades Principais
- **CRUD Dinâmico:** Inserção e remoção de nós, tratando os casos de nó folha, filho único e dois filhos.
- **Poda Profunda de Ramos:** Desalocação completa de memória de sub-árvores específicas, sem vazamento de dados.
- **Análise de Dados:** Estatísticas de ramos em tempo real (soma dos valores, contagem de folhas, contagem total de nós).
- **Pipeline Graphviz:** Exporta os estados estruturais para arquivos `.dot` para mapeamento arquitetural.
- **Algoritmo de Fisher-Yates:** Geração nativa de arrays aleatórios para testes de estresse balanceados.

## Arquitetura da Árvore

### Estado Inicial (`grafo_antes.dot`)
![Árvore Antes]
<img width="1383" height="1595" alt="antes" src="https://github.com/user-attachments/assets/a8f8395a-93ba-4cb5-b3df-c57f8a4b9e02" />

---

### Após Remoção em Lote (`grafo_depois.dot`)
![Árvore Depois]
<img width="1527" height="1307" alt="depois" src="https://github.com/user-attachments/assets/f8da6ac4-fd49-443a-bbd8-df0b4b5cae74" />

---

## Início Rápido & Compilação

### Configuração do Ambiente
```bash
sudo apt update && sudo apt install gcc graphviz -y
```
