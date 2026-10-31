<div align="center">

# 🕹️ Aventura nas Cavernas Ancestrais
<img width="800" height="400" alt="1791932279286" src="https://github.com/user-attachments/assets/42616d10-acb9-4f8a-9e40-a644d5d9f0a5" />


**Explore, Colete, Sobreviva**

Cada tesouro te aproxima da saída, e cada passo pode ser o último. Encare 10 cavernas, 3 heróis e monstros que não desistem. Sozinha ou em dupla, quem vai sobreviver?

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) &nbsp; ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) &nbsp; ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) &nbsp; ![Jogadores](https://img.shields.io/badge/Jogadores_1--2-8A2BE2) &nbsp; ![Status](https://img.shields.io/badge/Status_concluído-2EA44F)

</div>

</div>

---

##  Sobre o projeto

**Aventura nas Cavernas Ancestrais** é um jogo de ação e estratégia em grade que roda direto no navegador, sem instalação. Você controla um herói por 10 cavernas, coleta todos os tesouros, foge dos monstros e usa pedras para bloquear caminhos e se proteger. Quando o último tesouro é coletado, a saída da caverna aparece.

O jogo pode ser jogado **sozinho** ou **em dupla, no mesmo teclado**. Foi desenvolvido em grupo na graduação em Análise e Desenvolvimento de Sistemas (UNICID) para praticar lógica de programação, desenvolvimento de jogos e interface web.

##  Objetivo

1. Colete **todos os tesouros** da caverna: moedas, gemas, amuletos, cogumelos, orbes e provisões.
2. Quando o último tesouro for coletado, a **saída aparece**. Corra até ela!
3. Use **pedras** para bloquear os monstros e abra caminho quebrando as que você criou.
4. Se um herói cair, o outro pode continuar. O jogo só termina se **todos** os heróis forem derrotados.

##  Controles

| Ação | Jogador 1 | Jogador 2 |
|---|:---:|:---:|
| Mover | `↑` `↓` `←` `→` | `W` `A` `S` `D` |
| Criar pedra | `Espaço` | `F` |
| Quebrar pedra | `Enter` | `G` |
| Pausar | `Esc` | `Esc` |

A pedra é criada (ou quebrada) no bloco para onde o herói está olhando. Só é possível quebrar as pedras criadas por você; as rochas da caverna são fixas.


##  Funcionalidades

- 🗺️ **10 cavernas** com mapas diferentes e dificuldade crescente (de 9 a 25 tesouros por caverna)
- 👥 **1 ou 2 jogadores** no mesmo computador, com modo **cooperativo**
- 🧙 **3 heróis** à escolha: Assassino, Guerreiro e Andarilho
- 🪨 **Pedras estratégicas**: crie barreiras contra os inimigos e quebre-as para abrir caminho
- 👹 **Inimigos com comportamentos diferentes** (veja abaixo)
- ⭐ **Sistema de 1 a 3 estrelas** por caverna
- 💾 **Progresso salvo no navegador**: fases liberadas e estrelas conquistadas
- ⏱️ **Cronômetro** e contador de tesouros durante a partida
- ⏸️ **Pausa** a qualquer momento
- 🎨 Arte em pixel art e telas de menu ilustradas, com escala automática para o tamanho da janela

###  Inimigos

| Tipo | Comportamento | Dica |
|---|---|---|
| **Perseguidor** (goblins, caveman, viking...) | Vai atrás do herói mais próximo | Bloqueie o caminho com pedras |
| **Voador** | Também persegue, mas **atravessa pedras** criadas por você | Pedras não o detêm. Use as paredes da caverna |
| **Bando** | Anda de forma aleatória pela caverna | Observe o padrão antes de passar |

Cada caverna traz mais inimigos que a anterior: a caverna 1 tem 2 perseguidores, e a caverna 10 reúne 9 inimigos de todos os tipos.

###  Como funcionam as estrelas

| Estrelas | Condição |
|---|---|
| ★★★ | Concluir a caverna em até **90 segundos**, sem nenhum herói tombar |
| ★★☆ | Perder um dos critérios acima (demorar mais de 90 s **ou** ter um herói derrotado) |
| ★☆☆ | Perder os dois critérios |

O tempo em que o jogo fica pausado não conta.


##  Tecnologias utilizadas

| Tecnologia | Uso |
|---|---|
| **HTML5** | Estrutura das telas e menus |
| **CSS3** | Estilo dos menus, HUD, tela de pausa e animações |
| **JavaScript (puro)** | Lógica do jogo, controles, inteligência dos inimigos e colisões |
| **Canvas 2D** | Renderização do mapa, personagens e itens |
| **localStorage** | Salvar o progresso e as estrelas no navegador |

Não usa frameworks nem bibliotecas externas. Tudo roda em um único arquivo HTML.



##  Autoria

Projeto desenvolvido em grupo por **Kaylany** e colegas, na graduação em **Análise e Desenvolvimento de Sistemas (UNICID)**.
<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kaylany-thayna-b82931199) &nbsp;&nbsp; [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kaayllany) &nbsp;&nbsp; [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kaylanythayna@hotmail.com)

</div>


