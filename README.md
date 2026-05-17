# lift-pod
let produto=
document.getElementById("produtoNome").innerText;

let telefone=
document.getElementById("telefone").value;

let mensagem=
`Olá! Fiz o pedido do produto ${produto}. Nome: ${nome}. Telefone: ${telefone}. Estou enviando o comprovante do PIX.`;

let url=
"https://api.whatsapp.com/send?phone=5567992039174&text="
+encodeURIComponent(mensagem);

document.getElementById("btnWhatsapp")
.href=url;

irParaEtapa(4);

}

</script>

</body>
</html>
