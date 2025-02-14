# Gerador de Nomes Aleatórios

Este é um projeto de um **Gerador de Nomes Aleatórios** feito com HTML, CSS e JavaScript. O projeto permite ao usuário selecionar uma categoria e gerar um nome aleatório baseado nessa categoria.

## Funcionalidades

- O usuário pode escolher entre as seguintes categorias:
  - Personagens
  - Cidades
  - Animais
  - Homem
  - Mulher
- O nome gerado é exibido de forma destacada na tela.

## Tecnologias Utilizadas

- **HTML**: Estrutura do site.
- **CSS**: Estilização e layout do site, garantindo um design responsivo e moderno.
- **JavaScript**: Função de gerar nomes aleatórios e manipulação de eventos.

## Como Usar

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` em seu navegador.
3. Selecione uma categoria no menu suspenso.
4. Clique no botão **"Gerar Nome"** para ver um nome aleatório gerado.
5. O nome gerado será exibido abaixo do botão.

## Exemplo de Uso

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gerador de Nomes Aleatórios</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Gerador de Nomes Aleatórios</h1>
        <label for="categoria">Escolha uma categoria:</label>
        <select id="categoria">
            <option value="personagens">Personagens</option>
            <option value="cidades">Cidades</option>
            <option value="animais">Animais</option>
            <option value="homem">Homem</option>
            <option value="mulher">Mulher</option>
        </select>
        <button id="gerar">Gerar Nome</button>
        <p id="resultado"></p>
    </div>
    <script src="scrypt.js"></script>
</body>
</html>
