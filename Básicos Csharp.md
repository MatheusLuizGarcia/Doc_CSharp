# Documentação C# (Csharp)

## Noções básicas:

### 1- tipos de dados simples:

````string```` ->conjunto de caracteres a serem armazenados em uma variável string (linha)

EXEMPLO:
````
string frase = "<digite_sua_frase>";
````

````int```` ->numero inteiro a ser armazenado em uma váriavel int (integral, interger)

EXEMPLO:
````
int num = 3;
````

```float, double, decimal ```->numero real a ser armazenado em uma variável, sua precisão varia dependendo do tipo utilizado sendo ````float```` o menos preciso e ````decimal```` o mais preciso

EXEMPLO:
````
float num1 = 3.0;
double num2 = 2.5;
decimal num3 = 6.21;
````

````bool```` ->cria uma lógica de verdadeiro ou falso para checar uma variável

EXEMPLO:
````
bool true = true;
ou
bool false = false;
````

````char```` ->caractere a ser armazenado em uma variável

EXEMPLO:
````
char caractere = 'a';
````

### 2- equações

#### a) que inserem código

```Console.WriteLine("<insira_sua_informação_aqui>");``` ->escreve no console a informação, no caso de inserir números ou variáveis não se utiliza ("")

```Console.ReadLine("<digite_sua_informação_aqui>");``` ->espera o usuário inserir uma informação pelo console

#### b) que interagem com strings

```
string frase = "frase"
Console.WriteLine(frase.Lenght);
```
escreve quantos caracteres a string possui

```
string frase = "frase"
Console.WriteLine(frase.ToUpper());
```
converte todos os caracteres da string para maiúsculo, o mesmo pode ser feito para minúsculo com o método ```frase.ToLower```

```
string frase = "frase"
Console.WriteLine(frase.Contains("<insira_uma_informação"));
```
retorna um valor de verdadeiro se a string contém a informação ou falso se não contém

```
string frase = "frase"
Console.WriteLine(frase[<numero_inteiro>]);
```
retorna um único caractere com o index do número inserido, a partir do do número 0

```
string frase = "frase"
Console.WriteLine(frase.IndexOf("<insira_sua_palavra>"));
```
verifica se a palavra está contida na string e diz em que posição está indexada

#### c) que interagem com números

````<arg3> = <arg1> + <arg2>;```` -> soma o argumento 1 com o argumento 2 resultando no argumento 3

```<arg3> = <arg1> - <arg2>;``` ->subtrai o argumento 2 do argumento 1 resultando o argumento 3

```<arg3> = <arg1> * <arg2>;``` ->multiplica o argumento 1 pelo o argumento 2 resultando no argumento 3

```<arg3> = <arg1> / <arg2>;``` ->divide o argumento 1 pelo argumento 2 diferente de zero resultando no argumento 3
