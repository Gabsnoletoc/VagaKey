# VagaKey
VagaKey é uma solução inovadora desenvolvida para transformar a experiência dos motoristas na hora de encontrar, reservar e utilizar vagas de estacionamento em áreas urbanas e centros comerciais. Nosso app alia tecnologia móvel e inteligência artificial.


# 🚗 VagaKey – Plataforma Inteligente de Estacionamento

O **VagaKey** é uma solução mobile multiplataforma desenvolvida com **Flutter + Node.js + IA**, focada em transformar a experiência de motoristas ao encontrar, reservar e acessar vagas de estacionamento em centros urbanos que oferecerm: 

-Reserva em tempo real: Permite que o usuário encontre e reserve a vaga ideal com apenas alguns cliques.

-Integração via mapa: Visualização interativa das vagas disponíveis em tempo real, com navegação e rotas otimizadas.

-Pagamento integrado: Solução simples e segura para efetuar transações via Pix, cartão ou outros métodos.

-Funcionalidades inteligentes com IA:

-Recomendação de vagas baseada no perfil do usuário, localização e horário;

-Previsão de ocupação, análise de feedbacks, OCR para leitura de placas e assistência virtual (chatbot).

-A proposta do VagaKey é reduzir o tempo de busca por vagas, minimizar o estresse no trânsito e melhorar a eficiência na utilização dos estacionamentos, proporcionando uma experiência de usuário fluida, preditiva e segura.

---

## 📲 Protótipo (Gravação de Tela)

▶️ [Assista à demonstração no YouTube](https://www.youtube.com/)

---

## 🧠 Funcionalidades com IA

- Recomendação de vagas com base em perfil e localização
- Previsão de ocupação com dados históricos
- OCR para leitura de placas veiculares
- Classificação de sentimentos em feedbacks
- Chatbot inteligente (assistente Vikey)
- Sugestão de plano por uso
- Detecção de vagas livres com visão computacional
- Recomendação de rota com trânsito

---

## 🛠️ Tecnologias utilizadas

Nossa arquitetura é modular e escalável, planejada para facilitar a integração de novas funcionalidades e o aprimoramento contínuo do sistema.

| Camada      | Tecnologias                           |
|-------------|----------------------------------------|
| Frontend    | Flutter + Dart                         |
| Backend     | Node.js + Express                      |
| Banco       | PostgreSQL + Redis (cache)             |
| IA          | Python (Scikit-learn, TensorFlow, NLP) |
| Integrações | Firebase, Google Maps, MercadoPago     |
| CI/CD       | GitHub Actions, Codemagic              |

---

## 📁 Estrutura do repositório

O repositório contém:

/frontend: Código fonte do aplicativo desenvolvido com Flutter.

/backend: API e demais scripts de integração desenvolvidos em Node.js.

/assets: Recursos gráficos, imagens e vídeos do protótipo.

/docs: Documentação completa do projeto, slides da apresentação e link para o vídeo de demonstração.

README.md: Este arquivo com a visão geral do projeto.

LICENSE: Arquivo com a licença do projeto (MIT, por exemplo).

---

##👨‍💻 Equipe de Desenvolvimento
Nome	RM	Papel no Projeto
Gabriela Noleto Costa	86339	UX/UI, funcionalidades com IA
Marcelo Noquele Ribeiro	93256	Backend e integração de APIs
Bianca Hellen de Souza	93093	Banco de dados e QA
Lucas Ken Watanabe Furumoto	86720	Desenvolvimento Mobile (Flutter)
Célio Brunelli Yazbek	93476	Documentação e suporte à integração

---
##🤖 Como Executar
Para configurar o ambiente localmente, siga estes passos:

Clone o repositório:

´´´bash
Copy
Edit
git clone https://github.com/seuusuario/vagakey.git
´´´

Configuração do Frontend:
Navegue até a pasta /frontend e instale as dependências:

´´´bash
Copy
Edit
cd vagakey/frontend
flutter pub get
´´´

Configuração do Backend:
Navegue até a pasta /backend e instale as dependências:

´´´ bash
Copy
Edit
cd ../backend
npm install
´´´

Execução:
Inicie o aplicativo conforme as instruções fornecidas no README de cada pasta.

Para mais detalhes, consulte a documentação completa na pasta /docs.

---
##📜 Licença
Este projeto está licenciado sob a Licença MIT.

---
```bash
frontend/   # App Flutter
backend/    # API Node.js
assets/     # Logos, mockups, vídeos
docs/       # Documentos e apresentações



