# ⚔️ O Herói!

![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-4.27-313131?style=for-the-badge&logo=unrealengine)
![Blueprints](https://img.shields.io/badge/Blueprints-Visual%20Scripting-007ACC?style=for-the-badge)
![Paper2D](https://img.shields.io/badge/Paper2D-Pixel%20Art-orange?style=for-the-badge)

> Jogo de ação e aventura em estilo **2.5D** desenvolvido na **Unreal Engine 4.27**, combinando cenários tridimensionais com personagens e inimigos em *pixel art* (Paper2D).


---

## 🎮 Sobre o Projeto

Em **O Herói!**, o jogador atravessa diferentes biomas — passando pela **Vila**, a zona de **Guerra** e o **Cemitério** — enfrentando inimigos terrestres e voadores até o confronto contra o **Boss Final**. O jogo conta com um cronômetro integrado no HUD para incentivar corridas no estilo *speedrun*.

---

## ✨ Funcionalidades

* **Menu Principal Interativo:** Cena de fundo dinâmica no próprio mapa da vila com opções de *Novo Jogo*, *Créditos* e *Sair*.
* **HUD e Cronômetro Speedrun:** Exibição em tempo real de vida, contador de moedas e cronômetro contínuo via `Event Tick`.
* **Inimigos com IA e Herança de Blueprints:**
  * Navegação por `RecastNavMesh` com patrulha via *waypoints* e detecção de proximidade (*Sight Area* e *Attack Area*).
  * **Esqueleto (`esqueleto_bp`):** Inimigo terrestre base.
  * **Águia (`eagle_bp`):** *Child Blueprint* herdando a lógica do esqueleto com movimentação aérea em *Timeline* e ataque próprio.
  * **Boss Final:** Chefe localizado no cemitério com escala e atributos ampliados.
* **Combate e Coletáveis:** Ataque com flechas, moedas espalhadas pelos mapas e poções de recuperação de vida.
* **Sistema de Áudio:** Trilha sonora ambiente por mapa e efeitos sonoros dedicados para pulo, pouso, ataques, flechas, poções e coleta de moedas.

---

## 🕹️ Controles

| Tecla / Botão | Ação |
| :--- | :--- |
| **W A S D** | Movimentação |
| **Espaço** | Pular |
| **Clique Esquerdo** | Atacar / Disparar Flecha |
| **Mouse** | Navegar nos Menus |


---

## 🛠️ Tecnologias Utilizadas

* **Engine:** Unreal Engine 4.27
* **Lógica:** Blueprints Visual Scripting
* **Arte / Animação:** Paper2D (`PaperSprite` e `PaperFlipbook`)
* **Interface:** Unreal Motion Graphics (UMG)
* **Navegação / IA:** `RecastNavMesh`

---

## 🚀 Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone [https://github.com/IanLucca1/O-Heroi.git](https://github.com/IanLucca1/O-Heroi.git)
