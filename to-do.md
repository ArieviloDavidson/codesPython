
# Lista de Projetos para Implementar (To-Do)

Ideias de projetos rápidos em Python puro (sem bibliotecas externas complexas), com tempo estimado de implementação menor que 30 minutos cada.

---

- [ ] **1. Vetor 2D/3D com Dunder Methods (POO + Álgebra Linear Simples)**
  - **Tempo estimado:** 15 a 20 min
  - **Conceitos:** Métodos mágicos (`__add__`, `__sub__`, `__mul__`, `__abs__`, `__repr__`), encapsulamento.
  - **Objetivo:**
    - Criar classe `Vetor2D` com coordenadas `x` e `y`.
    - Sobrecarga dos operadores `+` e `-` para soma/subtração vetorial.
    - Operador `*` para multiplicação por escalar e produto escalar.
    - Função `abs(v)` retornando a norma euclidiana ($\sqrt{x^2 + y^2}$).

---

- [ ] **2. Decompositor em Fatores Primos e Crivo de Eratóstenes (Matemática Pura)**
  - **Tempo estimado:** 15 a 20 min
  - **Conceitos:** Algoritmos clássicos, otimização de laços, dicionários e listas.
  - **Objetivo:**
    - `crivo_eratostenes(limite: int) -> list[int]`: gera primos até $N$ de forma performática.
    - `fatorar_primos(n: int) -> dict[int, int]`: decompõe um inteiro em seus fatores primos e expoentes (ex.: $360 \rightarrow \{2: 3, 3: 2, 5: 1\}$).

---

- [ ] **3. Simulador de Batalha em Turnos / RPG (POO + Herança e Polimorfismo)**
  - **Tempo estimado:** 20 a 25 min
  - **Conceitos:** Herança, polimorfismo, `random.randint`, controle de fluxo.
  - **Objetivo:**
    - Classe base `Personagem` (`nome`, `vida`, `ataque`, `receber_dano`).
    - Subclasses `Guerreiro` (chance de acerto crítico) e `Mago` (sistema de mana para feitiço).
    - Loop de combate rodada a rodada no terminal até um dos personagens ser derrotado.

---

- [ ] **4. Conversor Bidirecional de Algarismos Romanos (Lógica + Mapeamentos)**
  - **Tempo estimado:** 15 a 25 min
  - **Conceitos:** Mapeamento com tuplas/dicionários, manipulação de strings, testes com `assert`.
  - **Objetivo:**
    - `inteiro_para_romano(num: int) -> str`: conversão com tabela ordenada decrescente.
    - `romano_para_inteiro(romano: str) -> int`: leitura sequencial considerando subtrações (ex.: IV, IX, XL, XC).

---

- [ ] **5. Mini Conta Bancária com Histórico de Extrato (POO + Tratamento de Exceções)**
  - **Tempo estimado:** 20 min
  - **Conceitos:** Exceções customizadas (`SaldoInsuficienteError`), `datetime`, classes e encapsulamento.
  - **Objetivo:**
    - Classe `Transacao` (`tipo`, `valor`, `data_hora`).
    - Classe `ContaBancaria` com `depositar(valor)`, `sacar(valor)` e `exibir_extrato()`.
    - Regras de validação (impedir depósitos negativos e saques sem saldo suficiente).
