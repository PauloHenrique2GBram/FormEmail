# FormEmail

## Estudos sobre Formulário enviados com API FormSubmit

- Caso 1
  - Como criou o formulário:
Na criação do formulário foi utilizada a tag form com uso de ("https://formsubmit.co/p.damaceno@aluno.senai.br"), que permite uso de inputs do tipo submit que tem a função de enviar os dados;
Utilizado o método (method) POST para que as informações fossem enviadas, sem que sejam expostas, caso contrário utilizar GET;
Para que o submit funcione corretamente, em todos os INPUT foi adicionado a tag NAME.

- Caso 2
  - Como deixou o formulário funcional (envio de form para um E-mail):
Com o uso de form e (action="https://formsubmit.co/p.damaceno@aluno.senai.br" method="post") é adicionada a API formSubmit (https://formsubmit.co), que permite que os dados adicionados ao formulário através de um botão sejam enviados para o endereço de E-mail que você definir;

- Caso 3
  - Comandos Git que usou para criar e publicar seu repositório no GitHub:
git init
git branch -M main
git add .
git commit -m "comentário"
git remote add origin "link do repositório"
git push -u origin main
