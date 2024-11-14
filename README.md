# CasaInteligente
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SmartViling</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="form-container">
        <img src="img/logo.png" alt="logotipo" class="logo">
        <form class="client-form">
            <h2>Formulário de Clientes</h2>
            <label for="nome">Nome completo</label>
            <input type="text" id="nome" name="nome" required>
            
            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>
            
            <label for="telefone">Telefone</label>
            <input type="tel" id="telefone" name="telefone" required>
            
            <label>Sexo:</label>
            <div class="radio-group">
                <input type="radio" id="feminino" name="sexo" value="feminino" required>
                <label for="feminino">Feminino</label>
                
                <input type="radio" id="masculino" name="sexo" value="masculino" required>
                <label for="masculino">Masculino</label>
                
                <input type="radio" id="outro" name="sexo" value="outro" required>
                <label for="outro">Outro</label>
            </div>
            
            <label for="nascimento">Data de Nascimento</label>
            <input type="date" id="nascimento" name="nascimento" required>
            
            <label for="cidade">Cidade</label>
            <input type="text" id="cidade" name="cidade" required>
            
            <label for="estado">Estado</label>
            <input type="text" id="estado" name="estado" required>
            
            <label for="endereco">Endereço</label>
            <input type="text" id="endereco" name="endereco" required>
            
            <button type="submit">Enviar</button>
        </form>
    </div>
    <script src="script.js"></script>
</body>
</html>
