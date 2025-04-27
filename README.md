# Projeto de Desenvolvimento do Servidor — Hookah & Alesia

Estamos desenvolvendo um servidor de Ragnarok Online e, após avanços recentes nas configurações e arquivos, gostaria de compartilhar algumas ideias e propostas para o projeto.
Atualmente estou sem internet até segunda-feira, o que limita meus testes online, mas isso não impede o planejamento!
Conto com seu apoio para analisar as ideias e, se possível, colaborar no que for necessário.

## ✨ Propostas Iniciais:

### 1. Sistema de Troca de Classe Dinâmico

- O personagem principal poderá mudar de classe a qualquer momento.
- Ao realizar a troca:
  - Atributos e habilidades serão resetados.
  - Um NPC fará perguntas para determinar:
    - **1st Class**, **2nd Class** ou **3rd Class**.
- Ajustes:
  - **2nd Class:** Personagem setado como nível 99/70.
  - **3rd Class:** Personagem setado como nível 175/60.
- **Observação:**
  Essa mecânica possibilita que o jogador tenha apenas um personagem principal, mudando livremente conforme necessário, otimizando o desempenho do servidor.
  (Ainda assim, manteremos a opção de criar múltiplos personagens, caso desejado.)

### 2. NPC do Éden

- Criação de um NPC para distribuição dos equipamentos do Éden, facilitando o início do jogo.

### 3. Sistema de Zeny Liberado

- Zeny gratuito para:
  - Criação de lojas personalizadas.
  - Compra de visuais, consumíveis, buffs, estilos, etc.

### 4. Sala Exclusiva para NPCs

- Centralização de todos os NPCs em uma sala personalizada.
- Demais mapas ficarão livres de NPCs, deixando o servidor mais limpo e organizado.

### 5. Arenas

- **Arena PvP:**
  Para duelos e combates amistosos.
- **Arena MVP:**
  Para enfrentar MVPs de maneira organizada.

### 6. Sistema de Testes de Cartas e Refinamentos

- Enfoque no combate a MVPs para obtenção de cartas, exigindo sorte e trabalho em equipe.
- Refinamento de equipamentos utilizando materiais obtidos durante os testes.
- Ideia: Treinamento colaborativo, onde times enfrentam MVPs desafiadores para fortalecer seus equipamentos.

### 7. NPCs de Itens por Classe

- Criação de NPCs dedicados a cada classe:
  - Exemplo: **NPC Sentinela**, vendendo apenas equipamentos utilizáveis pela classe.
- Inclusão também de:
  - Poções específicas.
  - Consumíveis variados.

_(Neste ponto precisarei de ajuda na escolha dos itens para cada classe.)_

### 8. Peso e Inventário Ilimitados

- Remoção de limitações de peso e capacidade de inventário, permitindo liberdade total para testes.

### 9. NPCs de Buffs

- **NPC de Buffs Padrão:**
  Oferece buffs básicos gratuitos.
- **NPC de Buffs VIP:**
  Oferece buffs avançados para testes de builds mais fortes.

---

## 📌 Próximos Passos:

- [ ] Finalizar a implementação do sistema de troca de classes.
- [ ] Criar e configurar a sala exclusiva de NPCs.
- [ ] Definir lista de itens para cada classe (apoio necessário).
- [ ] Implementar arenas PvP e MVP.
- [ ] Criar sistema de buffs padrão e VIP.
- [ ] Ajustar peso e inventário para modo ilimitado.
- [ ] Finalizar configuração do NPC do Éden.
- [ ] Testar sistema de lojinhas personalizadas com Zeny liberado.

---

## 📅 Status Atual

- Configurações básicas realizadas.
- Avanço significativo nos arquivos.
- Aguardando retorno da conexão para testes online.

---
