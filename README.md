# ChatGPT iOS UI · Web Study

Reprodução independente para navegador da demonstração visual em SwiftUI criada por [Bryan Ramirez-Gonzalez](https://github.com/bryanrg22/chatgpt-ios-ui)

**Este projeto não é o aplicativo oficial do ChatGPT nem tem afiliação com a OpenAI**

## O que foi implementado

- **40 telas** correspondentes ao catálogo `DemoScreen` do repositório original
- **80 capturas de referência**, com versões claras e escuras
- **Referência original**, que apresenta a captura visual exata da demonstração SwiftUI para cada tela, preservando a aparência original da imagem
- **Web interativa**, uma recriação independente em HTML, CSS e JavaScript com menus, campos, navegação, envio de mensagens de exemplo, painéis, configurações e demonstrações locais
- Catálogo pesquisável de todas as telas, seleção de tema e navegação entre estados
- Visualização responsiva em celulares e em um simulador de iPhone dentro do navegador desktop
- Sem APIs, login, chaves ou serviços externos de IA, nenhuma mensagem é enviada a um servidor

## Abrir no navegador

Com o GitHub Pages ativado para a branch `main` e a pasta raiz, a página fica em

https://100ratings.github.io/gpt2/

Para ativar, abra **Settings → Pages → Build and deployment → Deploy from a branch**, selecione **main** e **/(root)** e salve

O arquivo `index.html` é autossuficiente e não depende de compilação, npm nem servidor de aplicação

## Navegação

- No desktop, use o catálogo à esquerda e os controles **Dark / Light** e **Original reference / Interactive web**
- No iPhone, um **toque prolongado em uma área vazia** abre o catálogo com todas as telas
- Um toque com **dois dedos** também abre o catálogo
- As capturas de referência incluem áreas invisíveis de toque para acessar algumas telas relacionadas
- A URL aceita `?screen=chatHome&theme=dark&mode=reference` para abrir uma tela diretamente
- Atalhos no desktop: **G** catálogo, **L** tema, **R** apresentação, setas direita/esquerda para mudar de tela

## Limites de fidelidade

O código original é SwiftUI e depende de recursos nativos do iOS, como Liquid Glass, gestos, sistema de teclado e componentes do sistema operacional

**Nenhuma tecnologia web consegue executar essas views SwiftUI diretamente com fidelidade funcional integral**

Por isso existem duas apresentações separadas

1. **Original reference** mostra as capturas reais da própria demonstração em SwiftUI, com fidelidade visual à imagem da tela de referência, mas não é a view nativa executando no navegador
2. **Interactive web** recria a navegação e os principais componentes em tecnologias web, com interações demonstrativas e fidelidade visual aproximada, sem reivindicar equivalência perfeita

As capturas foram geradas no **simulador de iPhone 17 Pro com iOS 27**, em escala de 1 ponto por pixel, e podem ser proporcionalmente redimensionadas em aparelhos de tamanhos diferentes

## Dependência das capturas e imagens

As 80 capturas e algumas imagens de exemplo são carregadas diretamente do repositório público original via GitHub Raw

Este repositório contém o código web, mas **não hospeda cópias locais das 80 capturas nesta versão**, portanto a apresentação de referência depende da disponibilidade dos arquivos originais e de conexão com a internet

Se essas imagens não carregarem, a versão interativa em HTML continua disponível como apresentação alternativa

## Atribuição e licença

Projeto de origem: [bryanrg22/chatgpt-ios-ui](https://github.com/bryanrg22/chatgpt-ios-ui)

Original: Copyright (c) 2026 Bryan Ramirez-Gonzalez and contributors, distribuído sob a licença MIT

Foi mantida uma cópia da licença MIT original em [LICENSE](LICENSE), e o projeto original também mantém avisos de licenciamento próprios para arte, fontes e dependências

A reprodução web e o catálogo de navegação deste repositório são independentes e não utilizam o código SwiftUI como componente executável

**A demonstração é não oficial, não se conecta à OpenAI e não inclui as funcionalidades de IA do produto**
