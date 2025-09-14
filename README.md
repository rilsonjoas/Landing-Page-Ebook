# E-book Grátis: Sermões Temáticos e Expositivos para Sua Pregação

## Descrição

Este projeto implementa uma página web de captura de leads para um e-book gratuito com sermões temáticos e expositivos, utilizando HTML, CSS e JavaScript. A página tem como objetivo atrair pastores e líderes religiosos interessados em aprimorar sua pregação, oferecendo um e-book como recurso gratuito em troca de um endereço de e-mail. A página inclui um design visual atraente, informações sobre o autor e um formulário de inscrição para baixar o e-book.

## Funcionalidades

A página de captura oferece as seguintes funcionalidades:

*   **Chamada Atrativa:**
    *   Um título principal e um subtítulo que destacam o benefício de adquirir o e-book.
    *   Indicação de que o e-book é grátis por tempo limitado.
*   **Apresentação do Autor:**
    *   Foto do autor e informações sobre sua credibilidade, como sua formação teológica e experiência pastoral.
*   **Formulário de Captura:**
    *   Campo para inserir o endereço de e-mail.
    *   Botão para baixar o e-book e realizar o cadastro.
*   **Design Atraente:**
    *   Design visualmente agradável, incluindo um fundo com textura sutil, uso de imagens e ícones.
    *  Layout responsivo que se adapta a diferentes telas.
*   **Animações:**
    *  Ícones e outros elementos interativos

## Tecnologias Utilizadas

*   **Linguagem de Marcação:** HTML (para a estrutura da página)
*   **Linguagem de Estilização:** CSS (para o design da página e layout responsivo)
*   **Linguagem de Programação:** JavaScript (para interação com biblioteca de ícones animados)
*   **Bibliotecas:**
     * LordIcon: (para animações)

## Como Executar

1.  **Requisitos:**
    *   Navegador web moderno (Google Chrome, Mozilla Firefox, Safari, etc.).
2.  **Clonar Repositório:** Clone o repositório para sua máquina.
3.  **Abrir o arquivo HTML:** Abra o arquivo `index.html` em seu navegador web.

A aplicação será executada diretamente no seu navegador, sem necessidade de um servidor web.

## Estrutura do Projeto

*   `index.html`: Arquivo principal com a estrutura HTML da página.
*   `styles.css`: Arquivo com os estilos CSS para a página.
 * `images/`: Pasta com imagens e logo utilizados na aplicação
        * `favicon.ico`: Favicon da aplicação
        *  `ide2.png`: Imagem de um livro
        * `gilson.png`: Foto do autor

## Funcionamento do Código HTML (`index.html`)

*   **Estrutura Geral:**
    *   Um container externo para centralizar o conteúdo da página e definir o estilo da página.
     * Um container interno para organizar os elementos da página em flex-box.
     * As imagens do livro e o card do autor também são organizados com flexbox.
*   **Chamada:**
    *   Exibe a frase curta "ebook • grátis hoje" e o título principal com a promessa do e-book.
    *   Exibe a imagem do livro.
*   **Card do Autor:**
    *   Exibe a imagem, nome, autoria e informações de credibilidade do autor.
*   **Formulário de Download:**
    *   Contém o campo para inserir o endereço de e-mail, com ícone decorativo.
    *   Botão para baixar o e-book e um texto indicando a gratuidade por tempo limitado.

## Funcionamento do Código CSS (`styles.css`)

*   **Estilos Globais:**
    *   Define a fonte principal (Arial) e os estilos para o fundo da página e outros elementos.
*   **Layout da Página:**
    *   Define o layout flexível para centralizar e organizar os elementos na página.
    *  Define os estilos para o card do autor, input de e-mail e botão.
    * Define estilos para as imagens e outras decorações.
*   **Layout Responsivo:**
    *   Utiliza media queries para ajustar o layout e a exibição dos elementos em telas menores, como a exibição da imagem do livro principal e o tamanho do texto.

## Funcionamento do Código JavaScript

*  A biblioteca LordIcon é utilizada para inserir ícones animados na página. No entanto, a página por si só não possui nenhuma lógica em JavaScript.

## Contribuindo

Se você deseja contribuir com este projeto, sinta-se à vontade para:

*   Reportar bugs ou sugerir melhorias através de issues.
*   Enviar pull requests com suas modificações.

## Autor

*   Rilson Joás

## Observações

*   Este projeto é um exemplo simples, criado para fins de estudo e demonstração de como criar uma página de captura de leads.
*   Não há nenhuma integração de backend com serviços de e-mail ou armazenamento de dados, pois isso está fora do escopo do projeto.
*   A estilização CSS pode ser aprimorada para personalizar a aparência da página.