### Projeto desenvolvido durante Bootcamps da Digital Innovation One tendo como instrutor [Patrick Narciso](https://github.com/patrick-narciso).

O projeto tem por objetivo criar sistema web de busca de restaurantes, parecido com o serviço que o Google oferece. Vamos desenvolver esse buscador usando React.JS e API do Google

Para criar esse projeto usaremos React Js Também é necessário ter instalado no computador o Node.js (https://nodejs.org/pt-br/) e o Gerenciador de Pacotes NPM, que já será instalado junto com o Node.js

Para desenvolver o projeto utilizamos o Visual Studio Code (VS Code).

Para criar o projeto crie em seu computador uma pasta com o nome que desejar, por exemplo: projeto-react

Abra a pasta no VS Code.

Para criar o projeto digite o comando: npx create-react-app <nome-do-projeto> Como exemplo eu utilizei: `npx create-react-app restaurants-search`
  
Aguarde um tempinho que o VS Code irá criar a estrutura do projeto.
  
Após finalizada a criação da estrutura das pastas do projeto, ainda no terminal integrado navegue para a pasta que foi criada utilize o comando: `cd reastaurants-search
Após se certificar que está na pasta correta você precisa instalar algumas bibliotecas:
  
@material/ui-core
@material/react-text-field
google-maps-react
react-dom
react-lottie
react-rating-stars-component
react-redux
react-scripts
react-slick
redux
slick-carousel
styled-components
styled-reset

Para inicializar o projeto confirme que está na pasta do projeto (restaurants-search) digite no terminal integrado do VS Code o comando npm start

Caso não abra de forma automática no seu navegador padrão, clique ou copie o seguinte link http://localhost:3000.
  
Para parar a aplicação pressione as Teclas CTRL + C no terminal integrado do VS Code.
  
Para o desenvolvimento do projeto é necessário ter uma conta Google e se logar na Google Cloud Platform - GCP, criar um novo projeto na plataforma e criar uma nova credencial do tipo chave de API a qual será utilizada no projeto que está sendo desenvolvido no VS Code.
  
No projeto no GCP também precisam ser ativas as APIs: Maps JavaScript API e Places API.
  
Com a chave de API criada é necessário restringir as API, para isso em Restrições de API selecione apenas as duas APIs acima informadas e clique em salvar.
  
Caso você prefira fazer o download desse repositório ou realizar o clone do repositório não de esqueça de instalar as dependências do Node JS. para isso assim que abrir o projeto no seu VS Code digite o comando npm install e depois não se esqueça de instalar as outras bibliotecas utilizadas no projeto conforme orientações acima.
