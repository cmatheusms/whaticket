<h1 align="center">Whaticket Baileys |Canal Vem Fazer</h1>

<h1 align="center">https://www.youtube.com/channel/UCwFO9ylM7gHxYIXfJqAo1vQ</h1>


## Vamos instalar?

FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/ctichat/instaladorvemfazer install && sudo chmod -R 777 ./install && cd ./install && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd && cd ./install && sudo ./install_instancia
```


## Para Instalação você precisa:

Uma VPS Ubuntu 20.04 (Configuração recomendada: 3 VCPU's + 4 GB RAM)

Subdominio para Frontend

Subdominio para API - backoffice

Email válido para certificação SSL

## Personalizações

** Alterar Cor Primária: (#007aff)
/frontend/src/config.json
/frontend/src/App.js
/frontend/src/layout/index.js /frontend\src\pages\Chat\ChatMessages.js

** Cores do Chat Interno:
frontend\src\pages\Chat\ChatList.js

** Cores da Lista de Tarefas
/frontend/src/pages/ToDoList/index.js

** Popover de Anuncios / Chat Interno
/frontend/src/components/AnnouncementsPopover/index.js
/frontend/src/pages/Chat/ChatPopover.js

** Logo e LogoLogin:
/frontend/src/assets

** Icone e Favicon:
/frontend/public

** Comando para rebuild, caminho absoluto /home/deploy/"nome"/

cd /frontend npm run build


