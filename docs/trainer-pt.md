# QTHome Trainer — guia para os beta testers

O QTHome Trainer ouve o seu rádio consigo enquanto usa o WSJT-X como sempre, e compara o descodificador FT8/FT4 do QTHome com o do WSJT-X. Assim vemos onde o nosso descodificador falha para o corrigir.

**Nunca transmite e nunca controla o rádio.** Só lê o áudio.

## O que é preciso

- Um Mac (Apple ou Intel) ou um PC com Windows 10/11.
- O rádio ligado ao computador pela sua placa de som USB (a que usa para o WSJT-X).
- **WSJT-X instalado** (grátis: <https://wsjt.sourceforge.io/wsjtx.html>). O Trainer usa o seu descodificador como referência. Não precisa de estar aberto.

## Instalar

1. Abra a página das versões: <https://github.com/SculptWorksLTD/QTHome/releases/latest>
2. Descarregue **QTHome-Trainer-Mac.pkg** (Mac) ou **QTHome-Trainer-Windows.zip** (Windows).
3. Mac: duplo clique no .pkg. Se o Mac recusar: clique direito no ficheiro → **Abrir**.
   Windows: abra o zip e inicie **QTHome Trainer.exe**. Se o Windows avisar: **Mais informações → Executar mesmo assim**.

## A primeira vez

1. Escreva o seu **locator** (4 ou 6 caracteres, ex. JN45ab): só se usa a zona.
2. Marque com que recebe e a sua antena.
3. Decida se envia **excertos de áudio** (leia a caixa): ajudam muito, mas pode dizer que não.
4. **Guardar e começar**.

## Sempre que usar

1. Escolha a **entrada de áudio do rádio** (ex. «USB Audio CODEC»).
2. Prima **Começar a ouvir**. No Mac, na primeira vez o sistema pede permissão para o microfone: responda **Permitir**.
3. Ponha o rádio numa frequência FT8 (ex. 14,074 MHz USB) e deixe-o a funcionar.

No fim de cada slot de 15 segundos vê uma tabela: em cada mensagem, ✓ se o QTHome a descodificou e ✓ se o WSJT-X a descodificou.

Se a janela não conseguir usar o áudio aparece o botão **Abrir no navegador**: o Trainer abre-se no seu navegador, onde o microfone funciona sempre.

## CW do rádio

Em **Definições** marque **CW** e prima **Começar a ouvir** na placa de som do rádio. Ouça CW como sempre: a cada 30 segundos dois descodificadores do QTHome releem o que ouviu e os indicativos são verificados com o Reverse Beacon Network (RBN). Se o The Rigger estiver aberto, o Trainer também sabe em que banda está. Só se enviam os casos úteis: um indicativo que o RBN nunca ouviu, ou os dois descodificadores em desacordo.

## Skimmer com a pen SDR (por agora só Mac)

É preciso uma pen RTL-SDR V3 ou V4 com uma antena HF (o rádio fica livre). Marque **Skimmer com a pen SDR**, escolha as bandas e prima **Ligar o skimmer**: a pen caça sozinha. Vai para a banda onde o RBN e o espectro mostram mais estações, lê-as todas ao mesmo tempo e muda assim que deixam de chegar indicativos novos. Quantas mais bandas escolher, mais testes faz. Os indicativos são comparados com o RBN; na tabela ✓ quer dizer confirmado, ? nunca ouvido pelo RBN.

## O que é enviado ao QTHome

- Só os casos úteis: sinais fracos, bandas cheias, mensagens descodificadas por só um dos dois descodificadores.
- **Nunca o seu indicativo**, nem o endereço IP, o nome do computador ou as suas pastas pessoais.
- Excertos de áudio de 15 segundos só se aceitou, no máximo 6 por hora. São apagados após 12 meses.

## Se algo não funcionar

Prima **Comunicar** em cima à direita, conte o que aconteceu e envie. É anónimo; sem internet fica em fila.

Feito por IU1MVI.
