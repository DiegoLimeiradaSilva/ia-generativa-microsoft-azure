# ia-generativa-microsoft-azure
- Gerando Imagens com o Microsoft Copilot [https://copilot.microsoft.com/](https://copilot.microsoft.com/).
- Input 1:
  
![image](https://github.com/DiegoLimeiradaSilva/ia-generativa-microsoft-azure/blob/main/imagens/01.png?raw=true)

- Output 1:

![image](https://github.com/DiegoLimeiradaSilva/ia-generativa-microsoft-azure/blob/main/imagens/02.png?raw=true)

- Input 2:

![image](https://github.com/DiegoLimeiradaSilva/ia-generativa-microsoft-azure/blob/main/imagens/03.png?raw=true)

- Output 2:

![image](https://github.com/DiegoLimeiradaSilva/ia-generativa-microsoft-azure/blob/main/imagens/04.png?raw=true)


#


# Reconhecimento de Texto a partir de imagens

- Passo a passo de experimento utilizando Vision Studio/ **Azure AI Vision** para extrair texto de imagens sem a utilização de código, com tecnologia OCR (Optical Character Recognition).

<br/>

## Passo 1
- Acessar [portal.azure.com](portal.azure.com) e clicar em "create a resource"

![image](https://github.com/DiegoLimeiradaSilva/ia-generativa-microsoft-azure/blob/main/imagens/05.png?raw=true)

## Passo 2
- Buscar por "Ai azure services" e clicar em "create"

![image](https://github.com/DiegoLimeiradaSilva/ia-generativa-microsoft-azure/blob/main/imagens/06.png?raw=true)

![image](https://github.com/DiegoLimeiradaSilva/ia-generativa-microsoft-azure/blob/main/imagens/07.png?raw=true)

## Passo 3
- Preencher as informações mostradas abaixo. O resource group pode ser novo ou existente. Escolhi um que eu já havia criado anteriormente. Depois disso, basta clicar em "review + create", e depois "create", e aguardar a finalização do deploy.

![image](https://github.com/DiegoLimeiradaSilva/ia-generativa-microsoft-azure/blob/main/imagens/08.png?raw=true)
![image](https://github.com/DiegoLimeiradaSilva/ia-generativa-microsoft-azure/blob/main/imagens/09.png?raw=true)
![image](https://github.com/DiegoLimeiradaSilva/ia-generativa-microsoft-azure/blob/main/imagens/10.png?raw=true)

- Esta é a tela depois da finalização do deploy

![image](https://github.com/DiegoLimeiradaSilva/ia-generativa-microsoft-azure/blob/main/imagens/11.png?raw=true)

## Passo 4
- Conectar o resource com o Vision Studio.
- Em outro navegador, ir para [https://portal.vision.cognitive.azure.com/?azure-portal=true](https://portal.vision.cognitive.azure.com/?azure-portal=true) e clicar em "View All Resources"

![image](https://github.com/DiegoLimeiradaSilva/ia-generativa-microsoft-azure/blob/main/imagens/12.png?raw=true)

- Clicar em "refresh" para que a lista seja carregada com o resource criado anteriormente, clicar para selecionar o mesmo, e depois clicar em "Select as default resource"

![image](https://github.com/DiegoLimeiradaSilva/ia-generativa-microsoft-azure/blob/main/imagens/13.png?raw=true)

## Passo 5
- Em outro navegador, abrir novamente a landing page [https://portal.vision.cognitive.azure.com/](https://portal.vision.cognitive.azure.com/), ir até a aba "Optical Character Vision" e clicar em "Extract text from images"

![image](https://github.com/DiegoLimeiradaSilva/ia-generativa-microsoft-azure/blob/main/imagens/14.png?raw=true)

## Passo 6
- Marcar a opção conforme imagem abaixo
  
![image](https://github.com/DiegoLimeiradaSilva/ia-generativa-microsoft-azure/blob/main/imagens/15.png?raw=true)

## Passo 7
- No portal, selecione "browse for a file" e selecione uma imagem com texto, e depois clique em abrir.
- A coluna da esquerda mostra a imagem fornecida, e a da direita, o resultado do texto extraído.

![image](https://github.com/DiegoLimeiradaSilva/ia-generativa-microsoft-azure/blob/main/imagens/16.png?raw=true)

- Teste com a imagem 2

![image](https://github.com/DiegoLimeiradaSilva/ia-generativa-microsoft-azure/blob/main/imagens/17.png?raw=true)

- Teste com a imagem 3

![image](https://github.com/DiegoLimeiradaSilva/ia-generativa-microsoft-azure/blob/main/imagens/18.png?raw=true)

