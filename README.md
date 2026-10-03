# 🎱 Pool Ultimate — GameLab

Jogo de sinuca/bilhar 8-Ball para navegador, integrante da coleção **GameLab Engine / Teclabs Info**, desenvolvido por **Anthony Freitas**.

## v1.1 — primeira versão jogável
- Mesa completa com 6 caçapas
- 15 bolas numeradas + bola branca
- Formação triangular inicial
- Mira controlada pelo mouse
- Clique e segure para carregar a potência
- Colisão bola × bola com transferência de momento
- Rebote nas tabelas e atrito
- Detecção de bolas encaçapadas
- Reposição automática/manual da branca
- Contadores de tacadas e bolas encaçapadas
- Tema claro/escuro e áudio simples
- **6 cores predefinidas para o pano + seletor de qualquer cor**
- Preferências visuais persistidas com localStorage

## Controles
1. Mova o mouse sobre a mesa para apontar.
2. Clique e segure o botão esquerdo para carregar a força.
3. Solte para executar a tacada.
4. Aguarde todas as bolas pararem antes da próxima tacada.

## Tecnologias
HTML5, CSS3, JavaScript ES Modules, Canvas 2D e Web Audio API. Sem framework e sem dependências de runtime.

## Estrutura
`index.html` · `css/style.css` · `js/main.js` · `js/config.js` · `js/audio.js`

## Como executar
Use um servidor local (por exemplo, Live Server no VS Code) por causa dos ES Modules. Depois abra `index.html` pelo servidor.

## Limitações conhecidas da v1.0
A prioridade desta release é a mesa jogável e a física básica. Regras completas de 8-Ball, turnos, definição de lisas/listradas e CPU ainda não estão implementados. O modelo físico é voltado à diversão e estabilidade, não a uma simulação científica completa.

## Roadmap
- v2.0: regras completas de 8-Ball e dois jogadores locais
- v3.0: Jogador × CPU com dificuldades
- v4.0: polimento visual, partículas e áudio expandido
- v5.0: treino e desafios
- v6.0: spin/topspin/backspin/efeito lateral
- v7.0: modalidades adicionais

## Histórico de releases
### v1.0 — 02/10/2026
Primeira versão jogável: física, mesa, rack de 16 bolas, mira, força, caçapas, personalização da cor do pano e interface GameLab.

## GitHub
**Descrição sugerida:** `🎱 Pool Ultimate — jogo de sinuca 8-Ball em HTML5 Canvas com física 2D, mira, potência e mesa personalizável. GameLab Engine.`

**Topics sugeridos:** `javascript`, `html5`, `css3`, `canvas`, `game`, `pool-game`, `billiards`, `8-ball`, `physics`, `2d-game`, `web-game`, `gamelab`, `game-development`

## Autor
Anthony Freitas — GameLab Engine / Teclabs Info  
Portfólio: https://sammyfreitas.github.io/portfolio/


## v1.1 — Controles e reinício
- Rodinha do mouse recua/avança o taco e regula a potência.
- Espaço executa a tacada.
- Setas ↑/↓ funcionam como alternativa para potência.
- Nova Partida agora faz reset completo do rack, branca, placar, potência e estado da jogada.


## v1.2 — Correção de inicialização
- Removida dependência de ES Modules para permitir execução direta pelo `index.html` e Live Server.
- Novo botão **Iniciar jogo**.
- Configuração de cor agora possui fluxo explícito **selecionar → Aplicar cor da mesa**.
- **Nova partida** executa reset completo e remonta o rack.
- Rodinha do mouse regula potência; **Espaço** executa a tacada.


## v1.3 — Taco, potência e identidade
- Favicon alterado para uma bola 8 de sinuca.
- Controle consolidado: **rodinha do mouse regula a força; Espaço executa a tacada**.
- Potência máxima aumentada de 760 para 1500 para permitir uma quebra forte do rack.
- Incrementos da rodinha e das setas aumentados para tornar o ajuste de força mais responsivo.
