# Javascript-Tutorial


### Javascript

O javascript vai ser a linguagem usada para manipular o comportamento dos elementos de uma página web, ou seja, ela vai agir junto com o HTML e CSS para criar, por exemplo, efeitos quando você clica em um botão, ou para mostrar e esconder um menu, ou para avisar quando um formulário não estiver corretamente preenchido.

Um **Hello Word** talvez ajude a visualizar melhor o funcionamento.

```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <title>Hello Word</title>
    <meta charset="utf-8">
  </head>
  <body>
 	<script type="text/javascript">
		alert('Hello World!');
	</script>
  </body>
</html>
```

Se você copiar esse código e colocar em um arquivo com extenção ```.html``` (```example.html```), vai ver que uma mensagem ```Hello World!```.

Antes de passar para o conceito de JQuery, talvez seja interessante ver dois conceitos: variáveis e funções.

#### Variáveis 

As variáveis no js tem tipagem dinâmica, ou seja, a variável pode armazenar conteúdos de diferentes tipos no código.

```javascript
// variáveis globais
var nome = "gabriela";
var idade = 22;
// variáveis globais
curso = "bti"
```

Uma variável declarada fora de uma definição de função é uma variável global, e seu valor será acessível e modificável em todo o seu programa.  Uma variável declarada dentro de uma definição de função é local.  Ela é criada e destruída sempre que a função é executada e não pode ser acessada por qualquer código fora da função. 

[1] https://www.javascript.com/try

