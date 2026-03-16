<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/x-icon" href="book.png">
    <link rel="stylesheet" href="style.css">
    <title>Gerenciamento Bibliotecário</title>
</head>
<body>

<h1 class="titulo-principal">CADASTRO</h1>
    

    <main>
        <section class="container-cadastro">
            <form action="https://drive.google.com/drive/home" method="post">
                <div class="campo">
                    <label for="nome"><strong>NOME DA INSTITUIÇÃO</strong></label>
                    <input type="text" id="nome" name="nome" required>
                </div>

                <div class="campo">
                    <label for="turma"><strong>INEP</strong></label>
                    <input type="text" id="turma" name="turma" required>
                </div>

                <div class="campo">
                    <label for="livro"><strong></strong></label>
                    <input type="text" id="livro" name="livro" required>
                </div>

                <button type="submit" class="btn-enviar">Cadastrar no Sistema</button>
            </form>
        </section>
    </main>

</body>
</html>
