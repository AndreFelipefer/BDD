
# Banco De Dados (AC1)


## Lista Exercicios Diagrama 
### 1.1 -  PetShop 
![PetShop](https://github.com/AndreFelipefer/BDD/assets/129207232/11dc9f76-2adc-458c-8239-89d9ee9936bf)

### 1.2 -  Games
![Games](https://github.com/AndreFelipefer/BDD/assets/129207232/3ab2761b-c6d1-4985-a33f-cfc67a938ac3)

### 1.3 - Biblioteca 
![Biblioteca](https://github.com/AndreFelipefer/BDD/assets/129207232/81b39658-7aa0-41f2-8213-9acb32d9bb1a)

### 1.4 - Locadora
![Locadora](https://github.com/AndreFelipefer/BDD/assets/129207232/d3a1ad69-4179-47c9-811e-28a03bb5d2d7)

### 1.5 - Supermercado
![Supermercado](https://github.com/AndreFelipefer/BDD/assets/129207232/c2936536-4443-4048-9989-c8eba4736c21)

### 1.6 - Videoteca
![VideoTeca](https://github.com/AndreFelipefer/BDD/assets/129207232/89f7dfce-432f-473e-9bb4-46476745b542)

## Conforme Diagramas elaborados das seguintes questões apresentadas no exercicio, segue criação de Tabelas via SQLITEONLINE:

### 2.0 - Banco de Dados Aluno 
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



### 1.1.0 -  Banco de Dados PetShop 

CREATE TABLE TAB_PET_SHOP
(
  ID VARCHAR2(4000),
  
  NOME_CLIENTE VARCHAR2(4000),
  
  CPF VARCHAR2(4000),
  
  EMAIL VARCHAR(4000),
  
  TELEFONE VARCHAR(4000),
  
  NOME_PET VARCHAR(4000),
  
  ESPECIE VARCHAR(4000),
  
  DATA_NASCIMENTO_PET DATA(4000)
  );
  
  CREATE TABLE TAB_PET_SHOP_A
  (
    ID VARCHAR2(4000)
  );
  
  INSERT INTO TAB_PET_SHOP (ID, NOME_CLIENTE, CPF, EMAIL, TELEFONE, NOME_PET, ESPECIE, DATA_NASCIMENTO_PET) 
  VALUES ('1', 'André Felipe', 46401755822, 'Andre_felipefer@hotmail.com', '1599834-4442', 'THOR', 'SHI-TZU', 2020);

        

### 1.2.0 -  Banco de Dados Games 

CREATE TABLE TAB_DESENVOLVEDORES(

  ID INT,
  
  NOME_COLABORADOR VARCHAR2(200),
  
  CPF VARCHAR2(200),
  
  DATA_NASCIMENTO DATE
);

CREATE TABLE TAB_PROJETOS(

	ID INT,
 
  	NOME_PROJETO VARCHAR2(200),
   
  	DATA_LANCAMENTO DATE,
   
  	GENERO VARCHAR2(200),
   
  	FAIXA_ETARIA VARCHAR2(100)
   
 );
 
 INSERT INTO TAB_DESENVOLVEDORES (ID, NOME_COLABORADOR, CPF, DATA_NASCIMENTO)
 VALUES (1,'André Felipe', '46401755800', '1996-06-10');
 
 insert into TAB_PROJETOS (ID, NOME_PROJETO, DATA_LANCAMENTO, GENERO, FAIXA_ETARIA) 
 VALUES (2, 'UPX', '2023-09-04', 'TERROR', '18');

);

### 1.3.0 - Banco de Dados Biblioteca 

CREATE TABLE TAB_LIVRO(

ID INT,

TITULO VARCHAR2(100),

QTD_PAGINAS INT,

ACABAMENTO VARCHAR (4000),

EDITORA VARCHAR(200)

);

CREATE TABLE TAB_AUTOR(

ID INT,  

NOME VARCHAR2(200),

NACIONALIDADE VARCHAR2(200),

DATA_NASCIMENTO DATE,

EMAIL VARCHAR2(200)
);

INSERT INTO TAB_LIVRO (ID, TITULO, QTD_PAGINAS, ACABAMENTO, EDITORA) 
VALUES ('10', 'BANCO DE DADOS', 200, 'CAPA DURA', 'FACENS');

INSERT INTO TAB_AUTOR (ID, NOME, NACIONALIDADE, DATA_NASCIMENTO, EMAIL) 
VALUES ('11', 'ANDRÉ FELIPE', 'BRASILEIRO', 2000-01-01, 'ANDRE@HOTMAIL.COM');

### 1.4.0 - Banco de Dados Locadora

 CREATE TABLE TAB_AUTOMOVEL(
 
ID INT,

  MODELO VARCHAR2(200),
  
  ANO INT,
  
  PLACA VARCHAR2(200),
  
  LOGOTIPO VARCHAR2(200),
  
  NOME_MONTADORA VARCHAR2(200),
  
  SITE_MARCA VARCHAR2(200)
);

INSERT INTO TAB_AUTOMOVEL (ID, MODELO, ANO, PLACA, LOGOTIPO, NOME_MONTADORA, SITE_MARCA) 
VALUES ('1400', 'FOX', 2013, 'YYYKK', 'WV', 'WOLKSVAGEM', 'WV.COM.BR');

### 1.5.0 - Banco de Dados Supermercado

CREATE TABLE TAB_PRODUTO (

  ID INT,
  
  SAC VARCHAR2(2000),
  
  MARCA VARCHAR2(2000),
  
  PRECO DECIMAL,
  
  NOME_PRODUTO VARCHAR2(2000),
  
  NACIONALIDADE_PRODUTO VARCHAR2(2000),
  
  QTD_ESTOQUE INT
);


INSERT INTO TAB_PRODUTO (ID, SAC, MARCA, PRECO, NOME_PRODUTO, NACIONALIDADE_PRODUTO, QTD_ESTOQUE)
VALUES (78911063, '0800-7070', 'KINOR', 7.99, 'CALDO DE GALINHA', 'MADE IN BRAZIL', 15);ercado.txt…]()


### 1.6.0 - Banco de Dados Videoteca

CREATE TABLE TAB_FILME(

  ID INT,
  
  TITULO VARCHAR(200),
  
  DURACAO TIME,
  
  PRECO DECIMAL,
  
  IDIOMA VARCHAR(200)
  
);

CREATE TABLE TAB_ELENCO(

  ID INT,
  
  NOME_ATORES VARCHAR(200),
  
  DATA_NASCIMENTO DATE,
  
  NACIONALIDADE VARCHAR(200)
);

INSERT INTO TAB_FILME (ID, TITULO, DURACAO, PRECO, IDIOMA)
VALUES (1404, 'Facens', '01:50:00', 20.00, 'PORTUGUES');

INSERT INTO TAB_ELENCO (ID, NOME_ATORES, DATA_NASCIMENTO, NACIONALIDADE) 
VALUES (1405, 'FELIPE', '1996-06-10', 'BRASILEIRO');

# ARQUIVOS TXT:
[Supermercado.txt](https://github.com/AndreFelipefer/BDD/files/12529180/Supermercado.txt)
[GAMES.txt](https://github.com/AndreFelipefer/BDD/files/12529169/GAMES.txt)
[Colaborador.txt](https://github.com/AndreFelipefer/BDD/files/12529151/Colaborador.txt)
[Aluno.txt](https://github.com/AndreFelipefer/BDD/files/12529149/Aluno.txt)
[Pet_Shop.txt](https://github.com/AndreFelipefer/BDD/files/12529155/Pet_Shop.txt)
[Biblioteca.txt](https://github.com/AndreFelipefer/BDD/files/12529050/Biblioteca.txt)
[Locadora.txt](https://github.com/AndreFelipefer/BDD/files/12529177/Locadora.txt)
[Videoteca.txt](https://github.com/AndreFelipefer/BDD/files/12529054/Videoteca.txt)
