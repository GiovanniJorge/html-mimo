# Typewriter Portfolio

![Preview do projeto](preview.png)

Demo online: [https://giovannijorge.github.io/html-mimo/projetos/typewriter-portfolio/](https://giovannijorge.github.io/html-mimo/projetos/typewriter-portfolio/)

Descrição
--------
Typewriter Portfolio é um pequeno site de portfólio pessoal construído com HTML, CSS e JavaScript. O destaque do projeto é um efeito de "máquina de escrever" no cabeçalho que apresenta frases/ocupações dinamicamente, trazendo um toque animado e moderno à página. O projeto serve como exercício de manipulação do DOM, animações com JavaScript e boas práticas de front-end para apresentação pessoal.

Funcionalidades
--------------
- Efeito de máquina de escrever (typewriter) para frases no cabeçalho.
- Seções comuns de portfólio: Sobre, Projetos, Habilidades e Contato.
- Navegação suave (smooth scroll) entre seções.
- Grid responsivo para exibição de projetos.
- Botões/links para redes sociais e recursos externos.
- Tratamento de estados visuais (carregamento de animações, foco para acessibilidade).
- Layout responsivo para mobile e desktop.

Como usar
--------
1. Abra o arquivo `index.html` localmente no navegador ou acesse a demo online:
   - [https://giovannijorge.github.io/html-mimo/projetos/typewriter-portfolio/](https://giovannijorge.github.io/html-mimo/projetos/typewriter-portfolio/)
2. Veja o cabeçalho com o efeito de máquina de escrever e navegue pelas seções.
3. Clique nos cards de projetos para ver mais detalhes (quando disponíveis) ou siga os links para demos/repositórios.
4. Use a navegação superior para saltar entre seções com rolagem suave.

Como funciona
-------------
O efeito de máquina de escrever é implementado em JavaScript puro:
- Uma lista de frases é iterada; cada frase é digitada caractere por caractere, com controle de velocidade de digitação e pausa.
- Após a pausa, a frase pode ser apagada caractere a caractere para que a próxima seja escrita (loop contínuo).
- O restante do site usa manipulação simples do DOM para renderizar a lista de projetos e ativar a navegação suave.
- O layout e as animações são feitos com CSS, mantendo separação de responsabilidades entre HTML, CSS e JS.

Boas práticas aplicadas:
- Separação clara entre estrutura (HTML), estilo (CSS) e comportamento (JS).
- Elementos interativos acessíveis via teclado e com foco visível.
- Uso de atributos `alt` em imagens e labels em formulários.
- Layout responsivo e uso mínimo de bibliotecas externas para facilitar estudo.

Exemplos
--------
- Frases exibidas no efeito typewriter:
  - "Desenvolvedor Front-end"
  - "Criando interfaces acessíveis"
  - "JavaScript, HTML e CSS"
- Interação:
  - Ao visitar a página, a primeira frase é digitada automaticamente.
  - A navegação do menu leva diretamente à seção correspondente com rolagem suave.

Arquivos principais
-------------------
- `index.html` — interface do usuário e marcação das seções do portfólio.
- `style.css` — estilos, layout responsivo e animações CSS.
- `script.js` — lógica do efeito typewriter, navegação suave e manipulação do DOM.
- `preview.png` — imagem de preview usada neste README.

Tecnologias
-----------
- HTML5
- CSS3
- JavaScript (vanilla)

Acessibilidade e boas práticas
------------------------------
- Foco em elementos interativos (links, botões) para navegação por teclado.
- Labels e atributos `aria` quando aplicáveis para compatibilidade com leitores de tela.
- Contraste e tamanhos de fonte pensados para legibilidade.
- Indicação clara de estados visuais (animação ativa, foco).

Contribuição
------------
Contribuições são bem-vindas. Sugestões:
- Adicionar mais frases ou opções de configuração ao efeito typewriter (velocidade, loop, delay).
- Melhorar o SEO e metadados do site.
- Incluir testes e documentação adicional do JavaScript.
- Implementar formulário de contato funcional (ex.: integração com serviço de backend ou Formspree).

Para contribuir:
1. Fork este repositório.
2. Crie uma branch com sua feature: `git checkout -b minha-feature`.
3. Faça commits descritivos.
4. Abra um Pull Request descrevendo as mudanças.

Licença
-------
Nenhuma licença específica foi adicionada a este repositório por enquanto. Se desejar permitir reuso explícito, adicione um arquivo `LICENSE` (por exemplo MIT).

Autor
-----
Giovanni Jorge — repositório principal: [GiovanniJorge/html-mimo](https://github.com/GiovanniJorge/html-mimo)

Contato
-------
Problemas, dúvidas ou sugestões podem ser abertas como issues no repositório ou enviadas via perfil do GitHub.
