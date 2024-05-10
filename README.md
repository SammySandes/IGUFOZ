<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tabela de Itens</title>
  <style>
    table {
      border-collapse: collapse;
      width: 100%;
    }

    th, td {
      border: 1px solid black;
      padding: 8px;
      text-align: left;
    }

    th {
      background-color: #f2f2f2;
    }
  </style>
</head>
<body>

<table id="tabelaItens">
  <thead>
    <tr>
      <th>Código</th>
      <th>Item</th>
      <th>Quantidade</th>
      <th>Data de Entrega</th>
      <th>Data de Retorno</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td id="ciCodigo">CI#01</td>
      <td>Cadeira Infantil</td>
      <td id="ciQuantidade">6</td>
      <td id="ciEntrega">10/05/2024</td>
      <td id="ciRetorno">15/05/2024</td> <!-- Data de Retorno ajustada manualmente -->
    </tr>
    <tr>
      <td id="boCodigo">BO#02</td>
      <td>Booster</td>
      <td id="boQuantidade">5</td>
      <td id="boEntrega">10/05/2024</td>
      <td id="boRetorno">-</td> <!-- Data de Retorno ainda não determinada -->
    </tr>
    <tr>
      <td id="bcCodigo">BC#03</td>
      <td>Bebê Conforto</td>
      <td id="bcQuantidade">2</td>
      <td id="bcEntrega">10/05/2024</td>
      <td id="bcRetorno">18/05/2024</td> <!-- Data de Retorno ajustada manualmente -->
    </tr>
  </tbody>
</table>

<script>
  // Função para atualizar a data de retorno da cadeira infantil
  function atualizarDataRetornoCadeiraInfantil(novaDataRetorno) {
    document.getElementById("ciRetorno").innerText = novaDataRetorno;
  }

  // Exemplo de como chamar a função para atualizar a data de retorno da cadeira infantil
  atualizarDataRetornoCadeiraInfantil("20/05/2024");
</script>

</body>
</html>
