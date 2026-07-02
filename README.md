# HTML - Mimo

Projetos relacionados ao curso "HTML" da Mimo — coleção organizada de exercícios e projetos para aprendizado de HTML, CSS e JavaScript. Ideal para estudantes que buscam consolidar conceitos fundamentais de desenvolvimento web, manipulação do DOM e consumo de APIs.

## Conteúdo principal
- Projetos didáticos focados em conceitos fundamentais de web development.
- Estrutura organizada por pastas temáticas (projetos gerais, desafios, etc.).
- Interfaces responsivas com boas práticas de acessibilidade.
- Exemplos que demonstram integração entre HTML, CSS e JavaScript.

## Badges
![Licença](https://img.shields.io/github/license/GiovanniJorge/c-unaerp?style=flat-square)

## Sumário
- [Visão geral](#visão-geral)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Destaques do repositório](#destaques-do-repositório)
- [Como usar](#como-usar)
- [Contribuindo](#contribuindo)
- [Licença](#licença)
- [Autor / Contato](#autor--contato)

## Visão geral
Este repositório reúne pequenos projetos em HTML, CSS e JavaScript que demonstram conceitos web essenciais e boas práticas de desenvolvimento front-end. Cada projeto é independente e pode ser executado diretamente no navegador, com alguns incluindo consumo de APIs externas e manipulação interativa do DOM.

## Estrutura do repositório
Top-level:
```text
├── .gitattributes
├── LICENSE
├── README.md
└── projetos-gerais/            # Projetos diversos, exercícios e desafios
    ├── caesar-cipher/          # Cifra de César (encriptação/decriptação de texto)
    │   ├── index.html
    │   ├── style.css
    │   ├── script.js
    │   └── preview.png
    ├── rick-and-morty/         # Explorador de personagens (consumo de API)
    │   ├── index.html
    │   ├── style.css
    │   ├── script.js
    │   └── preview.png
    └── ...                     # Outros projetos e exercícios desenvolvidos no curso
```

### Como se encaixa:
- O repositório abriga uma variedade de projetos independentes criados ao longo do curso. 
- As pastas listadas acima funcionam como exemplos principais de aplicações completas contidas no diretório `projetos-gerais/`.

## Destaques do repositório

### Caesar Cipher
* **Descrição:** Implementação de cifra de César para encriptar e decriptar textos com deslocamento configurável (0–25). Mantém capitalização e caracteres não-alfabéticos.
* **Tecnologias:** HTML5, CSS3, JavaScript vanilla.
* **Demo online:** [Acessar Caesar Cipher](https://giovannijorge.github.io/html-mimo/projetos-gerais/caesar-cipher/)

### Rick and Morty
* **Descrição:** Explorador de personagens que consome a API pública Rick and Morty. Apresenta listagem com filtros (nome, status, espécie, gênero), paginação de resultados e visualização de detalhes em modal.
* **Tecnologias:** HTML5, CSS3, JavaScript vanilla, Fetch API.
* **Demo online:** [Acessar Rick and Morty](https://giovannijorge.github.io/html-mimo/projetos-gerais/rick-and-morty/)

## Como usar

### Opção 1: Clonar e abrir localmente
```bash
# Clonar o repositório
git clone [https://github.com/GiovanniJorge/html-mimo.git](https://github.com/GiovanniJorge/html-mimo.git)
cd html-mimo

# Abrir um projeto no navegador (Exemplo: Caesar Cipher)
# No Linux/macOS:
open projetos-gerais/caesar-cipher/index.html
# No Windows:
start projetos-gerais/caesar-cipher/index.html
```

### Opção 2: Usar um servidor local (Recomendado para consumo de APIs)
Para evitar bloqueios de políticas de CORS em navegadores modernos durante requisições, inicie um servidor HTTP local na pasta do projeto desejado:

```bash
# Com Python 3:
cd projetos-gerais/rick-and-morty
python -m http.server 8000

# Com Node.js (se tiver o pacote http-server instalado globalmente):
npx http-server
```
Acesse `http://localhost:8000` no seu navegador.

## Contribuindo

Contribuições são bem-vistas! Se deseja adicionar um novo exercício ou corrigir alguma funcionalidade, siga os passos abaixo:

1. Faça um **Fork** do repositório.
2. Crie uma branch com nome descritivo: `feature/novo-projeto` ou `fix/melhorar-acessibilidade`.
3. Faça commits atômicos com mensagens claras e objetivas.
4. Abra um **Pull Request** detalhando as alterações implementadas.

## Licença
Este repositório utiliza a licença MIT — consulte o arquivo [LICENSE](LICENSE) na raiz.

## Autor / Contato
- **Autor:** Giovanni Jorge  
- **Repositório:** [https://github.com/GiovanniJorge/html-mimo](https://github.com/GiovanniJorge/html-mimo)
