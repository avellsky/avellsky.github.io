# Manual do Usuário do Meteorium (Edição Gratuita)

O Meteorium visualiza as **"trilhas de poeira"** — faixas de poeira de cometas que produzem chuvas de meteoros — em 3D, com base em dinâmicas orbitais reais. A edição gratuita inclui **5.000 partículas de poeira de cinco retornos periélicos (1479, 1610, 1737, 1862 e 1992) do cometa 109P/Swift-Tuttle**, o corpo-parental das Perseidas.

- Órbitas integradas com REBOUND/ReboundX (gravidade planetária + pressão de radiação solar)
- Catálogo estelar: NASA Deep Star Maps 2020 (8K)
- Totalmente offline; sem coleta de dados e sem anúncios

## Layout da tela

![Screen layout](Meteorium/manual/img/fig_overview.jpg)

- Centro: visão 3D (arrastar = rotacionar, pinçar/roda do mouse = zoom)
- Canto superior direito: alternador de idioma EN/JP e botão ⓘ do painel de informações
- Painel direito: conjunto de dados, legenda das trilhas, configurações de exibição, pontos de vista e configurações de partículas
- Barra inferior: data/hora (UT), data de entrada, data, botão ponto de vista  e controles de tempo

Os painéis podem ser arrastados para qualquer lugar pelos seus puxadores; a altura do painel lateral pode ser ajustada pelo puxador inferior.

## Trilhas de poeira

As fichas coloridas listam as trilhas por ano de ejeção; toque para ativar ou desativar cada uma.  
“1992” é a poeira mais recente (periélio em 11/12/1992); as trilhas mais antigas já se alongaram ao longo da órbita.

## Configurações de exibição

Via Láctea / linhas de constelação / nomes / nome do cometa / rótulo da Terra / planetas rochosos / planetas gigantes / planetas / linhas de órbita / **partículas** / radiante.  

Padrões ao iniciar: linhas e nomes de constelações ligados; planetas terrestres e o radiante começam desligados (a edição gratuita sempre inicia com esses padrões).

## Pontos de vista

- **Eclíptica N**: visão de cima; cada toque gira 45° no sentido horário (**Eclíptica S**: sentido anti-horário)
- **Latitude Ecl.**: mantém a longitude atual e avança a latitude em 30°
- **Sol**: fixado no Sol; os toques alternam entre equinócio de primavera → rastreamento do cometa → Rastreamento da Terra (legenda no canto superior esquerdo; o rastreamento permanece após arrastar)
- **Terra**: visão do solo em direção ao radiante (veja abaixo)
- **Cometa**: acompanha o cometa; os toques alternam entre câmera frontal → câmera traseira → tela dividida (traseira|frontal) → frontal (legendas no canto superior esquerdo)
- **Visão livre**: tour automático — a cada 10 segundos a visão e o zoom mudam para um novo ângulo bem enquadrado; toque novamente ou arraste para interromper

Ao entrar na visão do solo, o radiante, as linhas e os nomes das constelações são ativados automaticamente; ao sair, o radiante é desativado novamente.

## A chuva de meteoros na visão do solo

![Meteor shower](Meteorium/manual/img/fig_ground.jpg)

Do solo, você observa os meteoros irradiando a partir do radiante da chuva (exibido com ZHR fixo de 5.000), **somente durante o período de atividade da chuva** (Perseidas: 17 de julho a 24 de agosto).

- Os meteoros aparecem por todo o céu; suas trajetórias remetem de volta para o radiante
- Perto do radiante: lentos, curtos e brilhantes — longe: rápidos, longos e fracos
- Bólidos (~7%) podem deixar um **rastro persistente** que se desloca e desaparece
- Aglomerados/clusters de meteoros (~4%): vários meteoros paralelos em poucos segundos
- Meteoros estacionários (~2%): um flash pontual no radiante (entrando de frente)
- Os planetas mostram suas cores verdadeiras e magnitudes aparentes

## Controles de tempo

- Campo de data (anos negativos para a.C.), botão **Hoje**
- **■** alterna entre parado ⇄ tempo real (×1)
- **< / >** avança a velocidade: ×2 → ×10 → ×100 → ×500 → ×1000 → ×5000 → ×10000
- Controle deslizante: velocidade contínua (centro = parado)
- Contador de retornos: número de retornos do cometa decorridos em relação à época do conjunto de dados

## Partículas

Fração renderizada: 10/25/50/100% e tamanho L/M/S (G/M/P - Grande/Médio/Pequeno).

## O que a versão Meteorium Pro adiciona

Todas as 13 chuvas principais + chuvas estabelecidas do IAU MDC, cálculo teórico com parâmetros ajustáveis e forças não gravitacionais, conjuntos de dados de órbitas observadas dos arquivos da IAU MDC (CAMS / SonotaCo / EDMOND / GMN / OTH), previsão de outbursts (surtos) de ZHR com seções transversais das trilhas, efemérides JPL DE, gravação de vídeo, exportação PNG/PDF, exportação de conjuntos de dados e configurações persistentes.

Os parâmetros das chuvas seguem o Calendário de Chuvas de Meteoros da IMO.

---

© Meteorium, Avellsky
