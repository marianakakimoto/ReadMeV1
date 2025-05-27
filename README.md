# 
<img src="390005662-37ec0295-1331-4944-ac2c-fb85503723cd.svg" alt="Banner para Site Sua Nova Sombra Roxo e Azul Moderno Delicado" style="border-radius: 200px; width: 100%; height: auto;">

## 🚀 Visão Geral

**Ecosrev** é uma plataforma web desenvolvida com o objetivo de incentivar o descarte correto de resíduos eletroeletrônicos. A aplicação conecta cidadãos a empresas especializadas em coleta de lixo eletrônico, promovendo a sustentabilidade e a conscientização ambiental. O sistema oferece recompensas para os usuários que participam do descarte responsável de seus resíduos.

Este projeto foi desenvolvido no âmbito do curso de **Laboratório de Desenvolvimento Web**, utilizando tecnologias modernas para garantir uma experiência de usuário de alta qualidade, bem como um backend eficiente e escalável.

---

## 🔧 Tecnologias Utilizadas

### **Frontend**
![Next.js](https://img.shields.io/badge/Next.js-%23000000?style=flat&logo=next.js&logoColor=white)
![React.js](https://img.shields.io/badge/React-%2320232a?style=flat&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC?style=flat&logo=typescript&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-%2361DAFB?style=flat&logo=react&logoColor=white)

### **Backend**
![Express.js](https://img.shields.io/badge/Express.js-%23404d59?style=flat&logo=express&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-%23339933?style=flat&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%2347A248?style=flat&logo=mongodb&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-%2385B8C8?style=flat&logo=swagger&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-%23FF6C37?style=flat&logo=postman&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900?style=flat&logo=amazon-aws&logoColor=white)

### **Deploy**
![Vercel](https://img.shields.io/badge/Vercel-%23000000?style=flat&logo=vercel&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-%23121011?style=flat&logo=github&logoColor=white)

---

## 💡 Requisitos
<details>
  <summary>Requisitos Funcionais (RF)</summary>
  <details>
    <summary>RF01 - Gerenciamento de Usuários</summary>
    <summary>O sistema deve permitir o cadastro de novos usuários com nome, email, senha e telefone.</summary>
    <p>O sistema deve validar a unicidade do email no cadastro.</p>
    <p>O sistema deve permitir login com email e senha.</p>
    <p>O sistema deve manter sessão do usuário logado.</p>
    <p>O sistema deve permitir logout do usuário.</p>

  </details>
</details>
<details>
  <summary>Requisitos Não Funcionais (RNF)</summary>
  <details>
    <summary></summary>
  </details>
</details>
---

## 💡 Protótipo e documentação

Acesse o protótipo interativo no Figma:  

[Protótipo no Figma](https://www.figma.com/design/9qf7Ry7BcaML25kAtYWB17/Untitled)

---

<details>
  <summary>🎬 Apresentação</summary>
  <p>
    <summary>Cadastro</summary>
    <img src="https://github.com/AEntropia/EcosRev-PI/blob/master/public/images/doc/usuario_cadastro.gif" alt="Cadastro">
  </p>
  <p>
    <summary>Login (usuário) </summary>
    <img src="https://github.com/AEntropia/EcosRev-PI/blob/master/public/images/doc/usuario_login.gif" alt="Login Usuário">
  </p>
  <p>
    <summary>Selecionar benefícios para resgate </summary>
    <img src="https://github.com/AEntropia/EcosRev-PI/blob/master/public/images/doc/usuario_trocapontos.gif" alt="Selecionar Benefícios">
  </p>
  <p>
    <summary>Perfil </summary>
    <img src="https://github.com/AEntropia/EcosRev-PI/blob/master/public/images/doc/usuario_perfil.gif" alt="Perfil">
  </p>
  <p>
    <summary>Logout </summary>
    <img src="https://github.com/AEntropia/EcosRev-PI/blob/master/public/images/doc/usuario_logout.gif" alt="Logout">
  </p>
  <p>
    <summary>Login (administrador) </summary> 
    <img src="https://github.com/AEntropia/EcosRev-PI/blob/master/public/images/doc/admin_login.gif" alt="Login Administrador">
  </p>
  <p>
    <summary>Cadastrar benefícios </summary> 
    <img src="https://github.com/AEntropia/EcosRev-PI/blob/master/public/images/doc/admin_cadastrarBeneficios.gif" alt="Cadastrar Benefícios">
  </p>
  <p>
    <summary>Editar benefícios </summary> 
    <img src="https://github.com/AEntropia/EcosRev-PI/blob/master/public/images/doc/admin_editarBeneficios.gif" alt="Editar Benefícios">
  </p>
  <p>
    <summary>Editar pontos </summary> 
    <img src="https://github.com/AEntropia/EcosRev-PI/blob/master/public/images/doc/admin_editarPontos.gif" alt="Editar Pontos">
  </p>
</details>

---
<details>
  <summary style="color: #0070f3;">☁ AWS: O que é e Como Usar</summary>
  <p>
    No desenvolvimento do EcosRev, utilizamos o Docker para garantir que tanto o frontend quanto o backend fossem executados de maneira consistente em diferentes ambientes. 
    Com a utilização de contêineres Docker, conseguimos isolar os serviços, garantindo que as dependências necessárias para o funcionamento de cada parte da aplicação estivessem sempre presentes,   
    independentemente do ambiente em que o projeto estivesse rodando.

   Você pode baixar o material completo em um arquivo .doc com as instruções detalhadas no link abaixo:
  </p>  
  
  <a href="https://github.com/Ecosrev/PI-DSM-front/blob/master/public/images/doc/Projeto%20Integrador.pdf" target="_blank">Baixar Instruções do Docker</a>
    
  <details>
    <summary>🐳 Docker: Frontend</summary>
    <p>
    Construir a Imagem do Frontend: 
     
      docker build -t ecosrev-frontend-app .
  <p> 
      Executar o Container:  

</p>
      
      docker run -p 3000:3000 -e NEXT_PUBLIC_API_URL=http://localhost:4000/api
  </p>
  
   Link do Frontend no Docker Hub:  
      <a href="https://hub.docker.com/r/yamaokak/ecosrev-frontend" target="_blank">Imagem Frontend Docker</a>
  </details>
  <details>
    <summary>🐳 Docker: Backend</summary>
    <p>
      Construir a Imagem do Backend:  
      
      docker build -t ecosrev-backend .
  <p>
     Executar o Container:  
  </p>
     
      docker run -p 4000:4000 --env-file .env ecosrev-backend 
  </p>
   Link do Backend no Docker Hub:  
   
  <a href="https://hub.docker.com/r/yamaokak/ecosrev-backend" target="_blank">Imagem Backend Docker</a>
  </details>
 
  <details>
    <summary>🐳 Docker: Composição (Frontend + Backend)</summary>
    <p>
      Rodar Frontend e Backend no Mesmo Container:  
      
      docker-compose up --build
      
  </p>
  </details>
</details>

## 🌐 Hospedagem do Site
Este site está hospedado na [Vercel](https://vercel.com), uma plataforma de deploy e hospedagem de aplicações web, otimizada para projetos front-end e full-stack. A Vercel oferece recursos como deploys automáticos a partir de repositórios Git, integração contínua e um desempenho de alta qualidade com uma rede de entrega de conteúdo (CDN) global.

## 📍 Acesso
Você pode acessar o site através do seguinte link: [EcosRev - PI](https://ecos-rev-pi.vercel.app)


## 🧑‍💻 Desenvolvedores

Este projeto foi desenvolvido por uma equipe de estudantes do curso de Desenvolvimento de Software Multiplataforma. Abaixo estão os nomes dos colaboradores:
| Nome | GitHub |
| ----- | ------ |
| *Gabriel Yamaoka Bernardes* | [YamaokaK](https://github.com/YamaokaK) |
| *João Lucas Melo* | [JoaoLucasMdO](https://github.com/JoaoLucasMdO) |
| *Laura Jane Antunes* | [LauraJaneAntunes](https://github.com/LauraJaneAntunes) |
| *Mariana Hirata* | [marianakakimoto](https://github.com/marianakakimoto) |
| *Mateus Ferreira* | [AEntropia](https://github.com/AEntropia) |
