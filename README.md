# 🐺🥕🍄 Lobo, Coelho e Cogumelo

<p align="center">
  <img src="banner.png" alt="Banner do Projeto" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C++-Programação-blue?style=for-the-badge&logo=c%2B%2B">
  <img src="https://img.shields.io/badge/Status-Concluído-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Projeto-Acadêmico-orange?style=for-the-badge">
</p>

> Jogo de lógica em C++ — versão para terminal local

**Autora:** Emanuele Kmiecik | **Linguagem:** C++

---

## 📖 Sobre o Projeto

**Lobo, Coelho e Cogumelo** é um jogo interativo de raciocínio lógico baseado em terminal.

O jogador assume o papel de um fazendeiro que precisa atravessar um rio levando três elementos, respeitando regras específicas para evitar conflitos.

> O desafio é tomar decisões estratégicas para completar a travessia com sucesso.

---

## 🎮 Personagens e Regras

| Personagem  | Restrição                                |
| ----------- | ---------------------------------------- |
| 🐺 Lobo     | Não pode ficar sozinho com o 🥕 Coelho   |
| 🥕 Coelho   | Não pode ficar sozinho com o 🍄 Cogumelo |
| 🍄 Cogumelo | Sem restrição direta                     |

---

## 🚀 Como Executar

### Pré-requisitos

* Compilador C++ (g++, MinGW, etc.)
* VSCode (recomendado)

### Passos

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/lobo-coelho-cogumelo.git

# 2. Entre na pasta
cd lobo-coelho-cogumelo

# 3. Compile
g++ src/main.cpp -o jogo

# 4. Execute
./jogo
```

---

## 🗂️ Estrutura do Projeto

```
lobo-coelho-cogumelo/
├── src/
│   ├── main.cpp
│   ├── ascii.h
│   └── ascii.cpp
├── assets/
├── README.md
└── .gitignore
```

---

## 🏆 Fluxo do Jogo

| Etapa | Ação                           |
| ----- | ------------------------------ |
| 1     | Escolher o primeiro personagem |
| 2     | Realizar travessias            |
| 3     | Tomar decisões estratégicas    |
| 4     | Evitar conflitos               |
| Final | Vitória ou Game Over           |

---

## 🧠 Conceitos Aplicados

| Conceito                | Descrição                   |
| ----------------------- | --------------------------- |
| Estruturas condicionais | Uso de `if` e `switch`      |
| Estruturas de repetição | Uso de `while`              |
| Funções                 | Organização modular         |
| Entrada e saída         | `cin` e `cout`              |
| Lógica                  | Resolução baseada em regras |

---

## ✨ Diferenciais

* ASCII Art interativo
* Experiência passo a passo
* Foco em lógica e tomada de decisão
* Código estruturado e didático

---

## 🤝 Como Contribuir

1. Fork do projeto
2. `git checkout -b minha-feature`
3. Commit: `git commit -m "feat: nova feature"`
4. Push: `git push origin minha-feature`
5. Pull Request

---

## 📜 Licença

Projeto acadêmico para fins de estudo.
