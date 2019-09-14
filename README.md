# Chatbotbase
Este arquivo tem a base de um chatbot feito em Rasa. Esá todo em portugues para facilitar, não far nada mais que comprimentar apenas isso.

## Instalar
Apos clonar os arquivos e ter o Rasa baixado na maquina siga o passo a passo:
#### 1-passo
vai fazer o traimaneto do bot
```
rasa train
```
#### 2-passo
para executar
```
rasa x
```
#### 1-passo
faça o treinamento do bot 


### Telegram
Ṕara usar ou testar no telegram usaremos o ngrok. Faça todos os passos no site deles apos isso vmaos para o terminal

```
ngrok http 5005
```
apos isso vamos executar o comando substituindo o XXXX pelo link gerado no comando anterio "NÃO PODE FECHAR O COMANDO ANTERIO TEM QUE FICAR ABERTO"
```
export RASA_X_HOSTNAME=https://xxxxxx.ngrok.io ; rasa x
```


