# Sei lá.. uns 1000!?

Jogo de palpites numéricos para jogar em grupo, com a TV como palco. Uma pergunta aparece na tela ("Quantos litros de ar uma pessoa adulta respira por dia?") e cada um chuta um número. Ganha quem chegar mais perto **sem passar** da resposta.

**Jogar agora:** https://rulico.github.io/uns1000/

Funciona direto no navegador, sem instalar nada e sem criar conta.

---

## Dois jeitos de jogar

### 📺 Só na TV
A TV mostra as perguntas e as respostas. Os palpites são falados em voz alta ou anotados no papel, e a contagem de pontos fica por conta do grupo.

- **Enter** ou **Espaço**: revela a resposta e depois avança para a próxima pergunta. Funciona com o controle remoto.
- **Setas**: navegam entre as perguntas.

### 📱 Pelo celular
A TV vira o apresentador e cada pessoa joga pelo próprio celular.

1. Na TV, escolha as categorias, toque em **Continuar** e selecione **Pelo celular**.
2. Os jogadores escaneiam o QR code ou digitam o código da sala de 4 letras.
3. Cada um escolhe um nome e um avatar, entre 20 opções.

Cada rodada tem três fases:

1. **Palpite**: cada jogador manda um número pelo celular.
2. **Apostas**: a TV mostra todos os palpites em ordem, e cada jogador aposta suas fichas no palpite que acha que vai ganhar. Vale apostar no próprio palpite.
3. **Revelação**: a resposta aparece e o placar é atualizado.

## Pontuação (modo celular)

| Situação | Pontos |
| --- | --- |
| Seu palpite foi o mais próximo **sem passar** da resposta | +1 |
| Cada ficha sua apostada no palpite vencedor | +1 |

- Sempre existe a opção **"menor que todos"**, que vence quando todos os palpites passam da resposta.
- Com até 7 jogadores, cada um tem 1 ficha. Com 8 ou mais, são 2 fichas, que podem ir no mesmo palpite ou em palpites diferentes.
- Cabem até 20 jogadores por sala.
- A partida termina quando alguém chega a 10, 20 ou 30 pontos. A meta é escolhida antes de começar.
- Na configuração da sala, dá para deixar os palpites **anônimos** ou **identificados** durante as apostas.

## Perguntas

São 1.463 perguntas em 12 categorias. Antes de cada partida você escolhe quais categorias entram.

| Categoria | Perguntas |
| --- | ---: |
| Animes e mangás | 136 |
| Artes e cultura | 98 |
| Brasil | 118 |
| Ciências | 180 |
| Cinema | 105 |
| Esportes | 119 |
| História | 119 |
| Jogos de tabuleiro | 108 |
| Mundo e cotidiano | 100 |
| Quadrinhos | 158 |
| Séries de TV | 107 |
| Tecnologia | 115 |

- As perguntas não se repetem entre partidas no mesmo aparelho, até acabarem. Dá para zerar esse histórico na tela inicial.
- Cada pergunta tem um código discreto no canto da tela, como `CN-037`, para localizá-la na planilha.
- O botão 🚩 marca uma pergunta com problema (resposta errada, enunciado confuso etc.) para revisar depois.
- **Importar** permite carregar uma planilha própria de perguntas.

---

Projeto pessoal, feito por diversão para jogar com amigos. Hospedado no GitHub Pages; a conexão entre TV e celulares usa o [Supabase](https://supabase.com).
