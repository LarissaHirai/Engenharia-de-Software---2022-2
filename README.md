Repositório voltado ao armazenamento da atividade 4 realizada no dia 15/09/2022 da disciplina de Engenharia de Software - UFT-Campus Palmas.  

# Ativiade-4 - Requisitos
Na atividade 4 foi proposto o levantamentos de dois requisitos, criação do caso de uso expandido, criação do user story e protótipo, para cada requisito levantado.  

## Requisitos

RQ01 - Efetuar Cadastro  
RQ02 - Efetuar Login

## Casos de uso expandido


##### RQ01 - Efetuar cadastro

-Atores:  
    Usuário - Insere, edita e exclui dados pessoais;  
-Descrição sucinta:  
    Cadastro de usuários para utilização do sistema e o portunidade de desfrutar dos recursos oferecidos pelo sistema;  
-Pré-condição:  
    O ator não pode ter conta cadastrada no sistema.  
-Fluxo principal:  
    1- O ator precisa acessar a tela inicial do sistema selecionar opção “Login”;  
	2- O sistema apresentará a tela de EMAIL e SENHA, abaixo será apresentada a opção de “Cadastrar”, o ator deve selecionar essa opção;  
	3- O sistema apresentará a tela de cadastro com as seguintes seções:  
		Nome completo;  
		Email;  
		Senha;  
	4- O ator deve preencher os campos e confirmar o cadastro clicando no botão “Enviar”;  
	5- O sistema envia os dados para o banco de dados para serem acessados posteriormente, após o ator é direcionado para a página de “Login” novamente para efetuar o mesmo;  
	6- O ator deve preencher os campos (email e senha) com os dados colocados na hora do cadastro e confirmar;  
	7- O sistema vai ser direcionado para a página inicial do sistema onde ele poderá utilizar os mecanismos que o sistema oferece;  
-Campos do formulário:  
Campo | Obrigatório? | Editável? | Formato   
:--- |:--- |:--- |:---    
Nome completo |Sim |Sim |Texto    
Email |Sim |Sim |Alfanumérico    
Senha |Sim |Sim |Alfanumérico    

-Opções do ator:  
Opção | Descrição | Atalho    
:--- |:--- |:---    
Enviar |Envia os dados informados no formulário |   

-Relatório do ator:  
Campo | Descrição | Formato    
:--- |:--- |:---    
 | |    

-Fluxos alternativos:  
    FA01 - Ator já possui uma conta  
        1- O sistema vai exibir um aviso informando ao ator que o cadastro não pode ser efetuado;  
        2- O ator é redirecionado para a página de "Login";  
    FA02 - Ator informa dados inválidos  
        1- O sistema exibe um aviso que o cadastro não pode ser efetuado pois algum dado informado é inválido;  
        2- O ator é redirecionado para a página de cadastro novamente, porém neste estágio o sistema estará informando qual dado está inválido;  
        3- Após a correção dos dados o ator deve confirmar novamente a efetuação do cadastro;  
    


#### RQ02 - Efetuar login

-Atores:  
    Usuário - Confirma os dados informados na hora do cadastro;  
-Decrição sucinta:  
    Confirmação dos dados e direcionamento para conta apropriada para que os atores possam utilizar o sistema e possibilita a portunidade de desfrutar dos recursos oferecidos pelo sistema;  
-Pré-condição:  
    O ator precisa ter uma conta cadastrada no sistema;  
-Fluxo principal:  
    1- O ator precisa acessar a tela inicial do sistema selecionar opção “Login”;  
	2- O sistema apresentará a tela de EMAIL e SENHA, o ator deve então informar o email e a senha informados na hora do cadastro;  
    3- O ator deve confirmar a efetuação do login clicando no botão de "Enviar";  
    4- O ator será redirecionado para página inicial do sistema;  
-Campos do formulário:  
Campo | Obrigatório? | Editável? | Formato   
:--- |:--- |:--- |:---   
Email |Sim |Sim |Alfanumérico   
Senha |Sim |Sim |Alfanumérico    

-Opções do ator:  
Opção | Descrição | Atalho    
:--- |:--- |:---   
Enviar |Confimar os dados informados para efetuação do login |   

-Relatório do ator:  
Campo | Descrição | Formato   
:--- |:--- |:---    
 | |    

-Fluxos alternativos:  
    FA01 - O ator não possui conta  
        1- O sistema apresentará um aviso informando que o login não pode ser efetuado pois não existe uma conta cadastrada;  
        2- O ator será direcionado novamente para página de "Login", porém dessa vez vazia;  
        3- O ator deverá percorrer a página até o final onde se encontrará um link para a página de cadatro sinalizado como "Cadastre-se aqui";  
        4- Após o ator clicar no link ele será redirecionado para página de cadastro onde ele poderá efetuar um cadastro;  
    FA02 - O ator esqueceu a senha  
        1- O ator deve informar que esqueceu a senha clicando no link de direcionamento para página de recuperação de conta;  
        2- O ator será redirecinado para página de recuperação de conta onde ele deverá unformar um email de confiança para receber um código de segurança;  
        3- Após o código ser enviado o ator deverá iforma-lo para o sistema que fará a verificação do código e redirecionará o ator para página de "Criação de senha", onde ele deverá informar uma nova senha preenchendo o campo "Senha" e confirmar;  

## User story
#### RQ01
-Eu como ator, gostaria de criar uma conta com os meus dados pessoais (nome, email) e uma senha, para obter acesso aos recursos oferecidos pelo sistema.  

#### RQ02
-Eu como ator, gostaria de efetuar o login na minha conta que já possui os meus dados e senha, para obter acesso a minha pagina pessoal onde já desfruto dos recursos oferecidos pelo sistema.  

## Protótipos

#### RQ01
![Efetuar cadastro](/img/Efetuar%20cadastro.PNG)  

#### RQ02
![Efetuar login](/img/Efetuar%20login.PNG)  



