# dio-lab-speech-language-studio

# Speech Studio

## Acesso ao Speech Studio

Aceder via url https://speech.microsoft.com/portal para explorar opções disponiveis.

Se ainda não foi configurado definir o recurso a usar (do tipo SpeechServices):

<img width="1649" height="909" alt="image" src="https://github.com/user-attachments/assets/fda7b08c-536d-4edc-aaa6-8feea40fa81e" />


### Uso do voz para texto

Aceder ao opção assinalada na imagem abaixo:

<img width="1596" height="778" alt="image" src="https://github.com/user-attachments/assets/e957deec-fe9f-4eef-b54c-f5a9a8c5100e" />

Seleccionar lingua (pt-PT) e carregar o seu proprio texto para analise (ficheiro "TextoVoz.wav" na pasta audio). 

Resultado conforme esperado, embora com ligeiros desvios nas palavras mais complexas:

<img width="1626" height="933" alt="image" src="https://github.com/user-attachments/assets/b5c0ce1d-88b0-4f28-922c-795d852e2f48" />

Texto do audio original:

> A perseguição ao Goeben e Breslau foi uma ação naval ocorrida no início da Primeira Guerra Mundial entre forças do Reino Unido sob o comando do almirante sir Berkeley Milne contra aquelas da Alemanha sob o comando do vice-almirante Wilhelm Souchon. Ela ocorreu entre os dias 4 e 10 de agosto de 1914 no Mar Mediterrâneo e Mar Egeu quando elementos da Frota do Mediterrâneo britânica tentaram interceptar as duas embarcações da Divisão do Mediterrâneo alemã.

Texto detetado:

> A perseguição ao Goben e brylao foi uma ação naval ocorrida no início da Primeira Guerra Mundial entre forças do Reino Unido, sob o comando do almirante Sir Berkeley Millm contra aquelas da Alemanha, sob o comando do Vice Almirante o Aleluia. Ela ocorreu entre os dias 4 e 10/08/1914 no Mar Mediterrâneo e Mar Egeu quando elementos da frota do Mediterrâneo britânica tentaram intercetar as 2 embarcações da divisão do Mediterrâneo alemã. 

### Aplicação (next steps)

O portal disponibiliza zona que explica como usar o serviço em aplicações, fornecendo exemplos, a documentação e informação sobre custos:

<img width="1267" height="602" alt="image" src="https://github.com/user-attachments/assets/34959da2-7a3a-438c-9087-5f7b3b178eb7" />


## Resumo do Speech Studio

Além dos exemplos há outras modalidades interessantes. Não esquecer do possível custo associado ao utilização e possiveis falhas na detetação (nas palavras menos comuns/nomes proprios etc.).


# Language Studio

## Criação do novo resource

Criar o novo recurso na sua subscriação do Azure, do tipo "Language service":

<img width="1190" height="707" alt="image" src="https://github.com/user-attachments/assets/ce4c40dc-57ed-4267-b597-3bc84019b99d" />

O mesmo serve para ser usado no Language Studio.

## Acesso ao Language Studio

Aceder via url https://language.cognitive.azure.com/ para explorar opções disponiveis.

Se ainda não foi configurado definir o recurso criado no passo anterior como recurso que deve ser usado para acesso aos funcionalidades.

### Uso de reconhecimento do sentimento

Aceder ao opção assinalada na imagem abaixo:

<img width="1460" height="899" alt="image" src="https://github.com/user-attachments/assets/a88d80e8-b847-4a4c-b2b8-ab4acb245ed8" />


Carregar o seu proprio texto para analise.

> Unfortunately, our experience at the SoSoHotel was disappointing. The front desk staff were unprofessional and seemed uninterested in helping us. Our room was not as clean as expected, and the mattress was very hard and uncomfortable, making for a poor night's sleep. We also found the Wi-Fi to be unreliable, which was a major inconvenience for our business trip.

Resultado conforme esperado (negativo). Portal assinala as palavras chaves usadas na deteção do sentimento, conforme pode se ver nas imagens infra:

<img width="607" height="672" alt="image" src="https://github.com/user-attachments/assets/39a0e7f9-43f5-494f-a32d-af6ca990aa39" />

<img width="912" height="653" alt="image" src="https://github.com/user-attachments/assets/29c39c6a-2856-4216-aa57-c83da56ab6e3" />

### Aplicação (next steps)

O portal disponibiliza zona que explica como usar o serviço em aplicações, fornecendo exemplos, a documentação e informação sobre custos:

<img width="1355" height="465" alt="image" src="https://github.com/user-attachments/assets/18da6819-9afb-44a4-b293-b0d57e056bbc" />


## Resumo do Language Studio

Além dos exemplos há outras modalidades interessantes. Não esquecer do possível custo associado ao utilização!

