# Loja virtual JavaScript
O projeto consiste em um e-commerce fictício, que vende decorações natalinas. 
Possui diversas funcionalidades de e-commerce, como carrinho de compras, 
atualização de estoque, formulário para finalização da compra, página de
pagamento e listagem de compras já realizadas.

Grande parte das funcionalidades se baseia na utilização do Local Storage,
pois todas as manipulações de produtos e registro de compras passam por ele.
Como é um projeto simples, que só utiliza JavaScript, o banco de dados foi
substituído pelo Local Storage. 

O formulário possui validação de preenchimento em todos os campos, caso o 
usuário já tenha realizado uma compra anteriormente, ao colocar o CPF no 
primeiro campo do formulário, o resto já é preenchido automaticamente. 
Além disso, ao digitar o CEP, é feita uma busca na API dos correios, que 
preenche os campos de endereço com a resposta da API.

A biblioteca iziToast foi utilizada para mostrar os alerts e a biblioteca
Cleave.js para formatação de inputs no formulário, adicionando máscara de 
CPF e CEP.

Esse foi um projeto pedido na aula de Scripts do segundo semestre da Fatec,
e os commits dele estão no meu repositório "https://github.com/micaelmi/fatec-js",
mas como foi um projeto que ficou bem legal e completo, decidi fazer um 
repositório só para ele.

Desenvolvido com participação de Mayara Ribeiro (https://github.com/mayaribeiro)

Acesse o site: https://micaelmi.github.io/e-commerce-js/


## Tecnologias e bibliotecas
- HTML
- CSS
- JS
- Local Storage
- API ViaCep https://viacep.com.br/
- IziToast https://github.com/marcelodolza/iziToast
- Cleave.js https://nosir.github.io/cleave.js/

FELIZ NATAL!
