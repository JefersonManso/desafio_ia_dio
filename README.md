### Explorar a Fala no portal do Azure AI Foundry
O serviço de Fala de IA do Azure transcreve fala em texto e texto em fala audível. Você pode usar o AI Speech para criar um aplicativo que possa transcrever anotações de reuniões ou gerar texto a partir da gravação de entrevistas.

Neste exercício, você usará o Azure AI Speech no portal Azure AI Foundry, a plataforma da Microsoft para criar aplicativos inteligentes, para transcrever áudio usando as experiências de teste internas.

## Criar um projeto no portal do Azure AI Foundry
1 - Em uma guia do navegador, navegue até <a>https://ai.azure.com/?azure-portal=true</a>.

2 -Faça login com sua conta.

3- Na home page do portal do Azure AI Foundry, selecione Criar um projeto. No Azure AI Foundry, os projetos são contêineres que ajudam a organizar seu trabalho.

<img src="https://github.com/JefersonManso/desafio_ia_dio/blob/main/foto_01png.png" alt="Página inicial do azure ai foundry">


4 - No painel Criar um projeto, você verá um nome de projeto gerado, que pode ser mantido como está. Dependendo se você criou um hub no passado, verá uma lista de novos recursos do Azure a serem criados ou uma lista suspensa de hubs existentes. Se você vir a lista suspensa de hubs existentes, selecione Criar novo hub, crie um nome exclusivo para seu hub e selecione Avançar.

<img src="https://github.com/JefersonManso/desafio_ia_dio/blob/main/foto_02.png" alt="Página inicial do azure ai foundry">

## Importante: você precisará de um recurso de serviços de IA do Azure provisionado em um local específico para concluir o restante do laboratório.

1- No mesmo painel Criar um projeto, selecione Personalizar e selecione um dos seguintes locais: Leste dos EUA, França Central, Coreia Central, Europa Ocidental ou Oeste dos EUA para concluir o restante do laboratório. Em seguida, selecione criar.

2- Anote os recursos criados:
- Serviços de IA do Azure
- Hub de IA do Azure
- Projeto de IA do Azure
- Conta de armazenamento
- Cofre de chaves
- Grupo de recursos
3- Depois que os recursos forem criados, você será levado à página Visão geral do seu projeto. No menu à esquerda da tela, selecione Serviços de Playgrounds.

<img src="" alt="Página inicial do azure ai foundry">

Na página Serviços de IA, selecione o bloco Fala para experimentar os recursos de Fala de IA do Azure.

Captura de tela do bloco Fala selecionado na página Serviços de IA.

Explorar a conversão de fala em texto no Playground de Fala do Azure AI Foundry
Vamos experimentar a conversão de fala em texto no Speech Playground do Azure AI Foundry.

Na página Fala, role para baixo e selecione Transcrição em tempo real em Experimentar recursos de fala. Você será levado ao Speech Playground.

Selecione https://aka.ms/mslearn-speech-files para baixar speech.zip. Abra a pasta.

Em Carregar arquivos, selecione Procurar arquivos e navegue até a pasta onde você salvou o arquivo. Selecione WhatAICanDo.m4a e, em seguida, Abrir.

Procurar arquivos

O serviço de Fala transcreve e exibe o texto em tempo real. Se você tiver áudio em seu computador, poderá ouvir a gravação enquanto o texto está sendo transcrito.

Revise a saída, que deve ter reconhecido e transcrito com êxito o áudio em texto.

Neste exercício, você experimentou os serviços de Fala de IA do Azure no Playground de Fala do Azure AI Foundry. Em seguida, você usou a transcrição em tempo real para transcrever uma gravação de áudio. Você pôde ver a transcrição do texto sendo gerada enquanto o arquivo de áudio era reproduzido.

Arrumar
Se você não pretende fazer mais exercícios, exclua todos os recursos que não são mais necessários. Isso evita o acúmulo de custos desnecessários.

Abra o portal do Azure e selecione o grupo de recursos que contém o recurso que você criou.
Selecione o recurso e selecione Excluir e, em seguida, Sim para confirmar. O recurso é então excluído.
Saiba Mais
Este exercício demonstrou um dos muitos recursos do serviço de Fala. Para saber mais sobre o que você pode fazer com esse serviço, consulte a página Fala.
