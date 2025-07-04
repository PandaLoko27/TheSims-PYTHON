# 🧍‍♂️ THE SIMS - Jogo em Python

Bem-vindo ao **The Sims (PYTHON)**!  
Neste jogo de terminal, você assume o controle de um personagem fictício (Sim) e precisa ajudá-lo a sobreviver o maior número de dias possível, gerenciando suas necessidades básicas como fome, energia, higiene, diversão e dinheiro.  

---

## 📌 Funcionalidades

- 🎮 Sistema de ações diárias (comer, dormir, tomar banho, trabalhar, assistir TV)  
- 🛍️ Loja interativa com itens que melhoram os status  
- ☠️ Morte por negligência (fome, tédio, exaustão ou sujeira)  
- 📊 Relatório final com resumo dos dias sobrevividos  
- 🎲 Mecânica de tempo que reduz aleatoriamente os atributos a cada turno  

---

## 🧠 Regras do Jogo

Cada dia, você pode realizar uma ação. Ao final de cada turno:  
- Os atributos do personagem diminuem com o tempo.  
- Se algum deles chegar a 0, o personagem morre e o jogo termina.  
- Você pode visitar a loja para recuperar atributos com o dinheiro ganho no trabalho.  

---

## 🖥️ Como jogar

1. Certifique-se de ter o Python 3 instalado.  
2. Baixe ou clone este repositório:  
```bash
git clone https://github.com/seu-usuario/Simulador-de-Vida-PYTHON.git
````

3. Navegue até a pasta do projeto e execute o script:

```bash
python simulador_de_vida.py
```

4. Siga as instruções no terminal.

---

## 📂 Estrutura do Código

| Seção              | Descrição                                                              |
| ------------------ | ---------------------------------------------------------------------- |
| `Sim`              | Classe principal com atributos e métodos para gerenciar o personagem   |
| `status()`         | Retorna os atributos atuais do personagem                              |
| `mostrar_status()` | Exibe os valores de status no terminal                                 |
| `checar_estado()`  | Verifica se o personagem ainda está vivo                               |
| Ações              | `comer()`, `dormir()`, `trabalhar()`, `tomar_banho()`, `assistir_tv()` |
| `comprar_item()`   | Menu de compras com melhorias pagas                                    |
| `passar_tempo()`   | Diminui aleatoriamente os status a cada rodada                         |
| `simular_jogo()`   | Lógica principal do jogo e loop de interação                           |

---

## 🛠️ Tecnologias Utilizadas

* Python 3.13.3
* Programação orientada a objetos (POO)
* Terminal/CLI para interação

---

## 📸 Demonstração (Console)

```
=== Dia 3 ===
Status de Lucas:
Fome: 45
Energia: 70
Diversão: 60
Higiene: 50
Dinheiro: 100

Escolha uma ação:
1. Comer
2. Dormir
3. Tomar banho
4. Trabalhar
5. Assistir TV
6. Comprar item
0. Sair do jogo
```

---

## 📄 Licença

Este projeto está licenciado sob a **MIT License**.
Sinta-se livre para usar, modificar e distribuir.

---

## 🙋 Sobre o Autor

Desenvolvido por **Otávio Guedes**
Estudante de Engenharia de Software | Dev Back-end
