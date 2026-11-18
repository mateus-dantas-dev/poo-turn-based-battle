
# ⚔️ Jogo de Batalha por Turnos — POO

Um pequeno jogo de batalha por turnos desenvolvido em Python, com o objetivo de praticar e aplicar os principais conceitos da Programação Orientada a Objetos (POO).

No jogo, o jogador controla um herói que precisa derrotar um inimigo utilizando ataques normais e habilidades especiais.

## 🎮 Sobre o Projeto

O projeto simula uma batalha entre dois personagens: um herói controlado pelo usuário e um inimigo controlado pelo próprio sistema.

Durante a batalha, o jogador pode escolher entre dois tipos de ataque:

- **Ataque Normal:** causa dano baseado no nível do personagem.
- **Ataque Especial:** causa um dano maior, utilizando uma habilidade exclusiva do herói.

O inimigo realiza seus ataques automaticamente após cada ação do jogador, até que um dos personagens fique sem vida.

## 🧱 Conceitos de POO Aplicados

O projeto foi desenvolvido utilizando os seguintes conceitos:

- **Herança:** as classes `Heroi` e `Inimigo` herdam características e comportamentos da classe `Personagem`.
- **Encapsulamento:** utilização de atributos privados e métodos getters para controlar o acesso às informações dos personagens.
- **Polimorfismo:** sobrescrita do método `exibir_detalhes()` nas subclasses, permitindo apresentar informações específicas de cada personagem.
- **Composição e organização:** a classe `Jogo` é responsável por gerenciar os personagens e controlar o fluxo da batalha.

## 🛠️ Tecnologias Utilizadas

- Python 3
- Biblioteca `random` (biblioteca padrão do Python)
- Programação Orientada a Objetos (POO)

## 📂 Estrutura do Projeto

```text
poo-turn-based-battle/
│
├── main.py
└── README.md
```

## ▶️ Como Executar

**1. Clone o repositório:**

```bash
git clone https://github.com/SEU-USUARIO/poo-turn-based-battle.git
```

**2. Entre na pasta do projeto:**

```bash
cd poo-turn-based-battle
```

**3. Execute o arquivo:**

```bash
python main.py
```

Não é necessário instalar bibliotecas externas.

## 🕹️ Como Jogar

1. Execute o programa.
2. Pressione Enter para continuar.
3. Escolha o tipo de ataque:
   - Digite `1` para Ataque Normal.
   - Digite `2` para Ataque Especial.
4. Acompanhe os danos causados e a vida dos personagens.
5. Continue até que o herói ou o inimigo seja derrotado.

## 📚 Objetivo de Aprendizado

Este projeto foi desenvolvido como exercício prático para consolidar conhecimentos em Python e Programação Orientada a Objetos, explorando a criação de classes, reutilização de código, encapsulamento, herança e polimorfismo.

---

**Desenvolvido com Python 🐍**
