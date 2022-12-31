<h1 align="center">4° Projeto Individual - Sistema Resilia </h1>


<h6 align="center">Projeto realizado em parceria com   
<a href="https://prefeitura.rio/desenvolvimento-economico-inovacao-simplificacao/programadores-cariocas-comemoram-formatura-na-cidade-das-artes/"        target="_blank">Prefeitura RJ </a> + 
<a href="https://www.resilia.com.br/" target="_blank">Resilia</a> + 
<a href="https://www.rj.senac.br/" target="_blank">Senac.</a> </h6>
<a href="" target="_blank"></a>


<div id="inicio" align=center>
  <a href="#sobre">Sobre</a>&nbsp;&nbsp;&nbsp;
  <a href="#extras">Extras</a>&nbsp;&nbsp;&nbsp;
  <a href="#andamento">Andamento</a>&nbsp;&nbsp;&nbsp;
  <a href="#projeto">Projeto</a>&nbsp;&nbsp;&nbsp;
  <a href="#ferramentas">Ferramentas</a>&nbsp;&nbsp;&nbsp;
  <a href="#autor">Autor</a> 
</div>


<h2 id="sobre">Sobre 🔎</h2>
  <h3>Projeto onde precisei desenvolver uma lógica para um banco de dados. Utilizando meus conhecimentos de Excel e a ferramenta online Miro(para montagem do Modelo) que contempla os requisitos abaixo:</h3>


<h4> Contexo da situação: </h4>
A Resilia está pensando em lançar um novo sistema de
acompanhamento e para isso precisa de ajuda para modelar um
banco de dados que vai armazenar seus cursos, turmas e alunos.


<h4> O que é para ser feito? </h4>
<p>Para apoiar nesse sistema recebemos a tarefa de realizar essa modelagem
e responder algumas perguntas com nosso modelo:<br>
⇨ Existem outras entidades além dessas três?<br>
⇨ Quais são os principais campos e tipos?<br>
⇨ Como essas entidades estão relacionadas?<br>
</p>


<h2 id="extras">Requisitos Extras 🔎</h2>
- Preparar os scripts que vão criar o banco de dados proposto e
adicionar uma pasta chamada SQL com os arquivos.<br>
Andamento: Não incluso.


<h2 id="andamento">Andamento do projeto 📈</h2>
- Incompleto.<br>
Faltando explicação do projeto e Extras.
<br>


<h2 id="projeto">Projeto 📈</h2>

- Print da Modelagem feita no site Miro.com:<br><br>

<div align="center">
  <img width="80%" src="https://user-images.githubusercontent.com/112782424/209417260-41260557-57c6-4f61-942c-d64bf6aee859.jpg" />
</div>

<h3>⇨ Explicação para cada atributo de cada entidade.</h3>

**Acrescentei duas entidades a mais (Unidades e Professor), com essas entidades a mais podemos ter uma noção melhor, como?**<br>

- Com a entidade Unidades, conseguimos saber a onde a entidade Cursos está dando aula, pois dentro da entidade Unidades temos alguns atributos importantes
como "id", "nome", "bairro", "cnpj" etc. <br> 
- Agora com a entidade Professor, conseguimos saber quem está dando aula nos Cursos e nesta entidade Professor especifica bem qual professor é, pois os atributos são "id", "nome", "cpf", etc.<br><br>

**Por que algumas entidades estão relacionadas uma com as outras (FK, chave estrangeira)?**<br>
- Para o nosso banco de dados é fundamental ter elas, pois o relacionamento conseguimos responder algumas perguntas básicas, por exemplo: <br>
> Quantos cursos X tem na unidade Y? <br>
Quais são os cursos que tem na unidade Y? <br>
Quantos alunos matriculados tem na unidade Y? <br>
Quantos alunos tem em sala de aula do curso X? <br>

Essas são algumas perguntas que poderiamos responder fácil com o banco de dados, pois elas estão relacionadas. Caso não conseguíssemos resolver alguma outra pergunta futuramente, poderíamos acrescentar uma FK em uma entidade para solucionar o problema ou dependendo da situação, acrescentar um atributo nas entidades.

<br>

<h3>Print da Modelagem com Excel:</h3>
<div align="center">
  <img width="80%" src="https://user-images.githubusercontent.com/112782424/209417316-bd355299-2e73-4ae3-bcb3-93cee5f47079.png" />
</div>

<h3>Respostas das perguntas: </h3>

> **⇨ Existem outras entidades além dessas três?**<br>
Sim, existem mais duas entidades, "Unidades" e "Professor". <br>
Precisei colocar essas entidades para ter um parâmetro, aonde a entidade "Curso" fica vinculado a entidade "Unidades" e a entidade "Professor" fica vinculado a "Turmas", portanto, todas conectadas para um gerenciamento melhor no banco de dados. <br> <br>

> **⇨ Quais são os principais campos e tipos?**<br>
... <br><br>

> **⇨ Como essas entidades estão relacionadas?**<br>
As entidades estão relacionadas com as chaves estrageiras (FK), como podemos ver na imagem feita no <a href="#projeto"> Miro </a>, em algumas entidades tem um atributo com "id_nomeDaEntidade", fazendo com que elas fiquem relacionadas. <br>

<h2 id="ferramentas">Ferramentas utilizadas nesse projeto 📚</h2>

  - [x] Excel
  - [x] Miro.com


<div id="autor" align="center">
  
  **Criado e desenvolvido por [Matheus Gomes](https://www.linkedin.com/in/matheus-gomes-780339211/).**
  
 <div align="center"> 
  
  <a href="https://github.com/MatheusPCRJ" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733553.png" height="40em" title="GitHub de MatheusPCRJ"></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/matheus-gomes-780339211/" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/145/145807.png" height="40em" title="LinkedIn de Matheus Gomes"></a>&nbsp;&nbsp;&nbsp;&nbsp;
  
  <a href="matheusdev1710@gmail.co"><img src="https://cdn-icons-png.flaticon.com/512/552/552486.png" height="40em" title="Enviar E-mail"></a>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
   
  </div>
</div>
<br>

<div align="center">
  &#11165;&nbsp;<a href="#inicio"><strong>Voltar ao topo</strong></a>&nbsp;&#11165;
</div>
