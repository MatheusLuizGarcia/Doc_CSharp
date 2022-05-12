# Documentação C# (Csharp)
## Noções básicas:
---
C# é uma linguagem de programação de alto nível, por meio dela é possível escrever códigos de várias complexidades.

Utilizando uma combinação de dados, equações e funções é possível escrever um programa em C#, para isso precisamos aprender como funciona a inserção de dados no console:

```Console.WriteLine("<insira_sua_informação_aqui>");``` ->escreve no console uma informação para o usuário, no caso de inserir números ou variáveis não se utiliza ("")

```Console.Write("<insira_sua_informação_aqui>");``` -> o mesmo que o anterior, mas o prompt de escrita continua na mesma linha

```Console.ReadLine("<digite_sua_informação_aqui>");``` ->espera o usuário inserir uma informação pelo console

---
### 1 - tipos de dados simples:

````string```` ->conjunto de caracteres a serem armazenados em uma variável string (linha)

EXEMPLO:
````bash
string frase = "<digite_sua_frase>";
````

````int```` ->numero inteiro a ser armazenado em uma váriavel int (integral, interger)

EXEMPLO:
````bash
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
````bash
bool true = true;
ou
bool false = false;
````

````char```` ->caractere a ser armazenado em uma variável

EXEMPLO:
````bash
char caractere = 'a'; #nota que se usa ' (apostrofo) no lugar de "(aspas) para caracteres
````
---
### 2 - equações:

**a) que interagem com strings**

```bash
string frase = "frase";
Console.WriteLine(frase.Lenght);
```
escreve quantos caracteres a string possui

```bash
string frase = "frase";
Console.WriteLine(frase.ToUpper());
```
converte todos os caracteres da string para maiúsculo, o mesmo pode ser feito para minúsculo com o método ```frase.ToLower```

```bash
string frase = "frase";
Console.WriteLine(frase.Contains("<insira_uma_informação"));
```
retorna um valor de verdadeiro se a string contém a informação ou falso se não contém

```bash
string frase = "frase";
Console.WriteLine(frase[<numero_inteiro>]);
```
retorna um único caractere com o index do número inserido, a partir do do número 0

```bash
string frase = "frase";
Console.WriteLine(frase.IndexOf("<insira_sua_palavra>"));
```
verifica se a palavra está contida na string e diz em que posição está indexada

**b) que interagem com números**

````<arg3> = <arg1> + <arg2>;```` -> soma o argumento 1 com o argumento 2 resultando no argumento 3

```<arg3> = <arg1> - <arg2>;``` ->subtrai o argumento 2 do argumento 1 resultando o argumento 3

```<arg3> = <arg1> * <arg2>;``` ->multiplica o argumento 1 pelo o argumento 2 resultando no argumento 3

```<arg3> = <arg1> / <arg2>;``` ->divide o argumento 1 pelo argumento 2 diferente de zero resultando no argumento 3
