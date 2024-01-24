var usuario = "raul@gmail.com";
var passowrd = "12345678";

function check_login() {
    var email = document.getElementById("email").value;
    var senha = document.getElementById("senha").value;


    if (usuario == email && passowrd == senha) {
        document.location.href = "login.html";
    } else {
        alert("Usuário ou senha errados")
        document.getElementById("forget").style.display = "flex";
    }

}
