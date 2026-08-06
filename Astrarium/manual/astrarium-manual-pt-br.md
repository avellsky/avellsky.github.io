# Astrarium — Manual do Usuário

**Versão 1.1**  
28 de julho de 2026

---

## Sumário

1. Introdução  
2. A tela  
3. Escolhendo onde você está  
4. Controlando o mapa  
5. Movendo-se no tempo  
6. O que o mapa mostra  
7. Chuvas de meteoros  
8. Cometas e asteroides  
9. Satélites  
10. Eventos  
11. A aba Info  
12. A aba Voz  
13. Se algo parecer errado  
14. Glossário  
15. Créditos e contato  

---

## 1. Introdução

O **Astrarium** é um planisfério e simulador astronômico para iPhone e iPad. Ele mostra o céu como está agora, mas também permite que você avance o relógio livremente — para o passado ou para o futuro — e coloca fases planetárias, eclipses, chuvas de meteoros, satélites e cometas no mesmo mapa.

As posições vêm da efeméride JPL DE421, dos modelos de precessão e nutação da IAU e dos dados de orientação da Terra do IERS, e são precisas o suficiente para planejar sessões reais de observação.

### 1.1 Requisitos

| Item              | Detalhe                                              |
|-------------------|------------------------------------------------------|
| Dispositivos      | iPhone / iPad (iOS e iPadOS 17.0 ou posterior)       |
| Orientação        | Retrato e paisagem ambos suportados                  |
| Preço             | Gratuito. Sem compras no aplicativo, sem publicidade |
| Rede              | O mapa e toda a astronomia rodam no dispositivo — funciona offline |
| Coleta de dados   | Nenhuma. Seu local e configurações permanecem no dispositivo |

Uma conexão com a internet é necessária apenas para **atualizar** três coisas:

- elementos orbitais de satélites (TLEs),
- elementos de cometas e asteroides (do MPC e do JPL),
- sua posição atual (isso usa os serviços de localização, não a rede).

### 1.2 Primeiros passos

1. Ao iniciar, o aplicativo mostra o céu sobre Tóquio no momento presente.  
2. Pressione 📍 na barra superior e permita o uso da sua localização. O Astrarium muda para a sua posição e informa o local registrado mais próximo e a que distância ele está. Se preferir não compartilhar sua localização, escolha um local da lista ou digite as coordenadas (capítulo 3).  
3. Ao ar livre, pressione 🔴 (visão noturna). Toda a interface fica vermelha para não prejudicar sua adaptação ao escuro.

---

## 2. A tela

A tela é dividida em cinco faixas, de cima para baixo.

| Faixa       | Onde            | O que faz                                      |
|-------------|-----------------|------------------------------------------------|
| Barra superior | Topo          | Relógio, local de observação, localização, painel, idioma, visão noturna |
| Mapa        | Meio            | O próprio céu — controlado com os dedos        |
| Barra rápida| Abaixo do mapa  | Controle deslizante de magnitude e doze interruptores comuns |
| Barra de tempo | Abaixo daquela | Modo de visualização, grades, mover e reproduzir o relógio |
| Assinatura  | Inferior        | Logotipo e autor, ambos links                  |

**Figura 1.** A visualização de céu inteiro (Tóquio, 12 de agosto de 2026, 20:00)

### 2.1 A barra superior

**Figura 2.** A barra superior: categoria e local do sítio, localização, painel, idioma, visão noturna

- **Relógio** — hora local no local de observação, Tempo Universal (UT) e Tempo Sideral Local (LST) lado a lado. O LST indica qual ascensão reta está no meridiano neste momento, o que é necessário ao apontar um telescópio.  
- **Categoria do sítio** — prefeituras japonesas, bons locais de observação, cidades do mundo, observatórios etc. Ao escolher observatórios, aparece um segundo menu **Região** para filtrar por continente.  
- **Sítio** — o local em si. As prefeituras e os locais de céu escuro vão do norte para o sul; as cidades do mundo estão em ordem alfabética, pela leitura do nome quando o aplicativo está em japonês.  
- 📍 — usar sua posição atual.  
- ☰ — abrir ou fechar o painel de detalhes (seis abas).  
- **EN / 日本語** — trocar o idioma. Os nomes dos objetos, os nomes das constelações e todas as descrições mudam junto.  
- 🔴 — visão noturna; pressione novamente para voltar às cores normais.

### 2.2 A linha de assinatura

O logotipo na parte inferior abre a página inicial do Astrarium e o © Avellsky abre a página do autor, ambos no navegador.

---

## 3. Escolhendo onde você está

Há três maneiras de definir o local de observação.

**Escolher da lista**  
Use os menus de categoria e sítio na barra superior. O aplicativo traz todas as 47 prefeituras japonesas, locais recomendados de céu escuro (cada um com sua prefeitura, listados do norte para o sul), as principais cidades do mundo e os observatórios do mundo com seus códigos MPC.

**Usar sua posição atual**  
Pressione 📍 e escolha “Durante o uso do app” quando o iOS perguntar. Sua latitude e longitude se tornam o local de observação, e o sítio registrado mais próximo é mostrado como referência.

**Digitar as coordenadas**  
☰ → aba Info → “Inserir coordenadas manualmente”. Preencha latitude, longitude e elevação e pressione “Usar esta posição”. “Preencher com a localização atual” copia sua posição presente para os campos.

Mudar o sítio atualiza o relógio, os horários de nascer e ocaso e toda a geometria do mapa juntos.

---

## 4. Controlando o mapa

### 4.1 Visualizações de céu inteiro e horizonte

Alterne com **Céu inteiro** e **Horizonte** à esquerda da barra de tempo.

- **Céu inteiro** — o céu todo como um círculo centrado no zênite, norte para cima e leste para a esquerda, exatamente como em um planisfério de papelão. A Via Láctea é desenhada nesta visualização.  
- **Horizonte** — parte do céu desenhada como você realmente a veria olhando para fora. O menu ao lado do botão escolhe para que lado você está olhando: N, L, S, O.

**Figura 3.** Visualização de horizonte, olhando para o sul, campo de 110 graus

### 4.2 Gestos

| Gesto              | Céu inteiro                                      | Horizonte     |
|--------------------|--------------------------------------------------|---------------|
| Arrastar com um dedo | Rotação diurna — o céu gira em torno do polo celeste e o relógio acompanha o dedo | Desloca a visualização |
| Pinça com dois dedos | Zoom em torno do ponto entre os dedos            | O mesmo       |
| Toque duplo        | Recentralizar no zênite                          | —             |
| Tocar em um objeto | Abre o popup de informações                      | O mesmo       |
| Roda do mouse      | Zoom                                             | Zoom          |
| SHIFT + arrastar   | Desloca o centro da visualização sem girar       | —             |

Arrastar na visualização de céu inteiro é o gesto do planisfério: o disco gira e o tempo simulado gira junto, para que você possa sentir com a ponta do dedo a que altura o Órion estará daqui a duas horas.

### 4.3 O que um toque informa

O popup mostra o nome, ascensão reta e declinação, azimute e altitude e a magnitude, com botões embaixo.

**Figura 4.** Saturno tocado: coordenadas, magnitude, nascer e ocaso, e dois botões

- **Centralizar e ampliar** — coloca o objeto no meio da tela, amplia e começa a rastreá-lo. Enquanto rastreia, o objeto permanece centralizado conforme o relógio avança. Solte-o com o botão Liberar no mapa ou com a tecla Esc; deslocar a visualização não interrompe o rastreamento.  
- **Visualização ampliada** (Sol, Lua e planetas) — abre uma janela que desenha o corpo como um disco. A Lua vem com sua idade, fração iluminada, libração e nome popular (Lua Rosa, supermoon etc.); Júpiter com as quatro luas galileanas; Saturno com os anéis e Titã; Marte com Fobos e Deimos. Você pode arrastar dentro da janela.

**Figura 5.** A visualização ampliada de Saturno, com os anéis e suas luas

Escolher um objeto de céu profundo traz uma fotografia e uma breve descrição; um cometa ou asteroide traz seus elementos orbitais e brilho estimado; um satélite traz seu alcance, altura e magnitude aparente com um botão **Próximas passagens visíveis**.

Com a arte das constelações ligada, tocar em uma das doze constelações zodiacais mostra o signo astrológico correspondente e suas datas de nascimento, junto com uma nota de que a precessão moveu os signos cerca de um mês em relação a onde o Sol realmente está.

**Figura 6.** O céu inteiro com as figuras das constelações desenhadas

---

## 5. Movendo-se no tempo

A barra de tempo tem duas linhas.

### 5.1 Passos e reprodução

| Controle          | O que faz                                              |
|-------------------|--------------------------------------------------------|
| −1d / −1h / −1m   | Voltar um dia, hora ou minuto                          |
| +1m / +1h / +1d   | Avançar um minuto, hora ou dia                         |
| +1Mo              | Avançar um mês sinódico (29,53 dias) — salta para a mesma fase lunar |
| Campo de data-hora| Ir diretamente para uma data e hora                    |
| ◀ / ▶             | Reproduzir para trás / para frente (pressione novamente para parar) |
| Agora             | Voltar ao presente                                     |
| ×1 … ×6000        | Velocidade de reprodução; em ×600 um segundo seu equivale a dez minutos de céu |

Com um teclado, ← e → movem ±10 minutos, com Shift ±1 dia, com Alt ±1 minuto, e ↑ ↓ movem ±1 hora.

### 5.2 Grades

O botão **Grades** abre um menu de sobreposições; você pode ter várias ao mesmo tempo.

| Sobreposição     | O que é                                                |
|------------------|--------------------------------------------------------|
| Grade Alt-Az     | Coordenadas horizontais — azimute e altitude           |
| Grade RA-Dec     | Coordenadas equatoriais, o sistema usado pelos catálogos de estrelas |
| Grade eclíptica  | Coordenadas eclípticas; os planetas e a Lua permanecem nessa faixa |
| Grade galáctica  | Coordenadas galácticas; a Via Láctea fica ao longo da latitude 0° |
| Equador celeste  | Desenhado como um único círculo máximo                 |
| Eclíptica        | O caminho do Sol, da mesma forma                       |
| Meridiano        | O círculo máximo norte–sul pelo qual os objetos transitam |

O espaçamento das linhas e a precisão dos rótulos acompanham o nível de zoom.

**Figura 7.** O menu de grades, com a grade RA-Dec e a eclíptica desenhadas

---

## 6. O que o mapa mostra

### 6.1 A barra rápida

O controle deslizante à esquerda é o **limite de magnitude**. Diminua-o e as estrelas fracas desaparecem, o que se aproxima muito de um céu de cidade; aumente-o e o mapa vai até a magnitude 6,5, o limite a olho nu.

A primeira linha controla o próprio mapa; a segunda, os tipos de objeto.

| Botão       | Mostra                                                |
|-------------|-------------------------------------------------------|
| Linhas      | As figuras das 88 constelações                        |
| Nomes       | Nomes das constelações                                |
| Arte        | Desenhos das constelações (86 delas; mostradas independentemente do limite de magnitude) |
| Estrelas    | Nomes das estrelas nomeadas                           |
| DSO         | Objetos Messier e Caldwell                            |
| Via Láctea  | A Via Láctea — desenhada na visualização de céu inteiro, ininterrupta até o horizonte |
| Lua         | Brilho do céu devido à luz da Lua                     |
| Chuvas      | Radiantes e taxas esperadas das chuvas de meteoros ativas (capítulo 7) |
| Cometas     | Todo cometa atualmente brilhante o suficiente (busca os elementos na primeira vez) |
| Satélites   | Satélites no mapa (busca os TLEs na primeira vez)     |
| Eventos     | Abre a aba Eventos                                    |
| Info        | Abre a aba Info                                       |

**Figura 8.** A barra rápida e a barra de tempo

### 6.2 A aba Visualização (☰ → Visualização)

Tudo o que a barra rápida não carrega fica aqui.

- **Planetas** — mostrar ou ocultar os planetas.  
- **Sol e luz da Lua** — luz do dia, crepúsculo e o brilho da Lua. Desligue para desenhar o céu como se fosse sempre escuro, o que serve para verificar onde estão as estrelas durante o dia.  
- **Espelho** — inverte a imagem para um buscador de telescópio que inverte.  
- **Trilhas de estrelas** — deixa um rastro atrás dos objetos em movimento durante a reprodução, de modo que o movimento diurno e as passagens de satélites são desenhados como linhas.  
- **Molduras de FOV** — retângulos para o campo de uma câmera ou círculos para uma ocular, sobrepostos ao mapa. “Adicionar moldura”, depois informe o tamanho do sensor e a distância focal, ou o campo aparente e a ampliação. Arraste o centro para mover a moldura, clique no centro para ampliar até ela, arraste um canto para girar. Útil para enquadrar uma fotografia ou para ver o que caberá no campo.  
- **Limite de mag** — o mesmo controle deslizante da barra rápida.

**Figura 9.** A aba Visualização

### 6.3 Exportar como PNG ou PDF

Salva o mapa para o horário e local atuais como imagem. Como esses arquivos se destinam a ser impressos e levados para o campo:

- o fundo é papel branco e as estrelas e linhas são pretas,  
- o brilho do céu (luz do Sol e da Lua) é omitido,  
- a Via Láctea é desenhada apenas como contornos, sem preenchimento,  
- a data, a hora e Astrarium © Avellsky aparecem no canto inferior direito.

**Figura 10.** Um mapa exportado: a Via Láctea desenhada como contornos em papel branco

### 6.4 Demonstração e gravação

**Demonstração** é um tour de cerca de dois minutos e meio. Ele roda sem som; cada cena é descrita em legendas abaixo do mapa. Passa pelo crepúsculo, a Via Láctea, um planeta, os anéis de Saturno, molduras de FOV, a Lua, uma chuva de meteoros, uma passagem da ISS, Starlink, a lista de eventos, a troca de idioma e o movimento diurno. Tocar na tela encerra o tour e restaura o que você tinha.

**Gravar** salva o mapa em movimento como vídeo (se o dispositivo não puder fazer isso, o botão avisa). Comece a gravar durante a demonstração e o arquivo se salva sozinho quando o tour termina.

---

## 7. Chuvas de meteoros

Use a aba Corpos ou o botão Chuvas na barra rápida.

### 7.1 A lista

O menu contém as principais chuvas do ano, ordenadas pela proximidade de seu máximo em relação à data do mapa. Escolher uma move o relógio para a noite desse máximo (cerca de 1h da manhã no horário local) e abre os detalhes.

| Campo              | Significado                                           |
|--------------------|-------------------------------------------------------|
| Máximo             | Dado tanto em Tempo Universal quanto no horário local do seu sítio |
| Radiante           | Ascensão reta e declinação, com sua altitude no máximo e agora |
| Velocidade de entrada | Quão rápido os meteoroides encontram a atmosfera   |
| Índice populacional r | A proporção de meteoros brilhantes; quanto menor, mais brilhantes |
| Corpo-pai          | O cometa ou asteroide de onde veio o enxame           |
| Taxa esperada      | Meteoros por hora, a partir do modelo abaixo          |

### 7.2 Como a taxa é calculada

O número em “por hora” não é o ZHR ideal — é o que você pode esperar do seu sítio naquele momento. Quatro fatores são multiplicados juntos:

1. **Distância do máximo.** Um perfil gaussiano: cerca de um dia de cada lado a taxa cai para o fundo esporádico, e fora do período de atividade nada é mostrado.  
2. **Altitude do radiante.** Quanto mais baixo o radiante, menos meteoros; abaixo do horizonte, nenhum.  
3. **Crepúsculo.** Zero entre o nascer e o ocaso do Sol, reduzido durante o crepúsculo na proporção do brilho do céu.  
4. **Luz da Lua.** Reduzido de acordo com a fase e a altitude da Lua.

As chuvas ativas também são listadas em uma caixa laranja no topo do mapa. Tocar em um nome na caixa abre seus detalhes; **Liberar** limpa a caixa (e desliga o botão Chuvas na barra rápida junto com ela).

**Figura 11.** O máximo das Perseidas (13 de agosto, 3h, 64 por hora esperados)

---

## 8. Cometas e asteroides

A metade inferior da aba Corpos.

- **Listar brilhantes agora** — os cometas e asteroides no céu, do mais brilhante para o mais fraco.  
- **Buscar** — por qualquer parte de um nome ou designação. Se o objeto não estiver nos dados locais, o Astrarium pede ao JPL e o adiciona (precisa de conexão).  
- **Todos / Cometas / Asteroides** — filtra a lista.  
- **Selecionados** — os objetos desenhados no mapa. Tudo o que você colocar aqui é plotado.  
- **Atualizar do MPC** — elementos frescos de cometas do Minor Planet Center e de asteroides do JPL. A data da última busca é mostrada abaixo.

Tocar em um cometa no mapa dá sua distância do Sol e da Terra, ângulo de fase, diâmetro estimado, elementos orbitais, período e época.

---

## 9. Satélites

A aba Satélites, ou o botão Satélites na barra rápida.

1. Pressione **Baixar / atualizar TLEs** primeiro (precisa de conexão). Se os elementos foram buscados há menos de duas horas, o aplicativo diz que estão atuais em vez de baixá-los de novo.  
2. Ative **Mostrar no mapa** e os satélites começam a se mover pelo céu.  
3. Escolha quais grupos plotar.

| Grupo             | Conteúdo                                              |
|-------------------|-------------------------------------------------------|
| Estações espaciais| A ISS e Tiangong                                      |
| Mais brilhantes (visual) | Os satélites brilhantes o suficiente para se ver |
| Ciência           | Satélites de pesquisa e observação                    |
| Starlink          | A constelação Starlink                                |
| Clima             | Satélites meteorológicos                              |

- **Limite de mag** — 4 por padrão, o que mantém a lista no que o olho consegue ver.  
- **Somente iluminados pelo Sol** — mostrar apenas satélites fora da sombra da Terra, ou seja, os que realmente estão pegando luz solar. Estes são os únicos que você consegue ver.

Tocar em um satélite dá seu alcance, altura, magnitude aparente e a idade de seus elementos. **Próximas passagens visíveis** lista todas as passagens nos próximos cinco dias.

Acima de ×600 de reprodução os satélites são pausados, porque a propagação não consegue acompanhar.

**Figura 12.** A aba Satélites, com as próximas passagens da ISS

---

## 10. Eventos

A aba Eventos lista eclipses, oposições e conjunções, solstícios e equinócios, máximos de meteoros, aproximações próximas da Lua e dos planetas, e ocultações.

- **Período** — 7, 30, 90 ou 180 dias, 1, 5 ou 10 anos.  
- **Direção** — futuros, passados ou ambos.  
- **Incluir ocultações** — a Lua passando na frente de uma estrela, com imersão ou emersão, limbo escuro ou brilhante, e a magnitude da estrela.  
- **Incluir passagens da ISS / Starlink** — adiciona passagens de satélites à lista.  
- **Somente eclipses** — restringe a eclipses, com circunstâncias locais (magnitude e horários para o seu sítio).  
- Toque em uma linha e **o mapa salta para aquele momento**, para que você possa ver por si mesmo como o céu estará.  
- O botão de recalcular. A primeira varredura de 5 ou 10 anos leva alguns minutos; o resultado é armazenado em cache e aparece instantaneamente depois.

**Figura 13.** A aba Eventos

---

## 11. A aba Info

- **Céu de hoje** — ocaso e nascer do Sol, início e fim do crepúsculo, a janela de escuridão, nascer e ocaso da Lua e idade lunar, os trânsitos do Sol e da Lua, a data lunissolar tradicional e o termo solar, e o tempo sideral local.  
- **Objeto selecionado** — a posição e os horários de nascer/ocaso do que você tocou por último no mapa.  
- **Inserir coordenadas manualmente** — como no capítulo 3.  
- **Créditos e fontes** — todos os catálogos, efemérides, imagens e bibliotecas que o aplicativo usa, com sua fonte, sua licença e a data em que foi verificado pela última vez. Segue a configuração de idioma.

**Figura 14.** A aba Info, “Céu de hoje”

---

## 12. A aba Voz

O Astrarium pode ler o céu em voz alta, em japonês ou inglês independentemente do idioma da interface.

- **Falar os destaques de hoje** — o que vale a pena observar esta noite.  
- **Falar o objeto selecionado** — a posição e os horários de nascer/ocaso do objeto que você escolheu no mapa.  
- **Taxa e Volume** — controles deslizantes.  
- **Parar de falar** — interrompe.

Isso é para o escuro, quando você preferir não olhar para uma tela de forma alguma, ou quando o olho estiver na ocular.

---

## 13. Se algo parecer errado

**A localização não funciona**  
Ajustes → Privacidade e Segurança → Serviços de Localização, e defina o Astrarium como “Durante o uso do app”. Você também pode pular a localização completamente e digitar as coordenadas na aba Info.

**Nenhum satélite aparece**  
Ou os TLEs nunca foram baixados, ou a reprodução está mais rápida que ×600. Com “Somente iluminados pelo Sol” marcado, satélites na sombra da Terra ficam ocultos.

**Nenhum cometa aparece**  
O botão Cometas não mostra nada quando nenhum cometa está mais brilhante que o limite, e buscar elementos atuais precisa de conexão.

**Nenhuma taxa de meteoros é mostrada**  
Você está a mais de um dia do máximo, ou fora do período de atividade. A taxa também é zero à luz do dia.

**Poucas ou muitas estrelas**  
Mova o controle deslizante de limite de magnitude. Para corresponder a um céu real, uma cidade fica em torno de 4, os subúrbios em 5 e algum, e um local de montanha escuro em 6,5.

**A lista de eventos está lenta**  
Somente a primeira varredura de 5 ou 10 anos, que leva alguns minutos. Depois fica em cache.

---

## 14. Glossário

| Termo                  | Significado                                           |
|------------------------|-------------------------------------------------------|
| Magnitude              | Brilho; quanto menor, mais brilhante, e uma magnitude é um fator de cerca de 2,5 |
| Azimute / altitude     | Direção em torno do horizonte (norte 0°, leste 90°) e ângulo acima dele |
| AR / Dec                | Coordenadas fixas no céu — o sistema que os catálogos de estrelas usam |
| Tempo sideral local    | A ascensão reta atualmente no meridiano               |
| Tempo Universal        | Tempo na longitude 0°                                 |
| Idade da Lua           | Dias desde a Lua nova; 0 é nova, cerca de 14,8 é cheia |
| Iluminação             | A fração do disco da Lua que está iluminada           |
| Massa de ar            | Espessura da atmosfera, 1 no zênite; quanto maior, pior a seeing |
| ZHR                    | Meteoros por hora com o radiante no zênite e um céu de magnitude 6,5 |
| Radiante               | O ponto de onde os meteoros de uma chuva parecem vir  |
| TLE                    | Elementos orbitais de um satélite; ficam desatualizados em poucos dias e precisam ser renovados |

---

## 15. Créditos e contato

Todas as fontes das quais o Astrarium calcula estão listadas no aplicativo em **Info → Créditos e fontes**. As principais são:

- Efeméride planetária: JPL DE421  
- Estrelas: Yale Bright Star Catalogue, Tycho-2  
- Céu profundo: os catálogos Messier e Caldwell; fotografias do Wikimedia Commons (apenas imagens com licença livre)  
- Satélites: Celestrak (TLEs), SGP4/SDP4  
- Cometas e asteroides: Minor Planet Center, JPL Small-Body Database  
- Orientação da Terra: IERS finals2000A  

**Autor:** Shinsuke Abe a.k.a. Avell  
**Página inicial:** https://avellsky.github.io/Astrarium/  
**Repositório-fonte do site:** https://github.com/avellsky/avellsky.github.io  
**Contato:** https://x.com/AvellSky  

Astrarium © Avellsky

---

*Tradução para o português do Brasil (fiel ao original em inglês). Ajustes finais a cargo do revisor.*
