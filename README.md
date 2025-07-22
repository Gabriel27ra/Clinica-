
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Clínica Vida Saudável</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background-color: #f4f4f4;
    }
    header {
      background-color: #2e8b57;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    section {
      padding: 20px;
      background-color: white;
      margin: 20px;
      border-radius: 8px;
    }
    h1, h2 {
      color: #2e8b57;
    }
    .servicos img {
      width: 100%;
      max-width: 400px;
      height: auto;
      border-radius: 6px;
    }
    .equipe {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
    }
    .membro {
      flex: 1 1 30%;
      background-color: #e0f2f1;
      padding: 10px;
      border-radius: 6px;
      text-align: center;
    }
    .membro img {
      width: 100px;
      height: 100px;
      border-radius: 50%;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }
    input, select {
      padding: 8px;
      border-radius: 4px;
      border: 1px solid #ccc;
    }
    button {
      background-color: #2e8b57;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <header>
    <h1>Clínica Vida Saudável</h1>
    <p>Cuidando da sua saúde com tecnologia e carinho</p>
  </header>

  <section class="servicos">
    <h2>Nossos Serviços</h2>
    <p>Oferecemos atendimento médico especializado, exames laboratoriais e de imagem com equipamentos modernos, além de acompanhamento nutricional personalizado.</p>
    <img src="https://via.placeholder.com/400x250?text=Atendimento+Médico" alt="Atendimento Médico">
    <img src="https://via.placeholder.com/400x250?text=Exames+Laboratoriais" alt="Exames Laboratoriais">
  </section>

  <section class="equipe">
    <h2>Nossa Equipe</h2>
    <div class="membro">
      <img src="https://via.placeholder.com/100" alt="Dra. Ana">
      <h3>Dra. Ana Silva</h3>
      <p>Médica Clínica Geral</p>
    </div>
    <div class="membro">
      <img src="https://via.placeholder.com/100" alt="Dr. João">
      <h3>Dr. João Mendes</h3>
      <p>Nutricionista</p>
    </div>
    <div class="membro">
      <img src="https://via.placeholder.com/100" alt="Carla">
      <h3>Carla Souza</h3>
      <p>Coordenadora Administrativa</p>
    </div>
  </section>

  <section>
    <h2>Formulário de Contato</h2>
    <form>
      <input type="text" placeholder="Nome" required>
      <input type="email" placeholder="E-mail" required>
      <input type="text" placeholder="Cidade" required>
      <select required>
        <option value="">Selecione o estado</option>
        <option value="DF">DF</option>
        <option value="SP">SP</option>
        <option value="RJ">RJ</option>
        <option value="MG">MG</option>
        <!-- adicione outros estados se quiser -->
      </select>
      <button type="submit">Enviar</button>
    </form>
  </section>

</body>
</html>
