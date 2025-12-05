# 🎮 Jogo da Forca em Java (POO + Herança + Polimorfismo)

Este projeto é uma implementação do clássico **Jogo da Forca**, desenvolvido utilizando **Java** e **Programação Orientada a Objetos (POO)**.  
O objetivo do projeto é demonstrar conhecimentos fundamentais de design OO através de:

- Herança  
- Polimorfismo (Override)  
- Organização modular (Engine, Model, Provider)  
- Coleções (Set, HashSet)  
- Boas práticas de código  

O jogador deve adivinhar uma palavra secreta, recebendo feedback a cada tentativa até vencer ou perder.

---

## 🚀 Funcionalidades

### 🎯 **Funcionalidades principais**
- Escolha automática de palavras através de um `WordProvider`
- Exibição da palavra oculta (ex: `_ _ A _ O`)
- Controle de tentativas restantes
- Histórico de letras já usadas
- Validação de entradas repetidas
- Condição de vitória e derrota

### 🧰 **Recursos de POO usados**
- **Classe abstrata `Game`** → fornece estrutura base para jogos
- **Classe concreta `HangmanGame`** → sobrescreve o método `start()`
- **Polimorfismo** → Engine roda qualquer tipo de jogo
- **`WordProvider` separado** → responsabilidade única
- **Coleções com Set** → evita duplicação de letras
- **Override de métodos** → comportamento específico do jogo

---

## 📂 Estrutura do Projeto

src/

├── br/com/game/main/

│ └── Main.java # Ponto de entrada da aplicação

│

└── br/com/game/model/

├── Game.java # Classe abstrata base para jogos

├── GameEngine.java # Responsável por rodar o jogo

├── HangmanGame.java # Implementação do Jogo da Forca

└── WordProvider.java # Gerador de palavras aleatórias


## 🖥️ Como executar

1. Certifique-se de ter o **Java 17+** instalado.
2. Compile tudo
3. Execute pelo Main:

java br.com.game.main.Main.Java


## 📜 Licença

Projeto livre para estudo e modificação.
