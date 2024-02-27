<div align="center">
 
 <h1>IA Vision Studio</h1>
 
</div>

Detecte a localização de um ou mais rostos humanos em imagens, juntamente com atributos como pose, máscara facial e pontos de referência faciais.

 <p align="center">
  <a href="#Tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Documentação">Documentação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#License">License</a>
</p>

![_fd439442-0502-47e9-8ab7-6e02a335d448](https://github.com/augustomiller/AZ-Vision_lab/assets/990877/895d2668-81f2-4c64-9dd8-b76ed8e16df2)
<p align="center">

</p>

## Tecnologias

- [Azure Vision Studio](https://portal.vision.cognitive.azure.com/gallery/featured)
- [Microsoft Copilot](https://copilot.microsoft.com/)
- [VS Code](https://code.visualstudio.com/)
- [Bash](https://www.gnu.org/software/bash/)
- [Git](https://git-scm.com/)

  ## Documentação

- [Azure Visio Studio Doc](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/)
- [Microsoft Copilot Doc](https://learn.microsoft.com/en-us/microsoft-copilot-studio/)
- [VS Code Doc](https://code.visualstudio.com/Docs)
- [Bash Doc](https://www.gnu.org/software/bash/manual/bash.html)
- [Git Doc](https://git-scm.com/doc)
- [Markdown Doc](https://google.github.io/styleguide/docguide/style.html)

</br>

## Importante! ⚠️

<p>

  - O acesso ao serviço presencial é limitado com base em critérios de elegibilidade e uso para apoiar nossos princípios de IA responsável. O serviço Face só está disponível para clientes e parceiros gerenciados pela Microsoft. Use o formulário de admissão de Reconhecimento Facial para solicitar acesso. Para obter mais informações, consulte a página Acesso limitado facial.

  - Os atributos faciais são previstos através do uso de algoritmos estatísticos. Nem sempre podem ser precisos. Tenha cuidado ao tomar decisões com base em dados de atributo. Por favor, abstenha-se de usar esses atributos para anti-spoofing. Em vez disso, recomendamos usar a detecção de vivacidade facial. Para obter mais informações, consulte Tutorial: [Detectar vivacidade em rostos](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/tutorials/liveness).
</p>

</br>

## Vamos lá 🚀

- 1 Acessar o portal do azure: https://portal.azure.com/#home
- 2 Selecione "+ create a resource" 
- 3 Selecione a categoria AI + Machine Learning
- 4 Selecione Azure AI Services (Create)
- 5 Criar um novo Resource group, clicando em "Create New":

![005](https://github.com/augustomiller/API_RestFul-RubyWithSinatra/assets/990877/d790cf85-18f1-4729-be45-bb60bb9e01f4)

- 6 Crie o recurso na regiao East US (é mais barato!), e dê um nome!

![006](https://github.com/augustomiller/AZ-Vision_lab/assets/990877/1ef651aa-3da1-4a36-ae7f-518687a3fb85)

- 7 Em "Pricing tier" selecione Standart SO

![007](https://github.com/augustomiller/API_RestFul-RubyWithSinatra/assets/990877/115ce80a-43d9-46cd-914c-90f4c2f2166f)

- 8 Selecione o checkinbox

![008](https://github.com/augustomiller/API_RestFul-RubyWithSinatra/assets/990877/8c390437-9461-4999-9c47-ec32643725cc)

- 9 Clique em "Review + create"

![009](https://github.com/augustomiller/API_RestFul-RubyWithSinatra/assets/990877/585d6e4a-189f-41a7-bec5-e9f505ed4e01)

### Vai ficar parecido com essa imagem:

![preview](https://github.com/augustomiller/API_RestFul-RubyWithSinatra/assets/990877/39f882aa-1bc2-4973-989a-3d6b3a281675)

## Agora vamos acessar o portal

- [Portal Vision](https://portal.vision.cognitive.azure.com/gallery/featured)

- Vamos clicar em "View all resources"

![portal_vision](https://github.com/augustomiller/API_RestFul-RubyWithSinatra/assets/990877/3abaa1a4-458f-4521-9026-0f21daf04cc1)

- Selecione o seu recurso criado anteriormente e o selecione como padrao!

![recurso](https://github.com/augustomiller/API_RestFul-RubyWithSinatra/assets/990877/cd1e666e-b228-4cb3-bb36-bb452f1a2383)

- Vamos voltar na página anterior e selecionar a opção "Face"

![face](https://github.com/augustomiller/API_RestFul-RubyWithSinatra/assets/990877/c8e73180-8cb7-410f-9115-e938686e86d4)

- Clique no card "Detect faces in an image"

- Vamos ser redirecionados para a pagina principal da ferramenta.
- Marque a opção "Try it out"

![try](https://github.com/augustomiller/API_RestFul-RubyWithSinatra/assets/990877/f7dd4df6-f6b0-4070-8be8-5f132e5bcc77)

- Selecione a imagem  e pronto o Vision faz todo o trabalho!

![working](https://github.com/augustomiller/API_RestFul-RubyWithSinatra/assets/990877/75c15def-1e77-46e0-b8e5-5976bd634c1f)

## Json gerado

```json
[
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 141,
      "height": 201,
      "left": 470,
      "top": 186
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 510.5,
        "y": 256.4
      },
      "pupilRight": {
        "x": 574.7,
        "y": 263.7
      },
      "noseTip": {
        "x": 538.1,
        "y": 301.7
      },
      "mouthLeft": {
        "x": 502.2,
        "y": 325
      },
      "mouthRight": {
        "x": 568.7,
        "y": 331.8
      },
      "eyebrowLeftOuter": {
        "x": 489.4,
        "y": 240.3
      },
      "eyebrowLeftInner": {
        "x": 527.7,
        "y": 242.4
      },
      "eyeLeftOuter": {
        "x": 499.2,
        "y": 255.3
      },
      "eyeLeftTop": {
        "x": 512.1,
        "y": 251.9
      },
      "eyeLeftBottom": {
        "x": 509.2,
        "y": 259.8
      },
      "eyeLeftInner": {
        "x": 521.7,
        "y": 258.7
      },
      "eyebrowRightInner": {
        "x": 560.6,
        "y": 246.7
      },
      "eyebrowRightOuter": {
        "x": 599.5,
        "y": 254.3
      },
      "eyeRightInner": {
        "x": 563.5,
        "y": 264.2
      },
      "eyeRightTop": {
        "x": 574.3,
        "y": 258.4
      },
      "eyeRightBottom": {
        "x": 574.7,
        "y": 267.4
      },
      "eyeRightOuter": {
        "x": 586.1,
        "y": 264.8
      },
      "noseRootLeft": {
        "x": 532.7,
        "y": 264.2
      },
      "noseRootRight": {
        "x": 550.9,
        "y": 266.2
      },
      "noseLeftAlarTop": {
        "x": 524.8,
        "y": 288.2
      },
      "noseRightAlarTop": {
        "x": 554.1,
        "y": 291.3
      },
      "noseLeftAlarOutTip": {
        "x": 516.3,
        "y": 299.9
      },
      "noseRightAlarOutTip": {
        "x": 559.2,
        "y": 305.3
      },
      "upperLipTop": {
        "x": 537.3,
        "y": 323.7
      },
      "upperLipBottom": {
        "x": 535.5,
        "y": 329
      },
      "underLipTop": {
        "x": 533.7,
        "y": 344.7
      },
      "underLipBottom": {
        "x": 532.7,
        "y": 353.6
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "noMask",
        "noseAndMouthCovered": false
      }
    }
  }
]

```

## Guia de início rápido do Face

- [Guia rápido do Face](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/quickstarts-sdk/identity-client-library?tabs=windows%2Cvisual-studio&pivots=programming-language-python)


## License

<div align="center">
  
<p>This project is licensed under the MIT License. See the
  <a href="https://mit-license.org/">
    <img src="https://img.shields.io/static/v1?label=license&message=MIT&color=5965E0&labelColor=121214" alt="License"></a> file for details.</p>
<p>Made with&nbsp;💙 &nbsp;by Augusto Miller</p>
  
<div>
