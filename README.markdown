Análise de Code Smells – Java Blackjack

Este repositório é um fork do projeto original:
https://github.com/davidwinter/java-blackjack

Realizar a análise de code smells no código-fonte do projeto e propor melhorias com base em boas práticas de engenharia de software.

---

Code Smells Identificados

1. Long Method
Métodos com muitas responsabilidades e alta complexidade.

Problemas:
- Dificuldade de leitura
- Baixa coesão
- Difícil manutenção

Proposta:
- Dividir métodos em funções menores

---

2. God Class
Classe central com muitas responsabilidades.

Problemas:
- Alto acoplamento
- Baixa reutilização

Proposta:
- Separar em múltiplas classes (GameService, UI, Model)

---

3. Primitive Obsession / Magic Numbers

Problemas:
- Uso excessivo de String e int
- Falta de tipagem forte

Proposta:
- Utilização de enums (Rank, Suit)

---

Melhorias propostas

- Separação de responsabilidades (SRP)
- Redução de complexidade
- Uso de orientação a objetos mais adequada

---

Observação
Este fork foi criado exclusivamente para fins acadêmicos.
