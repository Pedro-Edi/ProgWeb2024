# Início de um Projeto com Discord Bot
## 1. O que é um Discord Bot?
- Um Discord bot é um programa que automatiza tarefas no servidor do Discord. Ele pode responder a comandos de texto, moderar chats, enviar mensagens e muito mais.

## 2. Pré-requisitos para Criar um Discord Bot
- Conta Discord: Para criar um bot, você precisará de uma conta no Discord.
- Conta Developer no Discord: Você precisará criar uma conta de desenvolvedor no Portal de Desenvolvedores Discord para criar seu bot.

## 3. Criar um Novo Aplicativo Discord
- Vá ao Portal de Desenvolvedores Discord e clique em "New Application".
- Defina um nome para seu aplicativo Discord (por exemplo, "MeuBot.

## 4. Criar um Bot
- Clique em "Bot" na coluna da esquerda.
- Clique em "Add Bot" para criar um novo bot. Isso permitirá que você interaja com o bot através de comandos.

## 5. Configurar a Chave de Token do Bot
- Copie o token do bot gerado na parte inferior. Este token é essencial para fazer com que o bot funcione corretamente. GUARDE ESTE TOKEN COM SEGURANÇA, nunca o compartilhe publicamente.

## 6. Configurar o Bot para um Servidor
- Volte para o seu servidor Discord onde deseja usar o bot.
- Abra o aplicativo do seu bot no portal de desenvolvedores, vá até a guia "OAuth2" e selecione "URL de convite".
- Selecione as permissões desejadas e gere o link para adicionar o bot ao seu servidor.
- Entre na url desse link e selecione o servidor que ele ficará.

# Como Usar o Bot no Seu Servidor Discord

## 1. Inicializar o Bot com Python
- Instale o Python em seu computador se ainda não tiver (você pode fazer isso através do site oficial do Python).
- Crie um novo arquivo Python em branco e salve-o com um nome (por exemplo, index.py).

## 2. Instale as Bibliotecas Discord.py
- Abra o terminal ou prompt de comando e instale a biblioteca discord.py com o comando:
  - pip install discord.py 

## 3. Criar o Código do Bot
- No seu arquivo index.py, adicione o seguinte código básico para inicializar o bot:
  - import discord
  - from discord.ext import commands

# Inicializar o bot com um prefixo
 ## 1. Configurar token
 - Vá até o arquivo .env , se não tiver crie um , e dentro dele precisa estar "TOKEN = {seu_token}" , no caso o seu_token foi aquele você tem configurou.

## 2. Testar o Bot no Servidor Discord
- Para testar o bot no discord , basta digitar "/" e selecionar aquela funcionalidade que você desejar.