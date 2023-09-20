<p align='center'> 
	<h1 align='center'>NLW IA</h1>
	<img src="https://i.imgur.com/sBCneOa.png" alt="Imagem do layout da página inicial do NLW IA" />
</p>

## 🧪 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

Front-End:
- [React]
- [Radix-UI]
- [TailwindCSS]
- [Shadcn-UI]
- [Typescript]
- [Axios]
- [AI]
- [FFmpeg]
- [Lucide-react]

Back-End:
- [Fastify]
- [Fastify/cors]
- [Fastify/Multipart]
- [Prisma]
- [OpenAI]
- [Zod]

## 🚀 Como executar

Clone o projeto e acesse a pasta do mesmo

Rodando o projeto no Front-End:
```bash
$ git clone https://github.com/Kauacnok/NLW-IA.git

$ cd web
$ npm i (para instalar as dependências)
$ npm run dev
````

Fazendo o setup o projeto no Back-End:
```bash
$ git clone https://github.com/Kauacnok/NLW-IA.git

$ cd server
$ npm i (para instalar as dependências)
```` 

Criando o banco de dados com o Prisma: 

```bash
$ npx run prisma migrate dev
```

Renomeie o arquivo .env-example para .env e preencha as váriaveis que estão dentro com seus respectivos valores, você precisa de uma chave de acesso da Open AI para preencher uma das váriaveis.

Rodando a API do projeto no Back-End de forma local:

```bash
$ npm run dev
```

## 💻 Projeto

O Next Level Week é um evento de 5 dias de mão na massa no código oferecido pela Rocketseat. O projeto foi fazer um site que faça um upload de um vídeo que o usuário selecionar, o projeto converta esse vídeo para um MP3 e por fim com as configurações selecionadas pelo usuário esperamos que gere uma transcrição do conteúdo do audio.

Feedbacks sempre são bem vindos :)

## 📖 O que eu aprendi

No Front-End eu acabei conhecendo o Shadcn-UI que é uma biblioteca que já vem com uma estilização pré definida e já vem com a acessibilidade usando por baixo dos panos a biblioteca Radix-UI, aprendi também sobre o ffmpeg para converter um vídeo mp4 para mp3 sem precisar subir para um servidor e sim usando a própria máquina do usuário para fazer a conversão.

No Back-End eu aprendi sobre o Fastify-Multipart que é um tipo de formulário que serve para manusear tipos de arquivos como vídeo, vi novamente sobre o Zod para tipagens e também aprendi a como mexer e fazer o setup de conexão com a API da Open AI com a biblioteca Open AI.

## 📝 License

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/Kauacnok/NLW-IA/blob/main/license) para mais detalhes.
