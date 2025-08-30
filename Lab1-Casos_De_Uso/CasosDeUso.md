|Identificador|UC-01 - Carregar UEv|
|-------------|-----|
|Função|Permite ao administrador carregar as informações da UEg na UEv|
|Atores|Administrador|
|Pré Condição|1. A UEv estar cadastrada<br> 2. A UEg deve estar carregada|
|Pós Condição|A UEv estará carregada|
|Fluxo Principal|1. O administrador entra no sistema da UEg<br> 2. O administrador seleciona a UEv<br> 3. O administrador filtra as informações a serem carregadas<br> 4. O administrador carrega as informações da UEg na UEv |

|Identificador|UC-02 - Contabilizar Votos|
|-------------|-----|
|Função|Permite ao administrador contabilizar os votos registrados nas UEv's|
|Atores|Administrador|
|Pré Condição|Deve ter pelo menos uma UEv cadastrada|
|Pós Condição|Os votos serão contabilizados|
|Fluxo Principal|1. O administrador solicita o envio dos fotos das UEv's cadastrads para a UEg<br> 2. O administrador solicita a UEg para contabilizar os votos|

|Identificador|UC-03 - Cadastrar UEv|
|-------------|-----|
|Função|Permite ao administrador cadastrar uma nova UEv a uma UEg|
|Atores|Administrador|
|Pré Condição|Deve ter pelo menos uma UEg com menos de 100 UEv's cadastradas |
|Pós Condição|Uma nova UEv será cadastrada|
|Fluxo Principal|1. O administrador verifica a disponibilidade das UEg's<br> 2. O administrador cadastra a UEv |
|Fluxo Alternativo|1. O adminsitrador verifica a disponibilidade das UEg's<br> 2. Nenhuma UEg disponível|

|Identificador|UC-04 - Verificar Lista de Candidatos|
|-------------|-----|
|Função|Perminite ao administrador consultar a lista de candidatos cadastrados na UEg|
|Atores|Administrador|
|Pré Condição|A UEg deve estar carregada com as informações do site de cadastro|
|Pós Condição|A lista de candidatos será exibida|
|Fluxo Principal|1. O adminstrador solicitará a UEg para exibir a lista de candidatos. <br> 2. A lista de candadidatos será exibida |

|Identificador|UC-05 - Verificar Lista de Eleitores|
|-------------|-----|
|Função|Permite ao administrador verificar a lista de eleitores cadastrados no site|
|Atores|Administrador|
|Pré Condição|A UEg deve ser carregada com o as informações do site de cadastro|
|Pós Condição|A lista de eleitores será exibida|
|Fluxo Principal|1. O adminstrador solicitará a UEg para exibir a lista de eleitores. <br> 2. A lista de eleitores será exibida |

|Identificador|UC-06 - Divulgar Resultado|
|-------------|-----|
|Função|Permite ao administrador divulgar o resultado da eleição|
|Atores|Administrador|
|Pré Condição|Os votos devem ser contabilizados|
|Pós Condição|O resultado será divulgado|
|Fluxo Principal|1. O administrador solicita a UEg para divulgar os resultados|

|Identificador|UC-07 - Carregar UEg|
|-------------|-----|
|Função|Permite ao administrador carregar a UEg com as informações do site|
|Atores|Administrador|
|Pré Condição|Devem haver informações sobre eleitores e candidatos no site de cadastro|
|Pós Condição|A UEg será carregada com as informações do site de cadastro|
|Fluxo Principal|1. O administrador inicia a UEg <br> 2. O administrador solicita o envio das informações do site de cadastro para a UEg|

|Identificador|UC-08 - Votar|
|-------------|-----|
|Função|Permite ao eleitor votar no seu candidato|
|Atores|Eleitor|
|Pré Condição|1. O eleitor deve estar cadastrado no site de cadastro <br> O eleitor não deve ter votado anteriormente|
|Pós Condição|O voto será contabilizado pela UEv|
|Fluxo Principal|1. O eleitor se identifica a partir do documento pessoal<br> 2. A UEv se comunica com o site de cadastro para validar as informações do eleitor<br> 3. O eleitor seleciona o candidato<br>4. Eleitor confirma o voto<br>5. A UEv contabiliza o voto<br> 6. A UEv se comunica com o site de cadastro para informar que aquele eleitor já votou|
|Fluxo Alternativo 1|3. O eleitor seleciona o voto em branco<br>4. Eleitor confirma o voto<br>5. A UEv contabiliza o voto<br> 6. A UEv se comunica com o site de cadastro para informar que aquele eleitor já votou|
|Fluxo Alternativo 2|3. O eleitor seleciona o voto em nulo<br>4. Eleitor confirma o voto<br>5. A UEv contabiliza o voto<br> 6. A UEv se comunica com o site de cadastro para informar que aquele eleitor já votou|