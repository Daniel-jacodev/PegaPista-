PegaPista! 🏃‍♂️🏁
O PegaPista! é um aplicativo Android voltado para o monitoramento de atividades físicas (corridas) com funcionalidades sociais, permitindo que usuários acompanhem seu desempenho em tempo real, interajam com amigos e visualizem rankings.

🚀 Tecnologias Utilizadas
O projeto foi desenvolvido utilizando as tecnologias mais modernas do ecossistema Android:

Linguagem: Kotlin.

Interface de Usuário: Jetpack Compose para uma UI declarativa e reativa.

Injeção de Dependência: Koin.

Banco de Dados Local: Room Database para persistência de dados offline (Corridas, Postagens e Usuários).

Backend & Cloud (Firebase):

Firebase Auth: Autenticação de usuários (Email/Senha e Google Login).

Firestore: Armazenamento de dados em nuvem.

Firebase Storage: Armazenamento de mídias e imagens.

Firebase Messaging (FCM): Notificações push.

Mapas e Localização:

Google Maps Compose.

Play Services Location para rastreamento em tempo real.

Arquitetura: MVVM (Model-View-ViewModel).

Processamento em Segundo Plano: WorkManager para sincronização de dados e lembretes.

Carregamento de Imagens: Coil.

🛠️ Funcionalidades Principais
Autenticação Completa: Cadastro e Login via e-mail ou conta Google.

Monitoramento de Corrida: Rastreamento por GPS com visualização no mapa em tempo real.

Feed Social: Postagens de atividades, comentários e interação entre atletas.

Ranking: Sistema de classificação de usuários.

Perfil Personalizado: Gestão de informações do usuário e busca de amigos.

Sincronização Offline: Uso de Workers para garantir que os dados locais sejam enviados para a nuvem assim que houver conexão.

📦 Como Rodar o Projeto
Clonar o repositório:

Bash
git clone https://github.com/seu-usuario/pegapista.git
Configurar o Firebase:

Crie um projeto no Firebase Console.

Adicione um app Android com o package name com.example.pegapista.

Baixe o arquivo google-services.json e coloque-o na pasta app/.

Configurar chaves de API:

Ative a Maps SDK for Android no Google Cloud Console.

Adicione sua chave de API no AndroidManifest.xml (ou via Secrets Gradle Plugin).

Build:

Abra o projeto no Android Studio e execute o Sync do Gradle.

Rode o aplicativo em um emulador ou dispositivo físico.
