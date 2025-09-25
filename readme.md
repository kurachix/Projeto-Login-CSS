# Tela de Login

Este projeto é um exemplo simples de **tela de login responsiva**, desenvolvida com **HTML e CSS**.  
Ele serve como prática para iniciantes que estão aprendendo a estruturar páginas e aplicar estilos básicos.

---

## Estrutura de Arquivos

```

projeto-login/
│── index.html
│── style.css

````

---

## Demonstração

A tela final contém:
- Um título informativo no topo.
- Uma caixa centralizada de login com:
  - Campo de **email**.
  - Campo de **senha**.
  - Botão estilizado para envio.

---

## Código Final

### index.html
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tela de Login</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h2>Faça login para Acessar o Sistema</h2>

    <div class="login-box">
      <h3>Login</h3>
      <form>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Digite seu email">

        <label for="senha">Senha:</label>
        <input type="password" id="senha" name="senha" placeholder="Digite sua senha">

        <button type="submit" aria-label="Entrar no sistema">Login</button>
      </form>
    </div>
  </div>
</body>
</html>
````

---

### style.css

```css
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #dcdcdc;
}

.container {
  text-align: center;
  margin-top: 40px;
}

h2 {
  background-color: #111;
  color: #fff;
  padding: 20px;
  text-align: left;
  width: 60%;
  margin-left: 5%;
  box-sizing: border-box;
}

.login-box {
  background: #f9f9f9;
  width: 420px;
  margin: 30px auto;
  padding: 22px;
  border-radius: 8px;
  box-shadow: 0 1px 4px rgba(0,0,0,0.1);
}

.login-box h3 {
  text-align: left;
  color: #1d1a39;
  margin: 0 0 10px 0;
}

form {
  display: flex;
  flex-direction: column;
}

label {
  margin: 10px 0 6px;
  font-size: 13px;
  text-align: left;
}

input {
  padding: 10px;
  border: 1px solid #ddd;
  border-radius: 6px;
  outline: none;
  box-sizing: border-box;
}

input::placeholder {
  color: #bbb;
}

button {
  margin-top: 18px;
  padding: 10px;
  background: #00d25b;
  color: #fff;
  border: none;
  border-radius: 6px;
  cursor: pointer;
}

button:hover {
  background: #00b24f;
}
```

---

## Como Executar

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` em qualquer navegador.
3. A tela de login será exibida.

---


## Observações

* Este formulário é **somente visual** (não conectado a servidor).
* Pode ser usado como base para futuros projetos com **JavaScript** ou integração em **back-end**.

---

```
