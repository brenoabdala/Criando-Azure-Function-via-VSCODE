### Criando Azure Function via VSCODE

<p> O passo a passo a seguir, ilustra a maneira de criar Azure Function, via VSCODE permitindo assim mais facilidade de desenvolver códigos. 
No exemplo a seguir, usarei a linguagem python para exemplificar, atente-se de já ter uma conta no portal do Azure (portal.azure.com)</p>


#### Instalações necessárias 
 -  VSCODE (https://code.visualstudio.com/)
 -  Azure CLI (https://learn.microsoft.com/pt-br/cli/azure/install-azure-cli-windows?tabs=azure-cli)
 -  Python (https://www.python.org/downloads/)

#### Configurações dentro do VSCODE

<p> Será necessário realizar a instalação das extensões: </p>

<strong> Azure Tools </strong>
 > ![Azure Tools](https://github.com/user-attachments/assets/451a5b86-a173-48fc-8b1e-3656b950f9e3)

 <strong> Python </strong>
 > ![imagem1](https://github.com/user-attachments/assets/5d5269aa-1029-477a-90f7-965f0ed40aa8)

 
 <strong>  Login Azure </strong>  
 - Clique no botão da azure no menu lateral (conforme print a baixo) e seleciona a opção "sign to azure";
 - Realize o login no portal da azure com suas credenciais e em seguida pode a aba.
 
 #### Processo de criação da function
 
 - Expadir o a subscription;
 - Function App -> Clica com o botão direito e seleciona opção "Create Function App in Azure ...(Advanced);
 - Atribua um nome global para função;
 - Selecione a opção Consumption;
 - Selecione a região;
 - Selecione a linguagem desejada (Java, .Net, PowerShell ou Python), no caso do exemplo clique em python.
 - Selecione o Resource Group; 
 - Selecione a storage account ou crie um novo;
 - Crie um application Insights resouce (um para cada função);
 
 <p> Criado a fucntion global no portal, agora é necessário criar a função local com o código, ou seja o processo que será execcutado.</p>
 
 - Na aba lateral esquerda selecione o icone da Azure; 
 - Acesse Workspace e clique no icone da function e selecione "Create Function";
 - Selecione a pasta;
 - Selecione a linguagem (Python);
 - Selecione o Model, no exemplo proposto selecione a opção "Model 1";
 - Selecione "skip virtual environment";
 - Selecione "Timer Trigger"; 
 - Atribua um nome para esse processo dentro da função;
 - Atribua o cron;
 

 <p> Após a criação selecione a função global criada inicialmente e com o botão direito clique em "deploy". </p>
