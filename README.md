<h1>🥐 Sistema de Padaria – FlutterFlow</h1>
<h2>📌 Descrição do Projeto</h2>

O Sistema de Padaria é um aplicativo mobile desenvolvido utilizando FlutterFlow, com o objetivo de facilitar o cadastro, login e gerenciamento de informações de usuários em uma padaria digital.
O projeto inclui telas de autenticação, cadastro, home com categorias, gerenciamento de endereços e consulta de dados do usuário, além de integração completa com API para todas as operações.

<h2>✨ Funcionalidades</h2>
🔐 Login

Tela de login com:
Campo de e-mail
Campo de senha
Botão de autenticação
Personalização completa de layout com containers, cores, texto e imagem.

📝 Cadastro de Usuário

Página para criação de nova conta.
Estrutura semelhante à página de login, porém com campos adicionais.
Envio dos dados para a API de cadastro.

🏠 Home

AppBar personalizada
Barra de pesquisa
GridView com 8 imagens representando categorias / produtos
Barra inferior de navegação com ícones das páginas

📍 Cadastro de Endereço

Tela contendo:
Campo de texto para título
Container com 7 textfields relacionados ao endereço
Botão para salvar
Integração via API para inserir endereço

👤 Dados do Usuário

Exibição de informações pessoais do usuário
Estrutura com AppBar, barras inferiores, imagem e container com textfields
Requisição GET para buscar dados do usuário

🔗 API Calls

O sistema se comunica com um backend via chamadas API:
Cadastro de endereço – método POST com body em JSON
Cadastro de usuário – método POST
Login – método POST com e-mail e senha
Buscar dados do usuário – método GET com parâmetro de ID

🛠️ Tecnologias Utilizadas

📱 FlutterFlow

Construção visual das telas
Widgets personalizados
Configuração de navegação e states
Integração de API nativa

🌐 APIs REST

Endpoints gerenciados via Swagger
Métodos: GET, POST
Envio e recebimento de JSON

🎨 UI/UX

Containers customizados
Imagens via link (Network)
GridView
AppBar e barra inferior
Personalização de fonte, sombra, cores e arredondamento

<h2>📱 Telas FlutterFlow</h2>

<img width="389" height="791" alt="Captura de tela 2025-12-09 100442" src="https://github.com/user-attachments/assets/6854042e-430c-43e8-86e9-d5edeb51639c" />
<img width="376" height="786" alt="Captura de tela 2025-12-09 100450" src="https://github.com/user-attachments/assets/cb1ec076-9292-4647-8a00-e398768022b4" />
<img width="393" height="792" alt="Captura de tela 2025-12-09 100458" src="https://github.com/user-attachments/assets/39526d44-3d93-4a64-8402-e411e1e7eef3" />
<img width="404" height="788" alt="Captura de tela 2025-12-09 100503" src="https://github.com/user-attachments/assets/c7959508-b903-4ed1-a95e-8e72569e9310" />
<img width="379" height="789" alt="Captura de tela 2025-12-09 100508" src="https://github.com/user-attachments/assets/52ca5478-2a17-42f2-aaf7-78f2b826e463" />

<h2>🟢 Link Swagger</h2>
https://atividadeapi-komn.onrender.com/atividade-api/swagger-ui/index.html

Desenvolvido por Pedro Campos Dos Santos Silva
