# To-do-list-nodejs

### Sobre

Fiz este projeto para trabalhar minhas habilidades iniciais em **Nodejs**, trabalhando com **rotas**, **method post** no formulário.

#### Foi usado:


1. **Nodejs**
   - Para dar vida a página.
   - Criação de rotas
     - Criação de uma rota para deletar um item com base no ID
     
2. **Express**
   - Como  framework para o Nodejs
   
2. **CSS3**
   - Para fazer a estilização da página.
   
3. **EJS**
   - Para transportar dados do back-end para o front-end facilmente.

#


### Como funciona

No **front-end**, foi feito o formulário com o **method post**, com 2 (dois) inputs, 1 (um) type text, e 1 (um) type submit.

Indo para o **back-end**, fiz um array para armazenar os itens da lista, sendo que 3 (trêz) já vêm predefinidos. Como o formulário está com o **method post**, eu pego o value inserido no input e do um **push** no array, e pelo pra renderizar a página já com o array atualizado.

Foi criada uma rota para deletar os itens da lista com base no Id de cada item, depois de deletado eu do um redirect na página inical, e, renderizo a nova lista com o item já excluido.

Voltando para o **front-end**, apliquei um **for** em um template de cada item, fazendo com que multiplique o template de acordo o tamanho do array, e nele atribui o valor do Id de acordo sua posição no array, então quando clica no botão de excluir, já é indentifica qual o item que foi clicado; fazendo assim a exclusão do mesmo.

### *Ideias*

Caso tenha alguma ideia que eu possa melhorar nesse projeto ou qualquer outra ideia, manda uma **Issues** para eu conseguir ver suas ideias!!!
