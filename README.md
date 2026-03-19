Biblioteca Virtual App
Sobre o Projeto

Este projeto consiste em uma aplicação Android desenvolvida com foco em experiência do usuário e estética visual.

Foram realizadas as seguintes melhorias:

• Alteração da paleta de cores (de rosa/branco para tons de verde e laranja)
• Implementação de sistema de personalização de cores
• Implementação de rolagem (scroll)
• Melhorias na pesquisa de livros
• Adição de botão de ajuda no menu inicial

Funcionalidades e Implementações
Interface e Arquitetura

• Interface construída com Jetpack Compose
• Arquitetura seguindo o padrão MVVM

Listagem e Dados

• Uso de LazyColumn para listas
• Integração com API REST para busca de livros
• Persistência de dados local com Room Database

Pesquisa e Navegação

• Sistema de busca por título e autor
• Navegação entre telas com Navigation Component

Performance

• Implementação de carregamento assíncrono com Coroutines
• Gerenciamento de estado com ViewModel

Interface e Experiência do Usuário

• Carregamento de imagens com Coil
• Implementação de tela de detalhes do livro
• Criação de sistema de favoritos
• Adição de feedback visual (loading, mensagens, etc.)

Tratamento de Erros

• Tratamento de falhas de requisição (ex: ausência de internet)

Tecnologias Utilizadas
Linguagens e Frameworks

• Kotlin (versão 1.9.x)
• Jetpack Compose (versão 1.5.x)

Ferramentas

• Android Studio
• Git / GitHub

Bibliotecas

• Navigation Compose
• ViewModel (Android Jetpack)
• LiveData / State
• Room Database
• Retrofit
• Gson / Moshi
• Coil
• Coroutines
• Material 3

Instruções de Execução

Para executar o projeto:

• Abra o Android Studio
• Selecione a opção “Open Project”
• Escolha o diretório do projeto
• Aguarde a sincronização do Gradle
• Caso necessário, execute manualmente a sincronização
• Configure um dispositivo (emulador ou físico com depuração USB ativada)
• Clique em “Run” para compilar e executar o aplicativo
