
# Documentação da Rota de Envio de Mensagens no WhatsApp

Esta documentação descreve a rota para enviar mensagens no WhatsApp através da API fornecida. A rota pode ser acessada com o seguinte formato:


## /api/message/{{3-beecrm}}/msg

Nesta rota, você pode enviar diferentes tipos de mensagens, incluindo texto, imagem, sticker, vídeo, GIF, áudio, documento, localização e vCard. Abaixo estão os detalhes sobre como formatar os dados para cada tipo de mensagem:

Enviar Mensagem de Texto:

```json
{
  "type": "text",
  "message": "",
  "phoneNumber": ""
}```
Enviar Imagem:

```json
{
  "type": "image",
  "phoneNumber": "",
  "url_file": "URL_DA_IMAGEM",
  "caption": ""
}```
Enviar Sticker:

```json
{
  "type": "sticker",
  "url_file": "URL_DO_STICKER",
  "caption": "",
  "phoneNumber": ""
}```
Enviar Vídeo:

```json
{
  "type": "video",
  "url_file": "URL_DO_VÍDEO",
  "caption": "",
  "phoneNumber": ""
}```
Enviar GIF:

```json
{
  "type": "gif",
  "phoneNumber": "",
  "url_file": "URL_DO_GIF",
  "caption": ""
}```
Enviar Áudio:

```json
{
  "type": "audio",
  "url_file": "URL_DO_ÁUDIO",
  "caption": "",
  "phoneNumber": ""
}```
Enviar Documento:

```json
{
  "type": "document",
  "message": "",
  "url_file": "URL_DO_DOCUMENTO",
  "caption": "",
  "fileName": "",
  "phoneNumber": ""
}```
Enviar Localização:

```json
{
  "type": "location",
  "latitude": ,
  "longitude": ,
  "phoneNumber": ""
}```
Enviar vCard:

```json
{
  "type": "vcard",
  "phone": "",
  "name": "",
  "phoneNumber": ""
}```
Certifique-se de substituir as informações relevantes nas URLs e números de telefone.

Observações:

Para cada tipo de mensagem, os campos obrigatórios podem variar. Certifique-se de fornecer os campos necessários para cada tipo.
Lembre-se de que esta é uma documentação resumida e você pode expandi-la conforme necessário para atender aos requisitos específicos da sua equipe ou projeto.
