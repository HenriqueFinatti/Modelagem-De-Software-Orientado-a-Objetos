PROJETO MODELAGEM DE SOFTWARE ORIENTADO A OBJETO:

\- Primeiramente teremos um ator responsável por cadastrar os eleitor que irão votar a partir do documento pessoal e comprovante de residência.(foto será opcional)

\- O candidato só poderá se cadastrar caso ela já estiver cadastrador como eleitor, informando cargo que estão concorrendo, nome, apelido, numero e fotografia

\- O UEv será controlado pelo sistema de cadastro, onde define local para votar e muda a flag caso ele já tenha votado, assim evitando votos duplicados e verificando se o eleitor esta votando no lugar correto, caso esteja fora da região não será permitido o voto.

\- 





Trazer os casos de uso, não precisa ser um monte mas trazer valor nos casos e identificar os atores.

organizar fluxo principal e alternativo.



----------------------------------------



Use case:

1\) \*\*Votar\*\*

Ator: Eleitor. 

Fluxo Principal:

* O eleitor irá se identificar a partir do documento pessoal;
* Validar o documento para ver se está cadastrado como eleitor(documentação, lugar certo, já votou);
* Selecionar o candidato;
* Eleitor verifica se as informações do candidato esta correto;
* Eleitor confirma o voto;
* A UEg contabiliza o voto e flegua que já votou (include na parte de fleguar o voto, seria o site);



Fluxo Alternativo (voto em branco):

* O eleitor escolhe a opcao "voto em branco";
* Confirmar o voto;
* A UEv contabiliza voto em branco;





Fluxo Alternativo (voto nulo):

* O eleitor escolhe a opcao "voto em branco";
* Confirmar o voto;
* A UEv contabiliza voto em nulo;



2\) \*\*Contabilizar os votos\*\*

Ator: Administrador.



3\) \*\*Verificar resultado\*\*

Ator: Administrador



================================================================



4\) \*\*Ver lista de candidatos\*\*

Ator: Administrador



5\) \*\*Ver lista de eleitores\*\*

Ator: Administrador



6\) \*\*Validar informações de cadastro\*\*

Ator: Site de Cadastro



7\) \*\*













