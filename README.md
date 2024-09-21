<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./style.css"/>
    <link rel="preconnet" href="https://fonts.googleapis.com">
    <link rel="preconnet" href="https://fonts.gstatic.com"> <crossorigin>
    <link href=" https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;900&display=swap" rel="stylesheet">
 
    <title>Formulário</title>
</head>
<body>
    <div class="container">
        <div class="header">
            <h2> Criar uma conta</h2>

        </div>
        <form id="form" class="form"> 
            <div class="form-control">
                <label for="username">Nome do usuário</label>
                <input type="text" id="username" 
                placeholder="Digite o seu nome de usuário..."/>
                <i class="fas fa-exclamation-circle"></i>
                <i class="fas fa-checkp-circle"></i>
                <small>Mensagem de erro</small>
            </div>
            <div class="form-control">
                <label for="email">Email</label>
                <input type="text" id="email" placeholder="Digite o seu email..."/>
                <i class="fas fa-exclamation-circle"></i>
                <i class="fas fa-checkp-circle"></i>
                <small>Mensagem de erro</small>
            </div>
            <div class="form-control">
                <label for="password">Senha</label>
                <input type="password" id="password" placeholder="Digite sua senha..."/>
                <i class="fas fa-exclamation-circle"></i>
                <i class="fas fa-checkp-circle"></i>
                <small>Mensagem de erro</small>
            </div>
            <div class="form-control">
                <label for="password-confirmation">Confirmação de senha</label>
                <input type="password" id="password-confirmation" 
                placeholder="Digite a senha novamente..."/>
                <i class="fas fa-exclamation-circle"></i>
                <i class="fas fa-checkp-circle"></i>
                <small>Mensagem de erro</small>
            </div>
            <button type="submit">Enviar</button>
        </form>

    </div>
    <script src="https://kit.fontawesome.com/0e86200601.js" crossorigin="anonymous">
 </script>

 <script src="./scripts.js"></script>
</body>
</html>
