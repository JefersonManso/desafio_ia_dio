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

<img src="https://github.com/JefersonManso/desafio_ia_dio/blob/main/inputs/foto_03png.png" alt="Página inicial do azure ai foundry">

4- Na página Serviços de IA, selecione o bloco Fala para experimentar os recursos de Fala de IA do Azure.

## Extrair entidades nomeadas com a Linguagem de IA do Azure no portal do Azure AI Foundry
Entidades nomeadas são palavras que descrevem pessoas, lugares e objetos com nomes próprios. Vamos usar a funcionalidade de extração de entidade nomeada da Linguagem de IA do Azure para identificar tipos de informações em uma revisão.

1- No playground Idioma, selecione Extrair informações. Em seguida, selecione o bloco Extrair entidades nomeadas.

2- Em Amostra, copie e cole a seguinte revisão:

<img src="https://github.com/JefersonManso/desafio_ia_dio/blob/main/inputs/foto_04.png" alt="Página inicial do azure ai foundry">

3- Selecione <strong>Executar</strong>. Revise a saída. Observe na seção Detalhes como as entidades extraídas vêm com informações adicionais, como pontuações de tipo e confiança. A pontuação de confiança representa a probabilidade de que o tipo identificado realmente pertença a essa categoria.

## Extrair frases-chave com a Linguagem de IA do Azure no portal do Azure AI Foundry
As frases-chave são as informações mais importantes no texto. Vamos usar o recurso de extração de frases-chave da Linguagem de IA do Azure para extrair informações importantes de uma revisão.

1- No playground Idioma, selecione Extrair informações. Em seguida, selecione o bloco Extrair frases-chave.

2- Em Amostra, copie e cole a seguinte revisão:

<img src="https://github.com/JefersonManso/desafio_ia_dio/blob/main/inputs/foto_05.png" alt="Página inicial do azure ai foundry">

3- Selecione Executar. Revise a saída. Observe as diferentes frases extraídas na seção Detalhes. Essas frases devem contribuir mais para o significado do texto.

## Resumir texto com a Linguagem de IA do Azure no portal do Azure AI Foundry

1- Vejamos os recursos de resumo do Azure AI Language. No playground de idiomas, selecione Resumir informações e, em seguida, selecione o bloco Resumir texto.

2- Em Amostra, copie e cole a seguinte revisão:

<img src="https://github.com/JefersonManso/desafio_ia_dio/blob/main/inputs/foto_06.png" alt="Página inicial do azure ai foundry">

3- Selecione Executar. Revise a saída. Observe que o resumo extrativo em detalhes fornece pontuações de classificação para as frases mais salientes.


### Arrumar
Se você não pretende fazer mais exercícios, exclua todos os recursos que não são mais necessários. Isso evita o acúmulo de custos desnecessários.


### Referências: 
  
<a>https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html</a>

<a>https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html</a>

<h1>
  <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Saiba mais aqui</span>
</h1>
