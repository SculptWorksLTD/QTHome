# QTHome Trainer — guia para beta testers

O QTHome Trainer escuta o rádio consigo enquanto o usa como sempre e compara o
descodificador FT8/FT4 do QTHome com o do WSJT-X. Assim vemos onde o nosso
descodificador erra e corrigimo-lo.

**Nunca transmite nem comanda o rádio.** Só lê o áudio.

## O que é preciso

- Um Mac (Apple ou Intel) ou um PC com Windows 10/11.
- O rádio ligado ao computador pelo cabo USB (a placa de som dele, ex. «USB Audio CODEC»).
- Mais nada: o Trainer descarrega sozinho, uma vez, as ferramentas do WSJT-X necessárias para a comparação.

## Instalar

1. Abra a página das versões: <https://github.com/SculptWorksLTD/QTHome/releases/latest>
2. Descarregue **QTHome-Trainer-Mac.pkg** (Mac) ou **QTHome-Trainer-Windows.zip** (Windows).
3. Mac: duplo clique no .pkg. Se o Mac recusar: botão direito no ficheiro → **Abrir**.
   Windows: abra o zip e execute **QTHome Trainer.exe**. Se o Windows avisar: **Mais informações → Executar mesmo assim**.

## A primeira vez

Abre-se um guia em 5 passos:

1. **Boas-vindas**: o que faz o Trainer.
2. **A sua estação**: o locator (4 ou 6 caracteres, ex. JN45ab, só se usa a zona), o rádio, a antena.
3. **Áudio do rádio**: escolha a placa de som do rádio e sintonize uma frequência FT8 (ex. 14,074 MHz USB). O nível deve ficar na zona verde. No Mac, a primeira vez, o sistema pede autorização do microfone: responda **Permitir**.
4. **Privacidade**: o que enviamos e se quer enviar trechos de áudio.
5. **Tudo pronto**: carregue em **Começar a escutar**.

## A janela

- **Visão geral**: a escuta (entrada, nível com conselho, espetro), o **Estado da estação** (áudio, comparação com o WSJT-X, rádio, relógio, envio) e os seus números. As quatro luzes no topo dizem o mesmo num relance: verde está bem, amarelo para ver, vermelho para corrigir.
- **FT8 · FT4**: para cada slot, as mensagens lidas pelo QTHome e pelo WSJT-X (verde = ambos, vermelho = só WSJT-X, amarelo = só QTHome) e o acordo nos últimos slots.
- **CW** e **Skimmer**: ver abaixo.
- **Definições**: o que escutar, uso do computador, trechos de áudio, perfil da estação, atualizações.

Deixe o Trainer aberto (mesmo minimizado) enquanto usa o rádio: a cada arranque retoma a escuta sozinho.
O relógio do computador é verificado pela internet: se estiver errado, o Trainer corrige sozinho o corte dos slots.

## CW do rádio

No separador **CW** marque **Ler o CW do rádio** (com a escuta ligada). Escute CW como sempre: a cada 30 segundos
dois descodificadores do QTHome releem o que ouviu e os indicativos são verificados com a Reverse Beacon Network (RBN).
Se o The Rigger estiver ligado, o Trainer sabe também a sua banda e a verificação é mais precisa.

## Skimmer com a pen SDR (só Mac, por agora)

É preciso uma pen RTL-SDR V3 ou V4 com uma antena de HF (o rádio fica livre).
Em **Definições** marque **Skimmer com a pen SDR**; depois no separador **Skimmer** escolha as bandas e carregue em
**Ligar o skimmer**: a pen caça sozinha onde a RBN e o espetro mostram mais estações.
Na tabela ✓ significa confirmado pela RBN, ? nunca ouvido pela RBN.

## O que é enviado ao QTHome

- Só os casos úteis: sinais fracos, bandas cheias, mensagens lidas por apenas um dos dois descodificadores.
- **Nunca o seu indicativo**, nunca o endereço IP, o nome do computador ou pastas pessoais.
- Trechos de áudio de 15 segundos só se aceitou, no máximo 6 por hora. São apagados após 12 meses.
- Se o envio ainda não estiver ativo ou não houver internet, os casos esperam no computador e partem sozinhos depois: a linha **Envio** do estado diz sempre como está.

## Licença grátis para testers

Na Visão geral encontra as suas **horas de escuta**, as barras rumo à licença e o seu **código de tester** (QT-XXXX-XXXX): é anónimo. Escreva-o no formulário da página [Beta tester](https://iu1mvi.jimdofree.com/beta-tester/) com o seu indicativo.

- **10 horas** de escuta: QTHome PRO grátis por um ano.
- **100 horas** em pelo menos 3 meses diferentes: licença Fundador, PRO grátis para sempre.

Só contam as horas com o rádio ligado e sinal a chegar.

## Se algo correr mal

Carregue em **Relatar** em cima à direita, descreva o que aconteceu e envie. Chega de forma anónima; sem internet fica na fila e parte depois.

Feito por IU1MVI.
