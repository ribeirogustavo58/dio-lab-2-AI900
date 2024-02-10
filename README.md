# Serviços testados

Os serviços estão disponíveis e foram acessados no endereço https://portal.vision.cognitive.azure.com/ do "Vision Studio" e foram testados utilizando os créditos oferecidos pela própria Azure para experimentação.

1. **Extraia texto de imagens**

Imagem usada `test_extract_text_from_shakespeare_poem.jpg` para extrair suas informações de texto.

O resultado é salvo no diretório `output`.

2. **Adicione legendas às imagens**

Este serviço gera uma frase legível que descreve o conteúdo de uma imagem.

Eu testei com `test_recognize_objects.jpg`. Esta imagem foi obtida no Unsplash.

O serviço descreve a imagem como: “Um grupo de pessoas sentadas às mesas de um restaurante”

Para a imagem `test_ai_image_services.jpg` a legenda era: “Um grupo de pessoas caminhando na rua”.

3. **Serviços Espaciais**

Alguns serviços espaciais não estão abertos para teste com nossos ativos.

Fiquei curioso sobre os serviços que "Contam pessoas em uma área" e "Detectam quando pessoas entram/saem de uma zona".

4. **Detecte objetos comuns em imagens**

Para este serviço, utilizei `test_recognize_objects.jpg` e ele conseguiu detectar: ​​6 pessoas (1 perdida!) e 5 cadeiras.

![Print of detect objects service](outputs/print-detect-objects.png)

Também tentei com `grocery-shop.jpg` e `product-shelves.jpg` sem resultados.

O serviço semelhante ("Reconhecer e analisar produtos de prateleira") não pôde ser facilmente testado com imagens próprias.

5. **Adicione legendas densas às imagens**

Difere do serviço n. 3 mencionado. A legenda é totalmente detalhada.

Por exemplo, para a imagem `test_ai_image_services.jpg` a legenda era:

![Print of caption image](outputs/print-2-caption-image.png)
