# Playlist Creator

## Descrição do Projeto

Este é um projeto desenvolvido em Python que aplica os princípios de Clean Code para criar e gerenciar playlists de músicas. O objetivo principal é demonstrar boas práticas de programação, como organização de código, modularidade e legibilidade, enquanto implementa funcionalidades úteis para manipulação de playlists.

## Funcionalidades

- **Criação de Playlists**: Permite criar novas playlists com nome personalizado.
- **Cadastro de Músicas**: Adiciona músicas às playlists, incluindo informações como título, artista e duração.
- **Visualização de Playlists**: Exibe as playlists criadas e suas respectivas músicas.

## Estrutura do Projeto

O projeto segue uma arquitetura modular, dividida em camadas para facilitar a manutenção e escalabilidade:

- **Controllers**: Contém a lógica de controle, responsável por intermediar as interações entre as camadas de modelo e visão.
- **Models**: Define as entidades e repositórios, representando os dados e suas operações.
- **View**: Gerencia a interface com o usuário, exibindo informações e capturando entradas.
- **Main**: Contém o ponto de entrada e os handlers principais do processo.

## Tecnologias Utilizadas

- **Linguagem**: Python 3.10+
- **Paradigma**: Programação Orientada a Objetos (POO)
- **Princípios**: Clean Code

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone <https://github.com/Diogooliveira10/playlist>
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd playlist
   ```
3. Execute o arquivo principal:
   ```bash
   python run.py
   ```

## Estrutura de Pastas

```
playlist/
├── run.py
├── src/
│   ├── controllers/
│   │   ├── playlist_creator_controller.py
│   │   ├── song_register_controller.py
│   ├── main/
│   │   ├── process_handler.py
│   │   ├── constructor/
│   │       ├── playlist_creator_constructor.py
│   │       ├── song_register_constructor.py
│   ├── models/
│   │   ├── entities/
│   │   │   ├── music.py
│   │   ├── repositories/
│   │       ├── music_repository.py
│   ├── view/
│       ├── first_view.py
│       ├── playlist_creator_view.py
│       ├── song_register_view.py
```

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
