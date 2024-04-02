# ANALISE-DE-LINGUAGE-NATUARAL-AZURE

Esse Repiositório é uma demonstração do uso do Language Studio para analise de comentarios de pessoas sobre um Hotel

1. Para começar vamos criar o recurso: Language Service
![image](https://i.imgur.com/4rShLbb.jpeg)

2. Preencher as seguintes informações e clicar em: review + Create e depois em create novamente
![iamge](https://i.imgur.com/2y0eUH6.jpeg)

3. Após o deployment concluído clicar em: Go to resource group
![iamge](https://i.imgur.com/mTqmW6I.jpeg)


## Language Studio
O Language Studio (https://language.cognitive.azure.com/) tem um objetivo semelhante ao Speech Studio, contudo o enfoque dele é na leitura de documentos ou textos, em que ele irá analizá-los e retornar dados como conversão de texto para fala, tradução e entre outros.

1. Ao acessar o Language Studio, ele pedirá para você pedir o tipo de recurso (nesse caso o Language) e o nome do recurso criado agora à pouco e clicar em done
2. Selecionar Classyf text  e analize de sentimentos e opniões
![iamge](https://i.imgur.com/deXZuUS.jpeg)

3. Escolher o idioma e inserir o texto e depois clicar em  Run
![iamge](https://i.imgur.com/Sw1830v.jpeg)
![iamge](https://i.imgur.com/MgTnvVO.jpeg)

OBS: O texto inserido foi:
The Royal Hotel, London, United Kingdom
5/6/2018 
This is an old hotel (has been around since 1950's) and the room furnishings are average - becoming a bit old now and require changing. The internet didn't work and had to come to one of their office rooms to check in for my flight home. The website says it's close to the British Museum, but it's too far to walk.


## Resultados
![iamge](https://i.imgur.com/pjUo5Fv.jpeg)
![iamge](https://i.imgur.com/0zbPsdu.jpeg)
![iamge](https://i.imgur.com/N4UhaXK.jpeg)
![iamge](https://i.imgur.com/gQsE723.jpeg)

Neste resutado vimos como a ferramenta funciona,  a IA separa o texto em senteças, ler as frases separadas, identifica tags que foram avaliadas, analisa e faz o calculo em porcentagem dos sentimentos, nesse exemplo que demos foi 93% negativo.


