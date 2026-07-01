# HTML-Mimo
Projetos relacionados ao curso "HTML" da Mimo — coleção organizada de exercícios e projetos para aprendizado de HTML, CSS e JavaScript.

## Conteúdo principal
- Projetos didáticos focados em conceitos fundamentais de web development.
- Estrutura organizada por pastas temáticas (projetos gerais, desafios, etc.).
- Interfaces responsivas com boas práticas de acessibilidade.
- Exemplos que demonstram integração entre HTML, CSS e JavaScript.

## Badges
- Licença: MIT (ver arquivo LICENSE)

## Sumário
- [Visão geral](#visão-geral)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Projetos inclusos](#projetos-inclusos)
- [Como usar](#como-usar)
- [Boas práticas](#boas-práticas)
- [Contribuindo](#contribuindo)
- [Licença](#licença)
- [Autor / Contato](#autor--contato)

## Visão geral
Este repositório reúne pequenos projetos em HTML, CSS e JavaScript que demonstram conceitos web essenciais e boas práticas de desenvolvimento front-end. Cada projeto é independente e pode ser executado aberto diretamente no navegador, com alguns incluindo consumo de APIs externas e manipulação interativa do DOM.

## Estrutura do repositório
```
Top-level:
├── .gitattributes              — configuração de atributos Git
├── LICENSE                     — licença MIT
├── README.md                   — este arquivo
└── projetos-gerais/            — projetos diversos e desafios
    ├── caesar-cipher/          — cifra de César (encriptação/decriptação de texto)
    │   ├── index.html
    │   ├── style.css
    │   ├── script.js
    │   └── preview.png
    ├── rick-and-morty/         — explorador de personagens (consumo de API)
    │   ├── index.html
    │   ├── style.css
    │   ├── script.js
    │   └── preview.png
    └── ...                     — outros projetos
```

### Descrição dos projetos

#### Caesar Cipher
- **O quê:** Implementação de cifra de César para encriptar e decriptar textos.
- **Tecnologias:** HTML5, CSS3, JavaScript vanilla.
- **Funcionalidades:**
  - Cifrar/decifrar com deslocamento configurável (0–25).
  - Mantém capitalização e caracteres não-alfabéticos.
  - Interface responsiva e simples.
- **Demo online:** [https://giovannijorge.github.io/html-mimo/projetos-gerais/caesar-cipher/](https://giovannijorge.github.io/html-mimo/projetos-gerais/caesar-cipher/)

#### Rick and Morty
- **O quê:** Explorador de personagens que consome a API pública Rick and Morty.
- **Tecnologias:** HTML5, CSS3, JavaScript vanilla, Fetch API.
- **Funcionalidades:**
  - Listagem de personagens com filtros (nome, status, espécie, gênero).
  - Paginação de resultados.
  - Visualização de detalhes em modal.
  - Tratamento de erros e estados de carregamento.
  - Layout responsivo.
- **Demo online:** [https://giovannijorge.github.io/html-mimo/projetos-gerais/rick-and-morty/](https://giovannijorge.github.io/html-mimo/projetos-gerais/rick-and-morty/)

## Como usar

### Opção 1: Clonar e abrir localmente
```bash
# Clonar o repositório
git clone https://github.com/GiovanniJorge/html-mimo.git
cd html-mimo

# Abrir um projeto no navegador (exemplo: Caesar Cipher)
# Simplesmente abra o arquivo index.html em seu navegador favorito
# No Linux/macOS:
open projetos-gerais/caesar-cipher/index.html
# No Windows:
start projetos-gerais/caesar-cipher/index.html
```

### Opção 2: Usar um servidor local
Para evitar problemas com requisições de API em alguns navegadores, recomenda-se usar um servidor HTTP local:

```bash
# Com Python 3:
cd projetos-gerais/rick-and-morty
python -m http.server 8000

# Com Node.js (se tiver http-server instalado):
npx http-server

# Acesse http://localhost:8000 no navegador
```

### Opção 3: Demos online
Todos os projetos estão hospedados via GitHub Pages:
- Caesar Cipher: [https://giovannijorge.github.io/html-mimo/projetos-gerais/caesar-cipher/](https://giovannijorge.github.io/html-mimo/projetos-gerais/caesar-cipher/)
- Rick and Morty: [https://giovannijorge.github.io/html-mimo/projetos-gerais/rick-and-morty/](https://giovannijorge.github.io/html-mimo/projetos-gerais/rick-and-morty/)

## Boas práticas

### Estrutura de projeto
- Cada projeto possui seus próprios arquivos `index.html`, `style.css` e `script.js`.
- Separação clara de responsabilidades (HTML para estrutura, CSS para estilo, JS para lógica).
- Uso de nomes semânticos para classes e IDs.

### CSS
- Preferência por flexbox e grid para layouts responsivos.
- Mobile-first approach com media queries para escalabilidade.
- Variáveis CSS para temas e consistência.

### JavaScript
- Vanilla JavaScript (sem frameworks pesados) para maior compreensão.
- Código bem documentado com comentários explicativos.
- Manipulação cuidadosa do DOM com tratamento de erros.
- Uso de `const`/`let` em vez de `var`.

### Acessibilidade
- Labels associados a inputs para leitores de tela.
- Atributos `alt` em imagens.
- Contraste adequado de cores.
- Navegação por teclado funcional.

### Documentação
- Cada projeto inclui um README específico explicando:
  - O que o projeto faz.
  - Como usá-lo.
  - Tecnologias envolvidas.
  - Exemplos de uso.

## Contribuindo

Contribuições são bem-vindas! Se deseja adicionar um novo projeto ou melhorar um existente, siga este fluxo:

1. **Fork** do repositório.
2. **Crie uma branch** com nome descritivo:
   ```bash
   git checkout -b feature/novo-projeto
   # ou
   git checkout -b fix/melhorar-acessibilidade
   ```
3. **Faça commits atômicos** com mensagens claras:
   ```bash
   git commit -m "Adiciona novo projeto de TODO list"
   ```
4. **Abra um Pull Request** descrevendo:
   - O que foi adicionado/modificado.
   - Por que a mudança é útil.
   - Se aplicável, instruções para testar.

### Sugestões para novos projetos
- Calculadora interativa.
- To-Do List com localStorage.
- Galeria de imagens com lightbox.
- Jogo da memória (matching game).
- Conversor de unidades.
- Quiz interativo.
- Aplicação de clima (consumindo API OpenWeather).
- Gerenciador de tarefas com filtros.

### Checklist para novos projetos
- [ ] Código HTML semântico e bem estruturado.
- [ ] Estilos CSS responsivos e modulares.
- [ ] JavaScript funcional com boas práticas.
- [ ] README específico do projeto explicando funcionalidades e como usar.
- [ ] Acessibilidade mínima (labels, alt text, navegação por teclado).
- [ ] Preview (imagem `preview.png`) no diretório do projeto.

## Testes e validação (opcional)
- Validar HTML com [W3C Validator](https://validator.w3.org/).
- Testar CSS em navegadores modernos (Chrome, Firefox, Safari, Edge).
- Verificar responsividade em diferentes tamanhos de tela.
- Avaliar acessibilidade com ferramentas como [Axe DevTools](https://www.deque.com/axe/devtools/) ou [Lighthouse](https://developers.google.com/web/tools/lighthouse).

## Licença
Este repositório utiliza a licença MIT — consulte o arquivo `LICENSE` na raiz.

## Autor / Contato
**Autor:** Giovanni Jorge  
**Repositório:** https://github.com/GiovanniJorge/html-mimo  
