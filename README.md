
# Banco De Dados (AC1)


## Lista Exercicios Diagrama / Tabelas SQL
### 1.1 -  PetShop 
![PetShop](https://github.com/AndreFelipefer/BDD/assets/129207232/e5d845fd-c2a0-4fa2-9beb-fed4ab0dabf5)

Tabela SQL: 
[Pet_Shop.txt](https://github.com/AndreFelipefer/BDD/files/12529155/Pet_Shop.txt)


### 1.2 -  Games
![Games](https://github.com/AndreFelipefer/BDD/assets/129207232/56229c19-f661-4da1-92e2-b92d67bfdeda)

Tabela SQL: 
[GAMES.txt](https://github.com/AndreFelipefer/BDD/files/12529169/GAMES.txt)

### 1.3 - Biblioteca 
![Biblioteca](https://github.com/AndreFelipefer/BDD/assets/129207232/76a7bd89-c4ba-452f-aa70-707e291cd300)

Tabela SQL: 
[Biblioteca.txt](https://github.com/AndreFelipefer/BDD/files/12529050/Biblioteca.txt)

### 1.4 - Locadora
![Locadora](https://github.com/AndreFelipefer/BDD/assets/129207232/7cf81f96-f404-4c72-bc3d-707f5ced7218)

Tabela SQL: 
[Locadora.txt](https://github.com/AndreFelipefer/BDD/files/12529177/Locadora.txt)

### 1.5 - Supermercado
![Supermercado](https://github.com/AndreFelipefer/BDD/assets/129207232/c92043c3-c1e9-4166-8838-8d3e16fbff37)

Tabela SQL: 
[Supermercado.txt](https://github.com/AndreFelipefer/BDD/files/12581254/Supermercado.txt)

### 1.6 - Videoteca
![Videoteca](https://github.com/AndreFelipefer/BDD/assets/129207232/363ed03c-da5f-4255-ade1-d716aa07ad2d)

Tabela SQL: 
[Videoteca.txt](https://github.com/AndreFelipefer/BDD/files/12529054/Videoteca.txt)

## Tabelas Exercicio Etapa 03

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
	  
	  SALARIO DECIMAL(10,2)
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

   ### Obrigado!!



