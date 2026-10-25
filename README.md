# Sei lá.. uns 1000!?

Jogo de palpites numéricos para jogar em grupo, com a TV como palco. Uma pergunta aparece na tela ("Quantos litros de ar uma pessoa adulta respira por dia?") e cada um chuta um número. Ganha quem chegar mais perto **sem passar** da resposta.

**Jogar agora:** https://rulico.github.io/uns1000/

Funciona direto no navegador, sem instalar nada e sem criar conta.

---

## Como começar

A tela inicial tem dois caminhos:

- **📱 Entrar numa sala**: para quem vai jogar pelo celular. A pessoa escolhe nome e avatar e entra na sala aberta na TV. Quem escaneia o QR code da TV cai direto aqui.
- **📺 Criar uma sala**: para a TV ou o computador que vai apresentar. Leva para a escolha das categorias e, em seguida, para as opções da partida.

## Dois jeitos de jogar

### 📺 Só na TV
A TV mostra as perguntas e as respostas. Os palpites são falados em voz alta ou anotados no papel, e a contagem de pontos fica por conta do grupo.

### 📱 Com celulares
A TV vira o apresentador e cada pessoa joga pelo próprio celular.

1. Na TV, toque em **Criar uma sala**, escolha as categorias e selecione **Com celulares**.
2. Os jogadores escaneiam o QR code ou digitam o código da sala, de 4 letras.
3. Cada um escolhe um nome e um dos 20 avatares rabiscados.

Cada rodada tem três fases:

1. **Palpite**: cada jogador digita um número no celular. Os pontos de milhar aparecem enquanto digita, e a unidade da pergunta aparece logo abaixo do campo, como "km" ou "anos".
2. **Apostas**: a TV mostra todos os palpites em ordem, e cada jogador aposta suas fichas no palpite que acha que vai ganhar. Vale apostar no próprio palpite.
3. **Revelação**: a resposta aparece, seguida do placar.

## Pontuação (modo com celulares)

| Situação | Pontos |
| --- | --- |
| Seu palpite foi o mais próximo **sem passar** da resposta | +1 |
| Cada ficha sua apostada no palpite vencedor | +1 |

- Sempre existe a opção **"menor que todos"**, que vence quando todos os palpites passam da resposta.
- Com até 7 jogadores, cada um tem 1 ficha. Com 8 ou mais, são 2 fichas, que podem ir no mesmo palpite ou em palpites diferentes.
- Cabem até 20 jogadores por sala.
- A partida termina quando alguém chega a 10, 20 ou 30 pontos, ou depois de um número fixo de perguntas.
- Os palpites podem aparecer **anônimos** ou **identificados** durante as apostas.

## Tempo para responder

Nas opções da partida dá para escolher **Sem tempo**, **⏱ Rápido** ou **⏳ Longo**:

| Fase | Rápido | Longo |
| --- | --- | --- |
| Palpite | 20 a 30 s | 30 a 40 s |
| Apostas | 10 a 15 s | 15 a 20 s |
| Resposta revelada | 8 s | 12 s |
| Placar | 5 s | 10 s |

- O tempo de palpite e de apostas cresce com o número de jogadores.
- A TV mostra um relógio no alto da tela. Os celulares mostram a contagem no topo.
- Quando o tempo acaba, o jogo avança sozinho.
- **Pausar e retomar**: botão **⏸** na barra de baixo da TV, clique no relógio ou tecla **P**. Só a TV controla o tempo.

## Na TV

- **Controle remoto ou teclado**: **OK**, **Enter** ou **Espaço** revela e avança. Cada tela já abre com o botão de avançar selecionado.
- **Botão ›**: um botão discreto fica fixo no meio da borda direita, em telas grandes, e avança qualquer tela sem precisar mover o ponteiro.
- **Telas grandes e TVs 4K**: o layout se amplia proporcionalmente.
- **Salas abandonadas**: depois de 1 hora aberta, a TV pergunta se a sala ainda está em uso. **Manter aberta** já vem selecionado. Sem resposta em 5 minutos, a sala é encerrada e os celulares são avisados.

## Sons e trilha

- **🔊 Efeitos sonoros**: entrada de jogador, palpite recebido, apostas, rufar de tambor na revelação, fanfarra no fim e tique-taque nos últimos segundos do tempo.
- **🎵 Trilha**: vem ligada e começa quando alguém toca em **Criar uma sala**. A música muda conforme o momento do jogo e abaixa sozinha na revelação. Toca só na TV, nunca nos celulares.
- Os botões 🔊 e 🎵 da TV controlam o som da sala. O 🔊 do celular silencia apenas aquele celular. Nenhum jogador consegue pausar o tempo nem desligar a música da TV.

| Momento | Música | Arquivo |
| --- | --- | --- |
| Tela inicial e sala aguardando | [TV Show](https://pixabay.com/music/funk-tv-show-281116/), de Kulakovka | `trilha/trilha-intro.mp3` |
| Pergunta e palpites | [Thinking Time](https://pixabay.com/music/build-up-scenes-thinking-time-148496/), de Music_For_Videos | `trilha/trilha-palpite.mp3` |
| Apostas | [Quiz Countdown](https://pixabay.com/music/upbeat-quiz-countdown-337785/), de VadymKuznietsov | `trilha/trilha-apostas.mp3` |
| Resposta revelada e placar | [Quiz Master](https://pixabay.com/music/upbeat-quiz-master-382651/), de BackgroundMusicMaster | `trilha/trilha-placar.mp3` |

Se algum arquivo faltar, aquele momento toca uma trilha sintetizada pelo próprio jogo.

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

- As perguntas ficam no arquivo [`perguntas.csv`](perguntas.csv). Editar esse arquivo, aqui no GitHub ou numa planilha exportada como CSV, atualiza o jogo em poucos minutos. As respostas vão só com o número, com vírgula para decimais e sem ponto de milhar.
- As perguntas não se repetem entre partidas no mesmo aparelho, até acabarem. Dá para zerar esse histórico na tela de categorias.
- Cada pergunta tem um código discreto no canto da tela, como `CN-037`, para localizá-la no arquivo.
- O botão ⚑ marca uma pergunta com problema (resposta errada, enunciado confuso etc.) para revisar depois.

---

## Créditos e licenças

**Músicas:** as quatro faixas da pasta `trilha/` vêm do [Pixabay](https://pixabay.com/music/) e são usadas sob a [Pixabay Content License](https://pixabay.com/en/service/license/). Essa licença permite usar as músicas de graça, sem exigir crédito, mas os créditos ficam registrados aqui como agradecimento aos autores:

- **TV Show**, de Kulakovka
- **Thinking Time**, de Music_For_Videos
- **Quiz Countdown**, de VadymKuznietsov
- **Quiz Master**, de BackgroundMusicMaster (faixa marcada no Pixabay como gerada por IA)

A licença não permite redistribuir os arquivos de música isoladamente. Eles estão neste repositório só para tocar dentro do jogo. Para usar as músicas em outro projeto, baixe-as direto no Pixabay.

**Efeitos sonoros, trilha sintetizada e avatares:** criados para este jogo, gerados por código.

**Fontes:** [Anton](https://fonts.google.com/specimen/Anton) e [Archivo](https://fonts.google.com/specimen/Archivo), via Google Fonts, sob a SIL Open Font License.

---

Projeto pessoal, feito por diversão para jogar com amigos. Hospedado no GitHub Pages. A conexão entre a TV e os celulares usa o [Supabase](https://supabase.com).
