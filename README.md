# Reconhecimento Facial e Transformação de Imagens em Dados no Azure ML

***Desafio 2 do Bootcamp Azure Fundamentals AI-900 da DIO***

O objetivo deste desafio é explorar os recursos do Estúdio de Visão da IA do Azure. Para começar, é necessário acessar o portal do Azure, clicar em **IA + Machine Learning** e, em seguida, escolher a opção **Serviços Cognitivos** (caso a página esteja em português) ou **Azure AI Services** (se estiver em inglês). Depois, basta clicar em **Criar**.

**OBS:** Esse procedimento irá conectar o serviço de inteligência artificial à sua assinatura do Azure e ao Visual Studio (Estúdio de Visão).

O processo de criação é simples. Não há necessidade de alterar a subscrição, pois ela já vem preenchida. Escolha ou crie um **Resource Group (Grupo de recursos)**, selecione a região e atribua um nome de sua preferência. Em seguida, vá até **Pricing tier (Tipo de preço)** e escolha **Standard S0**. Por fim, marque a caixinha confirmando que leu e compreendeu os termos de responsabilidade da IA e clique em **Examinar + criar (Review + create)** para concluir a criação do recurso.

Após essa etapa, acesse o portal de visão ([portal.vision.cognitive.azure.com/gallery/featured](url)) e selecione o recurso criado. Depois de selecionar o recurso, clique no "X" no canto superior direito para voltar à tela inicial e escolher o estúdio para trabalhar.

### Primeira Parte: Detecção Facial

O primeiro teste foi realizado com a detecção de faces. Foi necessário clicar em **Face** e enviar as imagens anexadas no arquivo de entrada. A IA conseguiu identificar as características das imagens e retornar um código JSON com a descrição das imagens.

![teste face homem](https://example.com/face-image.jpg)

### Segunda Parte: Reconhecimento de Texto em Imagens

A segunda parte envolveu a análise de textos presentes em imagens, identificando as palavras e gerando o código JSON correspondente. Essa funcionalidade permite analisar documentos por meio do reconhecimento de caracteres, extraindo qualquer texto das imagens, seja manuscrito ou impresso. Para realizar esse teste, basta acessar **Optical character recognition** e enviar a foto para análise.

![teste palavra em foto](https://example.com/ocr-image.jpg)

### Terceira Parte: Análise de Imagens e Identificação de Cenários

A terceira parte do teste foi dedicada à análise de imagens, onde cenários específicos foram identificados. Para realizar esse teste, basta acessar a página inicial do Vision Studio, clicar em **Image analysis**, depois em **Add captions to images**, e enviar a foto que deseja analisar. O código JSON será gerado com a descrição da imagem.

![analise de cenario](https://example.com/image-analysis.jpg)

## Links Importantes:

- [Lab 04 - Face Detection](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html)
- [Lab 05 - Optical Character Recognition](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)
- [Lab 03 - Image Analysis](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html)
