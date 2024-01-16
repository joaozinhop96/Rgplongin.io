<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Ficha de RPG</title>
  <style>
    body {
      background-color: black;
      color: white;
      font-family: Arial, sans-serif;
    }

    h1 {
      color: white;
      text-align: center;
    }

    .section {
      margin-bottom: 20px;
    }

    .section-title {
      color: white;
      font-size: 20px;
      margin-bottom: 10px;
    }

    .section-content {
      color: white;
    }

    table {
      border-collapse: collapse;
      width: 100%;
    }

    th, td {
      border: 1px solid white;
      padding: 8px;
      text-align: left;
    }

    .editable {
      border: none;
      background-color: transparent;
      color: white;
      width: 100%;
    }

    .editable:focus {
      outline: none;
    }

    .button {
      display: inline-block;
      background-color: white;
      color: black;
      border: none;
      padding: 8px 16px;
      text-align: center;
      text-decoration: none;
      font-size: 14px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .button:hover {
      background-color: #ccc;
    }
  </style>
</head>
<body>
  <h1>Ficha de RPG</h1>

  <div class="section">
    <div class="section-title">Informações do Personagem</div>
    <div class="section-content">
      <table>
        <tr>
          <th>Nível</th>
          <td><span class="editable" contenteditable="true">1</span></td>
        </tr>
        <tr>
          <th>Nome do Personagem</th>
          <td><span class="editable" contenteditable="true">Nome do Personagem</span></td>
        </tr>
        <tr>
          <th>Nome do Jogador</th>
          <td><span class="editable" contenteditable="true">Nome do Jogador</span></td>
        </tr>
        <tr>
          <th>Nome da Campanha</th>
          <td><span class="editable" contenteditable="true">Nome da Campanha</span></td>
        </tr>
        <tr>
          <th>Origem do Personagem</th>
          <td><span class="editable" contenteditable="true">Origem do Personagem</span></td>
        </tr>
      </table>
    </div>
  </div>

  <div class="section">
    <div class="section-title">Inventário</div>
    <div class="section-content">
      <table>
        <tr>
          <th>Item</th>
          <th>Quantidade</th>
        </tr>
        <tr>
          <td><span class="editable" contenteditable="true">Item 1</span></td>
          <td><span class="editable" contenteditable="true">1</span></td>
        </tr>
        <tr>
          <td><span class="editable" contenteditable="true">Item 2</span></td>
          <td><span class="editable" contenteditable="true">3</span></td>
        </tr>
      </table>
    </div>
  </div>

  <div class="section">
    <div class="section-title">Atributos</div>
    <div class="section-content">
      <table>
        <tr>
          <th>Atributo</th>
          <th>Valor</th>
        </tr>
        <tr>
          <td>Força/Físico</td>
          <td><span class="editable" contenteditable="true">10</span></td>
        </tr>
        <tr>
          <td>Vigor/Vida</td>
          <td><span class="editable" contenteditable="true">15</span></td>
        </tr>
        <tr>
          <td>Carisma/Presença</td>
          <td><span class="editable" contenteditable="true">8</span></td>
        </tr>
        <tr>
          <td>Destreza/Agilidade</td>
          <td><span class="editable" contenteditable="true">12</span></td>
        </tr>
        <tr>
          <td>Kagune</td>
          <td><span class="editable" contenteditable="true">Tipo de Kagune</span></td>
        </tr>
        <tr>
          <td>Perícias</td>
          <td><span class="editable" contenteditable="true">Perícia 1, Perícia 2</span></td>
        </tr>
      </table>
    </div>
  </div>

  <div class="section">
    <div class="section-title">História</div>
    <div class="section-content">
      <textarea class="editable" rows="5" contenteditable="true">Digite a história do personagem aqui...</textarea>
    </div>
  </div>

  <div class="section">
    <div class="section-title">Habilidades</div>
    <div class="section-content">
      <ul>
        <li><span class="editable" contenteditable="true">Habilidade 1</span></li>
        <li><span class="editable" contenteditable="true">Habilidade 2</span></li>
        <li><span class="editable" contenteditable="true">Habilidade 3</span></li>
      </ul>
    </div>
  </div>

  <div class="section">
    <div class="section-title">Contatos</div>
    <div class="section-content">
      <table>
        <tr>
      </table>
    </div>
  </div>

  <div class="section">
    <div class="section-title">Anotações</div>
    <div class="section-content">
      <textarea class="editable" rows="5" contenteditable="true">Digite suas anotações aqui...</textarea>
    </div>
  </div>

  <div class="section">
    <button class="button">Salvar</button>
    <button class="button">Imprimir</button>
  </div>

</body>
</html>
