# Desafio Oni

Agradecemos seu interesse em fazer parte da equipe mais incrível que você irá conhecer, os OniDevs. Abaixo temos todas as informações necessárias para a realização do seu desafio.

## Avisos Importates

- Crie um reposotório no GitHub para hospedar seu projeto. **Não relacione o projeto a Onimusic**. Esse desafio poderá acrescentar seu portifólio :).
- Utilize as ferramentas da nossa [Stack de Desenvolvimento](#stack-de-desenvolvimento).
- Recomendamos a consulta ao Google, Stackoverflow e Docs oficiais. Evite utilizar ferramentas de IA generativas (ChatGPT e afins). No seu dia-a-dia de trabalho ferramentas como essa podem ser utilizadas, porém, nesse momento, queremos avaliar sua capacidade de resolver problemas.
- Ao término do desafio, envie o link do repositório para o recrutador.
- Tenha a liberdade para perguntar qualquer dúvida durante o processo.

## Stack de Desenvolvimento

Como é do seu conhecimento, nossa equipe utiliza o Django como framework no Backend. Utilizamos juntamente com o Django o Django Rest Framework (DRF) para construção das APIs. Além disso, utilizamos o React JS como framework no Frontend.

## Desafio: Gestor de Catálogo Musical

Um catálogo é composto por um Artista, que possui vários Albuns que, por sua vez, podem possuir uma ou mais Faixas. Todo artista deve possuir informações básicas como nome, email e CPF. Albuns possuem código único chamado UPC que devem ser únicos e validados conforme a referência. Além disso, os albuns devem possuir uma propriedade que informe se o mesmo é um Single ou Album (Single é um Album que possui uma única Faixa e Album possui duas ou mais Faixas). Além disso, um album pode ser apenas do tipo vídeo, vídeo/áudio ou áudio.

### Requisitos:

- O campo CPF do artista deve ser único. Não deve existir outro artista com o mesmo CPF.
- O Album pertence a unicamente um Artista. Mas um artista pode ter vários Albuns.
- Um Album pode ter várias Faixas mas, uma Faixa pertence apenas a um Album.
- Um Album deve possuir um título e uma propriedade que retorne a quantidade de Faixas presentes nele.
- Um Album deve possuir uma propriedade que informe se o mesmo é Single ou Album.
- Uma Faixa deve possuir um título e uma duração em segundos.
- O CRUD de Album, Faixa e Artista devem ser realizados através do Django Admin.
- Deve haver um endpoint Rest para consulta de Album, Faixa e Artista.
- Deve haver uma aplicação Front End em React JS para consumir e exibir os dados da API.

Estrutura de Pastas Sugerida:
```
.
├── backend
│   ├── [arquivos do backend]
│
└── frontend
    ├── [arquivos do frontend]
```

## Critérios de Avaliação

- Documentação
- Comentários claros e objetivos
- Código limpo e organizado
- Reutilização de código
- Atender aos requisitos

## Referências

- [Docs Django](https://docs.djangoproject.com/en/5.0/)  
- [Docs React](https://react.dev/learn)
- [Docs DRF](https://www.django-rest-framework.org/)
- [O que é UPC](https://tecnoblog.net/responde/o-que-e-upc-codigo-de-produto/)
- [Vídeo 1 sobre Django](https://www.youtube.com/watch?v=nGIg40xs9e4)
- [Vídeo 1 sobre React](https://www.youtube.com/watch?v=SqcY0GlETPk)
