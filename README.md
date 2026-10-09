# Celular na Romaria

Página de apoio a uma atividade de extensão universitária (Ciência da Computação) realizada na tenda de acolhimento aos romeiros.

Os romeiros recebem um panfleto com um checklist de 8 recursos do celular úteis durante a caminhada. O QR Code do panfleto abre esta página, que mostra o passo a passo com telas ilustradas para Android e iPhone.

## Conteúdo

1. Ficha médica e contato de emergência na tela de bloqueio
2. SOS rápido pelo botão lateral
3. Ligar para o socorro sem crédito (192, 193, 190, 191)
4. Localização em tempo real para a família (WhatsApp)
5. Mapa que funciona sem internet (Google Maps)
6. Modo de economia de bateria
7. Proteção contra perda ou roubo (IMEI, Encontre Meu Dispositivo / Buscar iPhone, Celular Seguro)
8. Lembrete de água e contador de passos

## Como funciona

- Um único arquivo `index.html`, sem dependências além das fontes do Google Fonts.
- As telas dos celulares são desenhadas em SVG por JavaScript a partir de uma lista de passos, então adicionar ou corrigir um tutorial é só editar os dados no array `T`.
- O botão Android/iPhone troca os passos; a escolha fica salva no navegador (`localStorage`) e o iPhone é detectado automaticamente na primeira visita.
- Layout responsivo, pensado para leitura no celular, com tema claro e escuro.

## Publicação

Hospedado com GitHub Pages a partir da branch `main`.

Desenvolvido com auxílio de IA (Claude, da Anthropic); conteúdo revisado e conferido nos aparelhos.
