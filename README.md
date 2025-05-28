# 
<img src="[Black and White Gradient Personal LinkedIn Banner.svg](https://github.com/marianakakimoto/ReadMeV1/blob/main/Black%20and%20%20White%20Gradient%20Personal%20LinkedIn%20Banner.svg)" alt="Banner para Site Sua Nova Sombra Roxo e Azul Moderno Delicado" style="border-radius: 200px; width: 100%; height: auto;">

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

## 📜 Requisitos
<details>
  <summary>**Requisitos Funcionais (RF)**</summary>

  <!-- RF01 - Gerenciamento de Usuários -->
  <details>
    <summary>RF01 - Gerenciamento de Usuários</summary>
    <p>O sistema deve permitir o cadastro de novos usuários com nome, email, senha e telefone.</p>
    <p>O sistema deve validar a unicidade do email no cadastro.</p>
    <p>O sistema deve permitir login com email e senha.</p>
    <p>O sistema deve manter sessão do usuário logado.</p>
    <p>O sistema deve permitir logout do usuário.</p>
  </details>

  <!-- RF02 - Recuperação de Senha -->
  <details>
    <summary>RF02 - Recuperação de Senha</summary>
    <p>O sistema deve permitir solicitar recuperação de senha via email.</p>
    <p>O sistema deve enviar link/código de recuperação por email.</p>
    <p>O sistema deve permitir redefinir senha através do link/código válido.</p>
    <p>O sistema deve invalidar links de recuperação após uso ou expiração.</p>
  </details>

  <!-- RF03 - Alteração de Senha -->
  <details>
    <summary>RF03 - Alteração de Senha</summary>
    <p>O sistema deve permitir alterar senha informando a senha atual.</p>
    <p>O sistema deve validar a senha atual antes de permitir alteração.</p>
    <p>O sistema deve confirmar nova senha antes da alteração.</p>
  </details>

  <!-- RF04 - Sistema de Pontos via QR Code -->
  <details>
    <summary>RF04 - Sistema de Pontos via QR Code</summary>
    <p>O sistema deve permitir leitura de QR codes através da câmera.</p>
    <p>O sistema deve validar e processar QR codes válidos.</p>
    <p>O sistema deve adicionar pontos à conta do usuário após leitura válida.</p>
    <p>O sistema deve impedir uso múltiplo do mesmo QR code pelo mesmo usuário.</p>
    <p>O sistema deve exibir confirmação de pontos recebidos.</p>
  </details>

  <!-- RF05 - Resgate de Benefícios -->
  <details>
    <summary>RF05 - Resgate de Benefícios</summary>
    <p>O sistema deve listar benefícios disponíveis (ingressos, descontos).</p>
    <p>O sistema deve exibir custo em pontos de cada benefício.</p>
    <p>O sistema deve verificar saldo suficiente antes do resgate.</p>
    <p>O sistema deve processar resgate e debitar pontos da conta.</p>
    <p>O sistema deve gerar comprovante/código do benefício resgatado.</p>
    <p>O sistema deve impedir resgate com saldo insuficiente.</p>
  </details>

  <!-- RF06 - Histórico e Saldo -->
  <details>
    <summary>RF06 - Histórico e Saldo</summary>
    <p>O sistema deve exibir saldo atual de pontos do usuário.</p>
    <p>O sistema deve listar histórico de ganho de pontos.</p>
    <p>O sistema deve listar histórico de gastos/resgates.</p>
    <p>O sistema deve permitir filtrar histórico por período.</p>
    <p>O sistema deve exibir detalhes de cada transação.</p>
  </details>

  <!-- RF07 - Perfil do Usuário -->
  <details>
    <summary>RF07 - Perfil do Usuário</summary>
    <p>O sistema deve permitir visualizar dados do perfil.</p>
    <p>O sistema deve permitir editar dados básicos do perfil.</p>
    <p>O sistema deve validar alterações antes de salvar.</p>
  </details>
    <!-- RF08 - Acessibilidade -->
  <details>
    <summary>RF08 - Acessibilidade</summary>
    <p>O sistema deve permitir ao usuário ajustar o tamanho das fontes para melhorar a legibilidade.</p>
    <p>O sistema deve garantir que as alterações de tamanho de fonte sejam aplicadas em todas as telas e componentes do aplicativo.</p>
    <p>O sistema deve manter a usabilidade e layout adequados mesmo com tamanhos de fonte maiores.</p>
  </details>

</details>

<details>
  <summary>**Requisitos Não Funcionais (RNF)**</summary>

  <!-- RNF01 - Performance -->
  <details>
    <summary>RNF01 - Performance</summary>
    <p>O tempo de resposta da API não deve exceder 5 segundos.</p>
    <p>O tempo de login não deve exceder 3 segundos.</p>
    <p>A leitura de QR code deve ser processada em até 1 segundo.</p>
    <p>O carregamento da tela inicial deve ocorrer em até 2 segundos.</p>
  </details>

  <!-- RNF02 - Usabilidade -->
  <details>
    <summary>RNF02 - Usabilidade</summary>
    <p>A interface deve ser intuitiva e seguir padrões mobile.</p>
    <p>O aplicativo deve funcionar em modo portrait e landscape.</p>
    <p>Fontes e botões devem ter tamanho adequado para toque.</p>
    <p>Feedback visual deve ser fornecido para todas as ações do usuário.</p>
  </details>

  <!-- RNF03 - Compatibilidade -->
  <details>
    <summary>RNF03 - Compatibilidade</summary>
    <p>O app deve ser compatível com Android 7.0+ e iOS 12.0+.</p>
    <p>O backend deve ser compatível com Node.js 20+.</p>
  </details>

  <!-- RNF04 - Segurança -->
  <details>
    <summary>RNF04 - Segurança</summary>
    <p>Senhas devem ser armazenadas com hash seguro (bcrypt).</p>
    <p>Comunicação deve usar HTTPS/TLS.</p>
    <p>Tokens de autenticação devem ter expiração.</p>
    <p>QR codes devem ter validação contra reutilização.</p>
    <p>Dados sensíveis não devem ser logados.</p>
  </details>

  <!-- RNF05 - Disponibilidade -->
  <details>
    <summary>RNF05 - Disponibilidade</summary>
    <p>Sincronização automática quando conexão for restabelecida.</p>
  </details>

  <!-- RNF06 - Escalabilidade -->
  <details>
    <summary>RNF06 - Escalabilidade</summary>
    <p>O sistema deve suportar até 1000 usuários simultâneos.</p>
    <p>O banco de dados deve suportar crescimento de 10000 transações/mês.</p>
    <p>A arquitetura deve permitir expansão horizontal.</p>
  </details>

  <!-- RNF07 - Manutenibilidade -->
  <details>
    <summary>RNF07 - Manutenibilidade</summary>
    <p>Código deve seguir padrões de Clean Code.</p>
    <p>APIs devem ser documentadas (Swagger).</p>
    <p>Logs estruturados devem ser implementados.</p>
    <p>Versionamento semântico deve ser adotado.</p>
  </details>

  <!-- RNF08 - Privacidade -->
  <details>
    <summary>RNF08 - Privacidade</summary>
    <p>Sistema deve estar em conformidade com LGPD.</p>
    <p>Usuário deve poder solicitar exclusão de dados.</p>
    <p>Dados pessoais devem ser minimizados e protegidos.</p>
  </details>

  <!-- RNF09 - Recursos do Dispositivo -->
  <details>
    <summary>RNF09 - Recursos do Dispositivo</summary>
    <p>App deve solicitar permissão para uso da câmera.</p>
    <p>App deve funcionar com pelo menos 2GB de RAM.</p>
    <p>App deve ocupar no máximo 200MB de armazenamento.</p>
    <p>Consumo de bateria deve ser otimizado.</p>
  </details>

</details>

---

## 💡 Protótipo

Acesse o protótipo no Figma:  

[Protótipo no Figma](https://www.figma.com/design/bXL4WXW3bh4LPZq1Nl6Mbh/EcosRev---com-tratamento-de-exce%C3%A7%C3%A3o?node-id=0-1&t=NFlEy2NGOc1szUI9-1)

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
