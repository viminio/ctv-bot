# Crude Twitch Viewer Bot (CTVB)
[![](https://img.shields.io/github/downloads/jlplenio/crude-twitch-viewer-bot/total)](https://github.com/jlplenio/crude-twitch-viewer-bot/releases/latest)
[![](https://github.com/jlplenio/crude-twitch-viewer-bot/actions/workflows/pytest.yml/badge.svg)](https://github.com/jlplenio/crude-twitch-viewer-bot/actions/workflows/pytest.yml)
[![format & lint](https://github.com/jlplenio/crude-twitch-viewer-bot/actions/workflows/format_lint.yml/badge.svg)](https://github.com/jlplenio/crude-twitch-viewer-bot/actions/workflows/format_lint.yml)
[![](https://github.com/jlplenio/crude-twitch-viewer-bot/actions/workflows/build.yml/badge.svg)](https://github.com/jlplenio/crude-twitch-viewer-bot/actions/workflows/build.yml)

Isenção de responsabilidade: Apenas para fins educacionais!

Pequena ferramenta que gera instâncias silenciadas do Google Chrome via [Playwright](https://github.com/microsoft/playwright-python), cada um com uma conexão de proxy HTTP e agente de usuário diferente.
Cada instância navega para o canal do twitch, ativa o modo teatro e adere ao espaço de tela disponível.
As configurações em localStorage garantem a resolução mais baixa possível.

- Baixe o executável de um arquivo para Windows a partir do [Mais recente CTVB](https://github.com/jlplenio/crude-twitch-viewer-bot/releases/latest).  

Leia calmamente a [Wiki](https://github.com/jlplenio/crude-twitch-viewer-bot/wiki) para um [Tutorial detalhado](https://github.com/jlplenio/crude-twitch-viewer-bot/wiki/Detailed-Tutorial), [Dicas de uso](https://github.com/jlplenio/crude-twitch-viewer-bot/wiki/Advanced-control) e [Etapas de solução de problemas](https://github.com/jlplenio/crude-twitch-viewer-bot/wiki/Troubleshooting).

### Importante
- Você precisa fornecer seus próprios proxies HTTP para o [proxy_list.txt](proxy/proxy_list.txt)  
  Segue o [Guia de proxy de compartilhamento da Web](https://github.com/jlplenio/crude-twitch-viewer-bot/wiki/Webshare.io-Proxies-Guide), se você precisar comprar alguns.
- O Chrome já deve estar instalado em seu sistema.
- Testado com contagem de instâncias: Headless ~ 100, headful ~ 30.
- Testado no Windows 10.
- A carga da CPU e a largura de banda podem ficar pesadas. Canais com 160p funcionam melhor.

### Em ação

![](docs/gui.png)

#### Códigos de cores das caixas quadradas

⬛ - A instância é gerada.    🟨 - A instância está em buffer.    🟩 - A instância está assistindo ativamente.
 
#### Abertura em Headful
![](docs/instances_spawning.gif)  
(Se você usar em Headless, as janelas do navegador ficarão invisíveis)  


### Uso no Windows

Leia calmamente a [Wiki](https://github.com/jlplenio/crude-twitch-viewer-bot/wiki) para um [Tutorial detalhado](https://github.com/jlplenio/crude-twitch-viewer-bot/wiki/Detailed-Tutorial), [Dicas de uso](https://github.com/jlplenio/crude-twitch-viewer-bot/wiki/Advanced-control) e [Etapas de solução de problemas](https://github.com/jlplenio/crude-twitch-viewer-bot/wiki/Troubleshooting).

#### Etapas de início rápido
Baixe o executável de um arquivo para Windows a partir do [Mais recente CTVB](https://github.com/jlplenio/crude-twitch-viewer-bot/releases/latest).  

1. Extraia o arquivo zip para uma pasta.
2. Adicione seus próprios proxies ao proxy/proxy_list.txt ou siga o [Guia de proxy de compartilhamento da Web](https://github.com/jlplenio/crude-twitch-viewer-bot/wiki/Webshare.io-Proxies-Guide), se você precisar comprar alguns.
3. Inicie o executável e aguarde a GUI.
4. Gere instâncias pacientemente.

#### Interações com as caixas quadradas
🖱️ Botão esquerdo: Atualizar página. 
🖱️ Botão direito: Destrua a instância.
🖱️ Botão esquerdo + CTRL: Faça a captura de tela (salvo na pasta raiz).  




