## Atividade de Front

Para a atividade de seleção, você deve criar uma página web que carregue
dinamicamente os Assuntos disponíveis atualmente no Pixcreen.

Além do assunto, a página deve conter o Prêmio em dinheiro e a meta.
Para assuntos que tem topic_id maior ou igual do que 400, você deverá usar a cor presente em subject_color para estilizar o assunto.

Essas informações devem ser acessadas por requisição AJAX via Axios.
Para isso, basta fazer uma requisição GET para a URL: https://pixcreen.com/topics/json/

Para fazer a chamada Ajax, e popular os dados na página que criou, você pode usar VueJS. Será um diferencial.

Use o Bootstrap como base para o seu CSS e faça alterações usando seus conhecimentos em CSS.

### Links Úteis
https://getbootstrap.com/docs/4.1/getting-started/introduction/

https://vuejs.org



## Atividade de Back (Bônus)

Para a atividade de seleção você deve fazer um arquivo PHP que funcione da seguinte forma:

```
/index.php?email=[EMAIL]&cpf=[CPF]
```

e imprima na tela se o E-mail e o CPF são válidos.

Exemplo:

```
/index.php?email=wgoulart@pixcreen.com&cpf=00000000000
```

Mostra na tela:

```
Seu E-mail wgoulart@pixcreen.com é válido

Seu CPF 000.000.000-00 é inválido.
```

**OBS:** Note que você deverá receber o CPF sem pontos e vírgulas e deverá imprimí-lo com pontos e traço

**OBS2:** Nessa atividade você precisará instalar um servidor Web e o PHP. Para isso, sugerimos a instalação do WampServer

**OBS3:** Você pode simplificar a validação do E-mail testando se ele tem um "@" e ".com".

### Links Úteis
https://howtoubuntu.org/how-to-install-lamp-on-ubuntu

http://www.wampserver.com/en/

## Considerações finais

- As atividades exigem mais do que você sabe e nossa intenção não é que você finalize, mas o quanto você conseguiu avançar na tarefa proposta.
- Use a internet a seu favor. Você é livre pra buscar aquilo que tem dúvida e não sabe. Google e StackOverflow são seus amigos.
- Envie seu código mesmo que não esteja completamente funcional. Comente suas dificuldades no código. Vamos levar em conta todo o seu esforço.
- Entregue seu código em um repositório público do GitHub e nos mande o link. Faça commits pequenos mostrando o quanto você caminhou.
