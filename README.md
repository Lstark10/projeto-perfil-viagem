# 🌍 Travelgram - Perfil de Viagem

Um projeto web responsivo que simula um perfil de rede social focado em viagens, apresentando uma interface elegante e moderna para compartilhamento de fotos e experiências de viagem.

## 📋 Sobre o Projeto

O **Travelgram** é uma página web estática que representa o perfil de viagem de Isabela Torres, uma entusiasta de viagens, cultura e gastronomia de São Paulo. O projeto demonstra suas aventuras através de uma galeria de fotos organizada e uma interface intuitiva.

### ✨ Características Principais

- 🎨 **Design Moderno**: Interface limpa e minimalista
- 📱 **Responsivo**: Adaptável a diferentes tamanhos de tela
- 🌈 **Paleta de Cores Harmoniosa**: Utilizando tons de coral (#EF5F4C) como cor principal
- 📸 **Galeria de Fotos**: Exibição organizada de 12 imagens de viagens
- 👤 **Perfil Personalizado**: Informações detalhadas do viajante
- 🚀 **Performance Otimizada**: CSS modular e semântica HTML

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica da página
- **CSS3**: Estilização e layout responsivo
- **Google Fonts**: Tipografia Poppins
- **SVG Icons**: Ícones vetoriais escaláveis
- **Metodologia BEM**: Organização do CSS (implícita na estrutura)

## 📁 Estrutura do Projeto

```
projeto-perfil-viagem/
├── index.html                 # Página principal
├── README.md                 # Documentação do projeto
├── assets/                   # Recursos estáticos
│   ├── Logo.svg             # Logotipo do Travelgram
│   ├── Profile pic.png      # Foto de perfil da usuária
│   ├── icons/               # Ícones SVG
│   │   ├── AirplaneTilt.svg # Ícone de avião
│   │   ├── Image.svg        # Ícone de imagem
│   │   ├── MagnifyingGlass.svg # Ícone de busca
│   │   └── MapPin.svg       # Ícone de localização
│   └── images/              # Galeria de fotos
│       ├── Image 01.png     # Foto de viagem 1
│       ├── Image 02.png     # Foto de viagem 2
│       └── ... (até Image 12.png)
└── styles/                  # Arquivos de estilo
    ├── index.css           # Arquivo principal (importa outros)
    ├── global.css          # Estilos globais e variáveis CSS
    ├── nav.css             # Estilos da navegação
    ├── header.css          # Estilos do cabeçalho/perfil
    ├── main.css            # Estilos da galeria principal
    └── footer.css          # Estilos do rodapé
```

## 🎨 Design System

### Paleta de Cores
- **Primária**: `#EF5F4C` (Coral vibrante)
- **Fundo**: `#FFFFFF` (Branco)
- **Superfície**: `#F5F5F5` (Cinza claro)
- **Texto Primário**: `#313131` (Cinza escuro)
- **Texto Secundário**: `#6C6C6C` (Cinza médio)
- **Transparência**: `#FFFFFF91` (Branco com opacidade)

### Tipografia
- **Fonte**: Poppins (Google Fonts)
- **Tamanhos**:
  - Grande: 32px (Títulos)
  - Médio: 14px (Textos secundários)
  - Pequeno: 12px (Detalhes)
  - Padrão: 16px (Texto geral)

## 🚀 Como Executar o Projeto

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexão com internet (para carregar as fontes do Google)

### Instalação e Execução

1. **Clone ou baixe o repositório:**
```bash
git clone https://github.com/Lstark10/projeto-perfil-viagem.git
```

2. **Navegue até o diretório do projeto:**
```bash
cd projeto-perfil-viagem
```

3. **Abra o arquivo `index.html` em seu navegador:**
   - Clique duas vezes no arquivo `index.html`
   - Ou arraste o arquivo para o navegador
   - Ou use um servidor local como Live Server (VS Code)

### 🌐 Servidor Local (Recomendado)

Para uma melhor experiência de desenvolvimento, use um servidor local:

**Com Live Server (VS Code):**
1. Instale a extensão "Live Server"
2. Clique com botão direito no `index.html`
3. Selecione "Open with Live Server"

**Com Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Com Node.js:**
```bash
npx serve .
```

## 📱 Funcionalidades

### 🧭 Navegação
- **Logo**: Link para página inicial
- **Busca**: Ícone de lupa (funcionalidade a ser implementada)
- **Explorer**: Link para explorar conteúdo
- **Minhas viagens**: Acesso às viagens do usuário
- **Perfil**: Foto do usuário

### 👤 Seção de Perfil
- **Foto de perfil**: Imagem da usuária
- **Nome**: Isabela Torres
- **Biografia**: Descrição pessoal com emojis
- **Estatísticas**:
  - 📍 Localização: São Paulo, Brazil
  - ✈️ Países visitados: 37
  - 📸 Fotos compartilhadas: 240

### 🖼️ Galeria
- **12 fotos de viagens** organizadas em grid responsivo
- **Layout adaptativo** para diferentes tamanhos de tela

### 📄 Rodapé
- **Copyright**: Travelgram © 2024
- **Links legais**: Termos de uso e Política de privacidade

## 🔧 Personalização

### Alterando Cores
Modifique as variáveis CSS no arquivo `styles/global.css`:

```css
:root {
  --brand-color: #EF5F4C;          /* Cor principal */
  --background-color: #FFFFFF;      /* Fundo */
  --surface-color: #F5F5F5;         /* Superfície */
  --text-color-primary: #313131;    /* Texto principal */
  --text-color-secondary: #6C6C6C;  /* Texto secundário */
}
```

### Adicionando Mais Fotos
1. Adicione as imagens na pasta `assets/images/`
2. Inclua as tags `<img>` correspondentes no `main` do `index.html`

### Modificando Informações do Perfil
Edite o arquivo `index.html` na seção `<header>` para alterar:
- Nome do usuário
- Biografia
- Estatísticas (países, fotos, localização)


## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

