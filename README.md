# Aplicativo Lista de Tarefas

Bem-vindo ao projeto do Aplicativo Lista de Tarefas! Este repositório contém a aplicação front-end Vue.js e uma API Symfony para o back-end.

## Pré-requisitos

Certifique-se de ter o Docker e o Docker Compose instalados em sua máquina.

## Começando

1. Clone este repositório:

```bash
git clone https://github.com/seu-nome-de-usuario/to-do-list.git
```

2. Navegue até a pasta do projeto:

```bash
cd to-do-list
```

3. Execute o seguinte comando para iniciar os containers:

```bash
# buildar imagem
docker-compose build

# subir container
docker-compose up -d
```

Caso queira acessar o terminal dos containers você pode usar um dos comandos :

```bash
# front-end
docker exec -it to-do-list-front-end sh

# back-end
docker exec -it to-do-list-back-end sh
```

Isso irá criar e iniciar os containers para o front-end (Vue.js) e o back-end (API Symfony).

4. Acesse a aplicação em seu navegador:
   Front-end Vue.js: [http://localhost](http://localhost)
   Back-end API Symfony: [http://localhost:8000](http://localhost:8000)

## Personalização

Certifique-se de atualizar o conteúdo dos projetos Vue.js e API Symfony de acordo com suas necessidades.

## Contato

Se tiver alguma dúvida ou precisar de ajuda, sinta-se à vontade para entrar em contato pelo [lucasdauto@gmail.com](lucasdauto@gmail.com).
