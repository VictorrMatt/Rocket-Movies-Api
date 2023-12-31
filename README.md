# 🚀 Rocket Movies
![image](https://github.com/VictorrMatt/Rocket-Movies-Web/assets/98140122/d1722c5e-7973-4ad6-9a2f-74738dbb55d2)


### 🔨 Visão Geral

"Rocket Movies" é um projeto desenvolvido após os módulos 08 e 09 do curso Explorer, oferecido pela plataforma de ensino Rocketseat. Este projeto consiste em duas partes complementares: o back-end e o front-end.

## Back-End:

O back-end é uma aplicação Node.js que permite aos usuários cadastrar informações sobre filmes. Os recursos do back-end incluem:

- Criação, leitura, atualização e exclusão de informações de filmes.
- Autenticação de usuários com geração e validação de tokens JWT (JSON Web Tokens) para garantir a segurança das rotas e dados sensíveis.
- Gerenciamento de usuários, incluindo o cadastro e atualização de informações.
- Utilização do Express para roteamento de requisições HTTP.
- Uso do Knex para automatizar comandos DDL no banco de dados.
- Suporte ao upload de imagens de perfil dos usuários com Multer.
- Implementação de testes automatizados com o Jest.
- Implantação do serviço na plataforma Render.

## 🔐Requisições:
### Sessions:
``POST / Create`` (Criação de um novo token Jwt que será necessário para as requisições):  
> {  
  >&nbsp;&nbsp;"email": "seu_email",  
   &nbsp;&nbsp;"password": "sua_senha"  
}  

### Users:  
``PATCH / Avatar:``  
> *Recebe a imagem do avatar que será salva no banco*  

``POST / Create`` (Criação de usuários):  
> {  
  &nbsp;&nbsp;"name": "seu_nome",  
  &nbsp;&nbsp;"email": "seu_email",  
  &nbsp;&nbsp;"password": "sua_senha"  
}  

``PUT / Update`` (Atualiza dados do usuário):  
> {  
  &nbsp;&nbsp;"name": "novo_nome",  
  &nbsp;&nbsp;"email": "novo_email",  
  &nbsp;&nbsp;"password": "nova_senha",  
  &nbsp;&nbsp;"old_password": "senha_antiga"  
}  

### Notes:  
``GET / Index`` (Retorna notas referentes a title):  
> *Queries: Title.*  

``DELETE / Delete`` (Deleta uma nota):  
> *Recebe o ID da nota por meio do route params.*  

``GET / Read`` (Retorna a nota e as suas tags):  
> *Recebe o ID da nota por meio do route params.*  

``POST / Create`` (Cria uma nova nota):  
> {  
  &nbsp;&nbsp;"title": "jegarne",  
  &nbsp;&nbsp;"description": "Massa",  
  &nbsp;&nbsp;"rating": 6,  
  &nbsp;&nbsp;"tags": ["Pamonha", "raimundo"]  
}  

### Tags:  
``GET / Index:``  
> *Retorna as tags que foram criadas nas notas pelo usuário.*  

### Files:  
``GET / ?`` (Recebe o nome da imagem cadastrada no banco e a retorna):    
> *Recebe o nome da imagem por meio do route params.*  

## ✔️ Tecnologias Utilizadas

### Back-End (Tecnologias comuns em projetos Node.js):

- ``Node.js``: Plataforma de execução JavaScript.
- ``Express``: Framework Node.js para a criação de APIs RESTful.
- ``Banco de Dados`` (SqLite): Armazenamento de informações de usuários e filmes.
- ``JWT`` (JSON Web Tokens): Autenticação e segurança.
- ``Multer``: Manipulação de uploads de imagens, como imagens de perfil.
- ``Cors``: Habilitação de requisições entre origens (CORS) no servidor.

### 📝 Resumo

*"Rocket Movies" é um projeto completo que consiste em uma aplicação de gerenciamento de informações de filmes, composta por um back-end desenvolvido em Node.js e um front-end construído em React.js e Styled-components. O projeto oferece recursos de autenticação, gerenciamento de usuários e filmes, segurança, e armazenamento de informações. "Rocket Movies" é uma solução eficaz para armazenar e gerenciar informações sobre filmes, e é resultado do curso Explorer da Rocketseat.*

Para acessar o site do "Rocket Movies", você pode [clicar aqui](https://rocketmoovies.netlify.app/).

## 🤝Desenvolvedores
<table align="center">
  
  <tr>
    <td align="center">
      <a href="https://github.com/victorrmatt">
        <img src="https://github.com/victorrmatt.png" width="100px;" alt="Foto do Victor Mateus no GitHub"/><br>
        <p align="center">
          <a href="https://www.linkedin.com/in/victor-mateus/" alt="LinkedIn">
          <img src="https://img.shields.io/badge/-Linkedin-0e76a8?style=flat-square&logo=Linkedin&logoColor=white&link=#"/></a>
          <a href="https://api.whatsapp.com/send?phone=5587988278980&text=Olá%20Tudo%20Bem?%0DVenho%20pelo%20GitHub." alt="WhatsApp">
          <img src="https://img.shields.io/badge/-WhatsApp-25d366?style=flat-square&labelColor=25d366&logo=whatsapp&logoColor=white&link=#"/></a>
        </p>
      </a>
    </td>
    <td>
      <img width="300" src="https://i2.wp.com/allhtaccess.info/wp-content/uploads/2018/03/programming.gif?fit=1281%2C716&ssl=1" />
    </td>
  </tr>
</table>

<p align="center">
  <img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>
