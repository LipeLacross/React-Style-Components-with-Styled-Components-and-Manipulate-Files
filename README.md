## 🌐 [English Version of README](README_EN.md)

# SpaceApp

SpaceApp é um projeto desenvolvido com React utilizando Vite como ferramenta de bundling. O projeto é uma galeria de imagens com funcionalidades como visualização ampliada das fotos, navegação através de uma barra lateral e filtros de imagens por categorias populares. Ele foi projetado para ser simples, eficiente e intuitivo, com foco na experiência do usuário.

## 🔨 Funcionalidades do Projeto

- **Galeria de Imagens**: Exibe uma galeria de imagens dividida em categorias populares e uma seção de imagens destacadas.
- **Zoom nas Imagens**: Permite ao usuário ampliar a imagem para uma visualização detalhada.
- **Navegação Lateral**: A barra lateral permite ao usuário filtrar as imagens por diferentes critérios, como "Mais Curtidas", "Mais Vistas", "Novas", e "Surpreenda-me".
- **Interface Responsiva**: O layout é responsivo, adaptando-se a diferentes tamanhos de tela, desde dispositivos móveis até desktops.
- **Buscador**: A funcionalidade de busca permite filtrar imagens por tags.

### Exemplo Visual do Projeto

![chrome-capture-2024-12-21 (1)](https://github.com/user-attachments/assets/5989b964-c178-4e43-a048-39d172a609b1)

## ✔️ Técnicas e Tecnologias Utilizadas

- **React**: Biblioteca JavaScript para criar interfaces de usuário dinâmicas.
- **Vite**: Ferramenta de build que proporciona um desenvolvimento rápido e otimizado.
- **CSS-in-JS (Styled Components)**: Estilização de componentes diretamente no código, com foco na reutilização e manutenibilidade.
- **Fontes Customizadas**: Uso de fontes personalizadas para um design único (GandhiSans).
- **JSON**: Para armazenar dados de imagens e tags.

## 📁 Estrutura do Projeto

- **public/**
    - **icones/**: Contém os ícones utilizados no sistema (ex: favoritos, expandir, fechar).
    - **imagens/**: Contém imagens para a galeria e logos.
        - **galeria/**: Imagens da galeria de fotos.
        - **populares/**: Imagens populares para exibição destacada.
    - **index.html**: Arquivo HTML principal, onde o React se conecta.
- **src/**
    - **App.jsx**: Componente raiz que organiza e renderiza a aplicação.
    - **components/**: Pasta que contém os componentes reutilizáveis da aplicação.
        - **Banner/**: Componente para exibir banners.
        - **BarraLateral/**: Componente de navegação lateral.
        - **BotaoIcone/**: Componente para botões de ícones.
        - **Galeria/**: Componente para exibir a galeria de imagens e tags.
        - **ModalZoom/**: Componente de visualização de imagens em zoom.
        - **Titulo/**: Componente para exibir títulos em diferentes seções da aplicação.
    - **fotos.json**: Arquivo JSON contendo dados das imagens exibidas.
    - **main.jsx**: Arquivo que inicializa a aplicação React.
- **vite.config.js**: Arquivo de configuração do Vite para otimização e build do projeto.

## 🛠️ Abrir e rodar o projeto

Para iniciar o projeto localmente, siga os passos abaixo:

1. **Certifique-se de que o Node.js está instalado**:
    - O [Node.js](https://nodejs.org/) é necessário para rodar o projeto. Você pode verificar se já o tem instalado com:

      ```bash
      node -v
      ```

    - Se não estiver instalado, baixe e instale a versão recomendada.

2. **Clone o Repositório**:
    - Copie a URL do repositório e execute o comando abaixo no terminal:

      ```bash
      git clone <URL_DO_REPOSITORIO>
      ```

3. **Instale as Dependências**:
    - Navegue até o diretório do projeto e execute o seguinte comando para instalar as dependências necessárias:

      ```bash
      npm install
      ```

4. **Inicie o Projeto**:
    - Após as dependências estarem instaladas, execute o comando abaixo para iniciar o servidor de desenvolvimento:

      ```bash
      npm run dev
      ```

    - O projeto estará disponível em [http://localhost:3000](http://localhost:3000) (ou o endereço indicado no terminal).

## 🌐 Deploy

Para realizar o deploy da aplicação, você pode usar plataformas como Vercel ou Netlify.

- **Vercel**: Basta conectar o repositório ao Vercel e ele cuidará do build e deploy.
- **Netlify**: Similar ao Vercel, conecte o repositório ao Netlify e ele gerenciará o deploy automaticamente.
