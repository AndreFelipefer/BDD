
# Banco De Dados (AC1)


## Lista Exercicios Diagrama 
### 1.1 -  PetShop 
![PetShop](https://github.com/AndreFelipefer/BDD/assets/129207232/11dc9f76-2adc-458c-8239-89d9ee9936bf)
[Pet_Shop.txt](https://github.com/AndreFelipefer/BDD/files/12529155/Pet_Shop.txt)


### 1.2 -  Games
![Games](https://github.com/AndreFelipefer/BDD/assets/129207232/3ab2761b-c6d1-4985-a33f-cfc67a938ac3)
[GAMES.txt](https://github.com/AndreFelipefer/BDD/files/12529169/GAMES.txt)

### 1.3 - Biblioteca 
![Biblioteca](https://github.com/AndreFelipefer/BDD/assets/129207232/81b39658-7aa0-41f2-8213-9acb32d9bb1a)
[Biblioteca.txt](https://github.com/AndreFelipefer/BDD/files/12529050/Biblioteca.txt)

### 1.4 - Locadora
![Locadora](https://github.com/AndreFelipefer/BDD/assets/129207232/d3a1ad69-4179-47c9-811e-28a03bb5d2d7)
[Locadora.txt](https://github.com/AndreFelipefer/BDD/files/12529177/Locadora.txt)

### 1.5 - Supermercado
![Supermercado](https://github.com/AndreFelipefer/BDD/assets/129207232/c2936536-4443-4048-9989-c8eba4736c21)
[Supermercado.txt](https://github.com/AndreFelipefer/BDD/files/12581254/Supermercado.txt)

### 1.6 - Videoteca
![VideoTeca](https://github.com/AndreFelipefer/BDD/assets/129207232/89f7dfce-432f-473e-9bb4-46476745b542)
[Videoteca.txt](https://github.com/AndreFelipefer/BDD/files/12529054/Videoteca.txt)

## Conforme Diagramas elaborados das seguintes questões apresentadas no exercicio, segue criação de Tabelas via SQLITEONLINE:

### 2.0 - Banco de Dados Aluno 
[Aluno.txt](https://github.com/AndreFelipefer/BDD/files/12529149/Aluno.txt)

	CREATE TABLE TAB_ALUNO_a (
	
	  ID VARCHAR2(4000),
	  
	  RA VARCHAR2(200),
	  
	  NOME VARCHAR2(200),
	  
	  Data_Nascimento DATE(8),
	  
	  Endereco_Email VARCHAR2(4000)
	  );
	  
	  CREATE TABLE TAB_Aluno_b
	  
	  (
	  
	   ID VARCHAR(4000)
	   
	   );
	   
	   INSERT INTO TAB_Aluno_a(ID, RA, NOME, Data_Nascimento, Endereco_Email) 
	   VALUES('1', '236059', 'Andre', 1996-06-10, 'Andre_Felipefer@hotmail.com');
	   
	   INSERT INTO TAB_Aluno_a(ID, RA, NOME, Data_Nascimento, Endereco_Email) 
	   VALUES('1', '236058', 'Juliana', 1994-05-12, 'Andre_Felipefer@hotmail.com');
	   
	   INSERT INTO TAB_Aluno_a(ID, RA, NOME, Data_Nascimento, Endereco_Email) 
	   VALUES('1', '236057', 'William', 1997-03-20, 'Andre_Felipefer@hotmail.com');
	   
	   INSERT INTO TAB_Aluno_a(ID, RA, NOME, Data_Nascimento, Endereco_Email) 
	   VALUES('1', '236056', 'Yasmin', 1998-07-11, 'Andre_Felipefer@hotmail.com');



### 2.1 - Banco de Dados Colaboradores
[Colaborador.txt](https://github.com/AndreFelipefer/BDD/files/12529151/Colaborador.txt)


	CREATE TABLE TAB_colaborador_a
	
	(
	  ID VARCHAR2(4000),
	  
	  CODIGO VARCHAR2(4000),
	  
	  NOME VARCHAR2(4000),
	  
	  CPF VARCHAR2(4000),
	  
	  CARGO VARCHAR2(4000),
	  
	  SALARIO DECIMAL(4000)
	);
	  CREATE TABLE TAB_colaborador_b
	  (
	    ID VARCHAR2(4000)
	  );
	  INSERT INTO TAB_colaborador_a(ID, CODIGO, NOME, CPF, CARGO, SALARIO) 
	  VALUES ('1', 236059,'Andre', '46401141848', 'Assistente de TI', 1.900,00 );
	  
	  INSERT INTO TAB_colaborador_a(ID, CODIGO, NOME, CPF, CARGO, SALARIO) 
	  ALUES ('1', 236059,'Juliana', '46401141847', 'Assistente de TI', 1.900,00 );  
	  
	  INSERT INTO TAB_colaborador_a(ID, CODIGO, NOME, CPF, CARGO, SALARIO) 
	  VALUES ('1', 236059,'Yasmin', '46401141846', 'Assistente de TI', 1.900,00 ); 
	  
	  INSERT INTO TAB_colaborador_a(ID, CODIGO, NOME, CPF, CARGO, SALARIO) 
	  VALUES ('1', 236059,'Teruo', '46401141845', 'Assistente de TI', 1.900,00 );  
	  
	  INSERT INTO TAB_colaborador_a(ID, CODIGO, NOME, CPF, CARGO, SALARIO) 
	  VALUES ('1', 236059,'William', '46401141844', 'Assistente de TI', 1.900,00 );  



