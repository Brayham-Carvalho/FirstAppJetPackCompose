# My App - Cartão de Visita Interativo

Este projeto Android demonstra a criação de um cartão de visita interativo usando Jetpack Compose. O aplicativo apresenta um cartão com informações básicas do usuário, uma imagem de perfil e um botão "Portfólio". Ao clicar no botão, uma lista de projetos é exibida em um formato de cartão.
<div align="center">
  <img src="https://github.com/user-attachments/assets/fbd36863-cee7-447c-9574-177746afb907" />
</div>

## Funcionalidades

- **Cartão de Visita**: Exibe o nome, profissão e contato do usuário em um cartão estilizado.
- **Imagem de Perfil**: Apresenta uma imagem de perfil circular com borda e sombra.
- **Botão Interativo**: Um botão "Portfólio" que, ao ser clicado, revela uma lista de projetos.
- **Lista de Projetos**: Uma lista de projetos exibida em cartões individuais, cada um com uma breve descrição e uma imagem.

## Tecnologias Utilizadas

- **Jetpack Compose**: Framework moderno para construção de interfaces de usuário no Android.
- **Kotlin**: Linguagem de programação concisa e expressiva.
- **Material Design**: Sistema de design do Google para criar interfaces bonitas e intuitivas.

## Como Executar

1. Clone o repositório: `git clone https://github.com/seu-usuario/seu-repositorio.git`
2. Abra o projeto no Android Studio.
3. Execute o aplicativo em um emulador ou dispositivo físico.

## Estrutura do Projeto

- `MainActivity.kt`: Classe principal da Activity que configura o tema e inicia o Composable MyApp.
- `MyApp.kt`: Composable principal que define a estrutura do aplicativo, incluindo o Scaffold e o cartão de visita.
- `CreateBizCard.kt`: Composable que cria o cartão de visita com imagem de perfil, informações e botão.
- `Content.kt`: Composable que exibe a lista de projetos quando o botão "Portfólio" é clicado.
- `Portfolio.kt`: Composable que cria a lista de projetos usando LazyColumn e cartões individuais.
- `CreateInfo.kt`: Composable que exibe as informações do usuário no cartão de visita.
- `CreateImageProfile.kt`: Composable que cria a imagem de perfil circular.

## Personalização

- `res/drawable/profile_image.png`: Substitua esta imagem pela sua própria imagem de perfil.
- `themes.xml`: Personalize as cores e estilos do tema Material.
- `strings.xml`: Modifique os textos exibidos no aplicativo.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.
