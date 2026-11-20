# QTHome — manual

O QTHome é o programa para toda a estação: rádio, log, CW, modos digitais, cluster, SDR, satélites, concursos e mais, numa só janela. Funciona no computador, sem assinatura para ouvir e descodificar.

## Instalar

- **Mac**: descarregue `QTHome-Mac.pkg`, abra-o e siga os passos. O QTHome fica em Aplicações.
- **Windows**: descarregue `QTHome-Windows.zip`, abra-o e arraste `QTHome.exe` para onde preferir (por exemplo o Ambiente de trabalho), depois abra-o.

O QTHome atualiza-se sozinho: quando sai uma versão nova, descarrega-a e instala-a ao fechar.

## A primeira vez

1. Ligue o rádio ao computador com o cabo USB e ligue-o.
2. Abra o QTHome: o rádio aparece sozinho no painel **Estação** (lá dentro está o The Rigger, que reconhece os rádios).
3. Clique em cima à direita em **indicativo?** e escreva o seu indicativo e o seu locator.
4. Para outro idioma: **Ajuda › Idioma…**

## A janela

- **Em cima**: os menus, o estado do rádio e da pen SDR, o seu indicativo e a hora UTC.
- **A barra do rádio** está sempre visível: escolhe o rádio, lê e muda a frequência (VFO A e B) e o modo, prime **PTT · TX** para transmitir (desliga-se sozinho após 3 minutos).
- **À esquerda** as secções; **à direita** o painel escolhido. As secções ainda não prontas estão marcadas «Em breve».
- Tudo funciona também pelo teclado e com leitor de ecrã; **Ajuda › Voz** diz em voz alta frequência, modo e sinal.

## As secções

- **Estação**: os rádios ligados, a frequência grande, o S-meter, um QSO rápido. Programas como WSJT-X, fldigi ou JS8Call ligam-se ao rádio através do QTHome: as instruções estão em «Como ligar os programas».
- **Rotor**: ligue um rotor (Yaesu GS-232 ou Hamlib rotctld) e aponte-o em graus ou para um locator, também pelo caminho longo.
- **Log**: cada QSO, exportar e importar ADIF. Em baixo, as **QSL eletrónicas**: LoTW (é preciso o TQSL, grátis), eQSL, QRZ Logbook e Club Log; as palavras-passe ficam no seu computador.
- **Fonia**: escuta e gravação, os últimos 60 segundos sempre salváveis, 4 memórias de voz (F1-F4) para transmitir. **FreeDV** (700D, 700E, 700C, 1600): escuta pelo áudio do rádio e «segure para falar». **Pi-Star / WPSD**: quem passa pelo seu hotspot DMR, D-STAR, YSF, com um clique para a barra QSO.
- **CW**: o descodificador CWEngine, o manipulador, as mensagens, o skimmer com a pen SDR. A descodificação CW é grátis para sempre.
- **Modos digitais**: FT8 e FT4 como o WSJT-X (recepção e transmissão), RTTY, PSK, APRS, WSPR, Hell, QRSS e SSTV. Q65, MSK144 e JT65 pelo WSJT-X aberto ao lado (quadro «Outros modos com o WSJT-X»).
- **Cluster e propagação**: DX cluster e Reverse Beacon Network com filtros; um clique num spot leva o rádio para lá. Dados solares e condições das bandas.
- **SDR**: recetor com a pen RTL-SDR, espectro e waterfall; clique para ouvir uma frequência.
- **Satélites e espaço**: próximas passagens, Doppler, seguimento com o rotor e correção do rádio.
- **Concurso**: ARI DX, CQ WW, CQ WPX, IARU HF, VHF e genérico; números, duplicados, Cabrillo. Enter regista, Esc limpa.
- **QTHome Chat**: salas de texto e de voz entre radioamadores; nada fica no servidor.
- **Winlink**: correio pela internet ou por rádio com o modem VARA (instalado à parte): entrada, saída, escrever. A senha do Winlink fica no seu computador.
- **Mapa** e **Ferramentas**: o mundo agora (spots, quem ouve você, linha cinzenta, ionossondas) e calculadoras para a estação.
- **Assistente IA**: escreva o que quer («põe o rádio em 14.074 FT8», «quando passa a ISS», «o que quer dizer QSB»). Trabalha no computador, sem internet, e nunca transmite.

## Grátis e PRO

Ouvir, descodificar e manter o log é sempre grátis. Transmitir a partir do QTHome, os automatismos, o concurso avançado e as QSL online fazem parte do PRO; os primeiros 30 dias são um teste completo. O PRO custa **12 € por ano**: cobre os custos de servidores e investigação.

## Se algo não funcionar

- **O rádio não aparece**: verifique o cabo USB e se o rádio está ligado; depois **Estação › Procurar os rádios de novo**.
- **Sem áudio**: no Mac permita o microfone ao QTHome em Definições do Sistema › Privacidade e segurança.
- **Comunicar um problema**: **Ajuda › Comunicar um problema ou uma ideia…** É enviado de forma anónima, sem indicativos, nomes ou endereços.

O QTHome é feito por IU1MVI. Se lhe for útil, pode oferecer-lhe um café: paypal.me/nerosdmf
