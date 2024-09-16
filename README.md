# Instruções
## 1. Abra o prompt de comando e acesse a pasta do projeto usando o código cd

cd src

## 2. após acessar a pasta, digite os comandos npm install para instalar os componentes

npm install

## 3. como o projeto utiliza rotas e estilização por meio da biblioteca UI Material, é necessário instalar esses pacotes

npm install react-router-dom

npm install @mui/icons-material @mui/material @emotion/styled @emotion/react

## 4. por fim npm start para iniciar a conexão com a porta 3000

npm start

## Após a execução dos comandos anteriores, é esperado que abra a página "HOME" do projeto no navegador

![home](https://github.com/user-attachments/assets/788f3d7c-bdc3-462a-a6fe-031b9e8fea0c)

# Funcionamento
## Introdução

Este projeto é critério parcial para conclusão da disciplina de "Desenvolvimento de Sistemas frontend" e tem por objetivo verificar os conhecimentos adquiridos em JavaScript e CSS. 
Aluna - Thais Oliveira Federico

## Funções e Comandos
Foram criadas 3 funções para:

<b>AdicionaCarro:</b> Identifica o input cadastrado pelo usuário e cria um carrinho ao final da lista com o próximo id sequencial disponível

<b>ExcluiCarro:</b> busca o id do carro na lista, realiza uma busca na lista de todos os carros e faz um filtro, deixando de mostrar o carro que foi excluído

<b>Atualiza:</b> verifica a informação atual do carro e atualiza a cor para a digitada pelo usuário

A navegação entre as páginas do projeto ocorreu usando o comando router. As páginas criadas foram: Home, Sobre, Carros e Adicionar Carros.

<b>Home</b>

![home](https://github.com/user-attachments/assets/09f5d95a-8661-4ec0-b4c1-f9a4ad5586a9)


<b>Sobre</b>

![Sobre](https://github.com/user-attachments/assets/68a5dfbb-9f6b-4708-8d31-1da858be3706)


<b>Carros </b>

![Carros](https://github.com/user-attachments/assets/8bd5b9be-ac6e-4dff-b944-588ed747f699)


Por padrão, são apresentados 3 carros que são importados do arquivo "dados.js". 
Importante observar que os carros adicionados pelo usuário e as alterações feitas por ele não mudam a base de dados, mudam apenas a tela de visualização.
Os ícones de lápis e lixeira chama as funções de “Atualiza” e “ExcluiCarro” respectivamente.

Ao clicar em atualizar, aparecem os campos de atualização preenchidos com as informações do carro. Após atualizar, quando clica no botão, os novos dados aparecem na lista de carrinhos.

![Atualiza Carros](https://github.com/user-attachments/assets/ba6593d0-5ca1-4730-a4fd-eafac22602a4)


<b>Adicionar Carros</b>

![Adicionar](https://github.com/user-attachments/assets/69c0db27-156a-44bf-8153-23d2eb0ad007)

Após adicionar, o novo carro aparece na lista de carrinhos:

![Carros +1](https://github.com/user-attachments/assets/637b8d31-f02d-4b22-91dd-0dc2fde2fee1)

