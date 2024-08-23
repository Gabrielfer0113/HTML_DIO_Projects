<h1>Tags</h1>

|TAG|Exemplo|
|---|-------|
|<.i></.i>|\|<i>Ele deixa o texto em italico</i>|
|<.Strong><./Strong>|\|<strong>Deixa em negrito</strong>|
|<.input>|\|Ele cria um campo para digitar <input>|
|<.br>|\|Ele pula a linha<br>|
|h1,2,3,4,...|\|O "h(numero)" seria usado para determinar um titulo|
|<.mark></.mark>|\|Ele marca a parte do texto como se fosse um marcador de texto|
|<.sup><./sup>|\|Ele deixa o texto escrito acima da metade da linha|
|<.u><./u>|\|Ele sublinha o texto marcado|
|<.ol><./ol>|\|É uma lista ordenada|
|<.li><./li>|\|Ele seria o item dentro da lista, ele é usado em conjunto do <.ol><./ol>|
|<.ul><./ul>|\|É uma lista não ordenada|
|<.a><./a>|\|Ele é usado para linkar a sua pagina Web a outra a partir do link|
|<.hr>|\|Ele cria uma linha horizontal na pagina|
|<.p>|\|Paragrafo|
|<.sub><./sub>|\|Ela deixa o texto pequeno e coloca na parte de baixo da linha|
|<.sup><./sup>|\|Ela deixa o texto pequeno e coloca na parte de acima da linha|
|<.blockquote><./blockquote>|\|?|
|<.form><./form>|\|Esse comando é usado para fazer campos de formularios no site, ele é usado juntamente com o comando "input". Exemplo:     
    <.form>
        Nome: <.input type="text" name="name"/><.br>
        Idade: <.input type="number"  name="age"/><.br>
        Senha: <.input type="password" name="password"/><.br>
        <.button type="submit">Enviar</.button>
    </.form>|
|||
|----------------|-------|
|<.option></.option>|\|Ele é usado em conjunto do comando 'select' para fazer uma barra de seleção.
|<.select></.select>|\|Ele é usado para fazer um campo de seleção dentro da barra de seleção. Exemplo:
    <.label>Cargo:</.label>
    <.select name="role">
        <.option value="">Escolha uma opção</.option>
        <.option value="Gerente">Gerente</.option>
        <.option value="Diretor">Diretor</.option>
        <.option value="Presidente">Presidente</.option>
    </.select>|
|||
|----------------|-------|
|<.audio><./audio>|\|Essa tag é usado para colocar audios mp3 no seu web site|
|<.source/>|\|É uma tag filha da tag "audio"|
||\||

|Atributo de Tags|Exemplo|
|----------------|-------|
|id=""|\|Ele é um identificador de tal elemento, JS|
|style=color:(cor)>;|\|Ele é usado com o CSS para formatar de uma formar que você queira|
|class=""|\|ele padroniza oque tiver a classe que estiver dentro de "class"|
|type=""|\|Dentro do "type" você pode usar varios tipos de comandos que modificam o programas, Ex: text, number, color, etc|
|src=""|\|seria um atributo junto com a tag "img, audio, video" que ele procura o link da imagem na internet ou no seu computador|
|width|\|Ele define a largura de tal elemento|
|href=""|\|É usado para colocar um link dentro que vai te mandar para outro site, usado com a tag <.a><./a>|
|target=""|\|Esse atributo é usado no momento que for abrir um link, ele cria duas opções principais "blank" e "self", a blan       k abrira uma nova pagina para aquele link, e o self ele substitui a pagina atual pela a do link|
|title=""|\|Ele cria uma mensagem que ira ser criada caso o usuario deixe o cursor em cima do link|
|action="link"|\|Ele é usado para mandar um formulario para o link que esta destinado no código|
|autocomplete="on/off"|\|Esse atributo é para que aquela mensagem de salvar a senha apareça na tela do usuario, obs: deixar o "autocomplete" no modo "on"|
|on(mensagem)=""|\|o comando "on(mensagem)" tem varias variaveis, uma delas é "onsubmit", ou seja, quando a pessoa fizer o submit tal coisa acontece, mas isso é normalmente usado com o JS implementado no site|
|min=""|\|Define o minimo numerico|
|max=""|\|Define o maximo numerico|
|step=""|\|Ele define a quantidade de casas que vai pular usando as setas|
|method=""|\|Ele é usado para mandar uma mensagem para o servidor, Exemplo: 
    <.form method=(post,get,dialog)>
        Ele mandaria a informação util que estaria aqui para o servidor e a linguagem backend faria o seu serviço
    </.form>
|||
|----------------|-------|
|name=""|\|Ele serve para identificar uma variavel no HTML. Exemplo: 
    <.form method="post">
        <.input type="text" name="(nome da variavel)" value="(Nome do que o usuario vai selecionar)"/>
    </.form>|
|||
|----------------|-------|
|value=""|\|Ele é usado para colocar uma valor para o atributo. Exemplo:
    <.form method="post">
        <.input type="text" name="Pão" value="Pão frances"/>
    </.form>|
|||
|----------------|-------|
|rows=""|\|Ele define a quantidade de linhas a tag <.textarea></.textarea> vai ter|
|cols=""|\|Ele define a quantidade de colunas a tag <.textarea></.textarea> vai ter|
|controls|É usado dentro da tag "audio", serve para colocar controles no audio|
||\||
||\||





