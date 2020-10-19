# Atividade-4
Recuperação Extra Desenvolvimento de Sistemas
<DOCTYPE HTML>
<html lang="pt-br">
	<head>
		<title>
			Loja de Bijuterias
		</title>
		<meta charset="UTF-8">
	</head>
	<body>
    <small>
         <h1>Bijuterias online</h1>

		<div>
    <label for="login">Login:</label>
    <input type="text" id="login" name="login">
</div>

	<br>
	
<div>
    <label for="senha">Senha:</label>
    <input type="senha" id="senha" name="senha"
           minlength="8" required>
</div>

<br>

<input type="submit" value="Entrar" onclick="msg()">
<script>
function msg() {
  alert("Tela logada");
}
</script>
<br>
<br>

<h2> Cadastro de usuário</h2>

<div>
    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="Nome">
</div>

	<br>
    
<div>
    <label for="sobrenome">Sobrenome:</label>
    <input type="text" id="sobrenome" name="sobrenome">
</div>

	<br>
	
<div>
    <label for="senha">Senha:</label>
    <input type="senha" id="senha" name="senha"
           minlength="8" required>
</div>

<br>

<input type="submit" value="Cadastrar">
<form>
<br>
  <input type="button" value="Tela inicial" onclick="msg()">
</form>
<script>
function msg() {
  alert("Loja de Bijuterias");
}
</script>
<br>

<h1>Contato</h1>

	<form method="get" action="/envio_dados.php">
    <input type="text" name="nome" placeholder="Digite seu nome">
    <input type="email" name="email" placeholder="Digite seu email">
    <input type="text" name="mensagem" placeholder="Digite sua mensagem">
</form>
<script>
function displayResult(){
    alert(document.getElementById("Mensagens cadastradas").rows.length);
}
</script>
<table id="Mensagens cadastradas" border="1">
    <tr>
        <td>Cadastro concluído</td>
        <td>1</td>
    </tr>
    <tr>
        <td>Cadastro concluído</td>
        <td>2</td>
    </tr>
</table>
