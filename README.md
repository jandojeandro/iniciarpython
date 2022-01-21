# iniciarpython
 Instruções inicias uso Python

print é escreva
= é receber
input é mostrar
int(input()) é fazer conta com números inteiros
int 7 -4 0 9875
float 4.5 75.69 48855.0
from(XXX(import(x,y))) importa a biblioteca XXX as funções x e y
str são caracteres que não são números, sempre entre ' '
bool entende número verdadeiro e falso
+ soma
- subtrai
* multiplica (pode multiplicar as informações A*20 resulta AAAAAAAAAAAAAAAAAAAA
/ divide -> para mostras apenas 3 casas após vírgula {:.3f}
** potência (pode ser usado pow(5,2) cinco ao quadrado) e raiz 81**(1/3) raiz cúbica de 81
// divisão inteira (valor dividido inteiro sem vírgula)
% resto da divisão (valor inteiro que sobraria da divisão, após a vírgula)
== igual
< alinhamento esquerda > direita ^ central
Ordem execução -> entre (), **, *././/.%, +.-
\n quebra linha
\t tabula (= tecla Tab)
barra invertida em um string, use uma barra invertida dupla //
end=' ' puxa debaixo para mesma linha
{}'.format(a, b, ...) insere objeto dentro de uma escrita pode ser usado mais de 1 
número não colocar aspas para fazer cálculo print(7+3) será 11 print('7'+'3') será 73
, une informações com espaço
+ une informações sem espaço
toda variável é objeto
todos os comandos são funções
dados mensagens devem estar entre ('  ')

int=inteiro
float=decimal
str=caracteres
bool=V ou F (boleano) lógico
list=lista
tuple=tupla
set=conjunto
dict=dicionário
stride=passo
s=slice=fatiamento
print=escreva na tela
input=entre com informação
if=se
else=senão
elif=senão se
not=não
when=quando
while=enquanto
for=para
break=parar
continue=continuar
return=retornar
def=defina
len=conta caracteres
from=para
import=importar
math=biblioteca matemática
ceil=arredonda pra cima
floor=arredonda pra baixo
trunc=trunca elimina da vírgula pra frente
pow=potencia
sqrt=raiz quadrada
factorial=fatorial

sqrt(numero): Retorna a raiz quadrada do número.
pow(x, y): Retorna x elevado a y.
cos(numero): Retorna o cosseno do número em radiano.
sin(numero): Retorna o seno do número em radiano.
tan(numero): Retorna a tangente do número em radiano.
radians(numero): Converte o angulo ‘numero’ de graus para radiano.
pi: número pi (3.1415926535897931).
hypot(x, y): Retorna a hipotenusa dos números (catetos) fornecidos

    >>> texto = 'abacate'
    >>> len(texto)
    7
    >>> texto[0]
    'a'
    >>> texto[1:4]
    'bac'
    >>> texto[2:]
    'acate'
    >>> texto[:3]
    'aba'
    >>> texto[-1]
    'e'
    >>> texto[-2]
    't'
    >>> 
tipos string
upper(): Converte toda a string em maiúscula.
lower():Converte toda a string em minúscula.
capitalize():Converte somente a primeira posição em maiúscula.
count(s1):Conta quantas vezes aparece a string s1 dentro da string.
strip():Retira os espaços em branco do início e do final da string.
split(“i1”):Separa a string em palavras a cada i1 que encontrar.
“i1”.join([p1,p2,p3]): Faz a junção das palavras p1, p2 e p3.
startswith(“L1”):Verifica se a string começa com L1 e retorna True ou False.
endswith(“L1”): Verifica se a string finaliza com L1 e retorna True ou False.
replace(“s1”,”s2”):Substitui s1 por s2 na string.
center(x):Centraliza a string de acordo com o valor de x.
find(“s1”):Retorna a primeira posição de s1 contida na string, se não houver, retornará -1.
