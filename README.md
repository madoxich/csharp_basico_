# csharp_basico_
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Helloworld
{
    internal class Program
    {
        static void Main(string[] args)
        {

            //1.TIPOS DE VARIÁVEIS:
            // int: tipo inteira (números inteiros) - 20 ou + 20;
            // float: tipo flutuante (números decimais) 1.2, 103.5;
            // bool: tipo lógico (verdadeiro ou falso);
            // string: tipo texto (palavras ou letras);
            // char: caractere (aspas simples) 'a', 'b', um único caractere.

            //2.REGRAS PARA VARIÁVEIS:
            //começar com letra;
            //não utilizar caracter especial (@#$ etc);
            //utilizar letras de a a z;
            //utilizar números de 0a 9;
            //não utilizar nomes reservados pelo c#;
            //pode utilizar _.

            /*int segundaGuerraMundial = 1942;
            string cor_favorita = "Azul";
            float velocidadeF1 = 294.48f;
            bool segundaGuerraMundialAconteceu = true;

            Console.WriteLine(segundaGuerraMundial);
            Console.WriteLine(cor_favorita);
            Console.WriteLine(velocidadeF1);
            Console.WriteLine(segundaGuerraMundialAconteceu);

            //3.ALTERAR O VALOR DE UMA VARIÁVEL: escrever apenas o nome da variável.
            velocidadeF1 = 300.80f;
            cor_favorita = "AZUL";

            Console.WriteLine(velocidadeF1);
            Console.WriteLine(cor_favorita);

            Console.ReadLine();*/

            //4.OUTRA FORMA DE DECLARAR VARIÁVEIS: utilizando "var"
            /*var corFavorita = "azul";
            var velocidadeF1 = 300.10;
            Console.WriteLine(corFavorita);
            Console.WriteLine(velocidadeF1);
            Console.ReadLine();*/

            //4.VARIÁVEIS DO TIPO DINÂNICO: "dynamic" (pode alterar o tipo)
            /*dynamic cor_favorita = "azul";
            Console.WriteLine(cor_favorita);
            cor_favorita = 100;
            Console.WriteLine(cor_favorita);*/

            /*Console.Write("Olá, mundo!\n"); //\n é utilizado para pular linha
           // Console.WriteLine("Código em desenvolvimento"); //writeline é utilizado para escrever e pular linha (o código fica mais limpo)
           // Console.Write("desenvolvendo um código");*/

            //6.CONSTANTES
            /* constantes são valores que não podem ser alterados ao longo do desenvolvimento
               de um software/programa. Para declarar uma constante utilizar "const" e em 
            seguida o tipo da constante (float, int, char, bool, string).
            EXEMPLO: fórmula para conversão de temperatura Celsius para Kelvin

            const float = 273.15 (273,15 é um valor constante do tipo float "decimal").*/

            //7.CAPTURAR ALGO QUE O USUÁRIO DIGITOU:
            /*para isto é preciso escrever as seguintes linhas de código
            string nome = "";
            Console.WriteLine("por favor escreva seu nome e em seguida aperte a tecla Enter:");
            nome = Console.ReadLine(); 
            Console.WriteLine("Seu nome é: ");
            Console.WriteLine(nome);*/

            // 8.OPERADORES ARITMÉTICOS

            /* Os operadores matemáticos/aritméticos são os sinais
             + adição;
            - subtração;
            * vezes/multiplicação;
            / divisão.
            Para efetuar operações matemáticas basta declarar o tipo de variável no início,
            int para números inteiros (1, 2, 10, 30, 100, 40000 etc) ou float para números
            decimais (20.1, 1.3, 0.4, 0.0403241, 10000.001, etc). Obs.: algo que esqueci de 
            mencionar é que durante o desenvolvimento do seu programa sempre utilize o
            "." ponto e não a "," vírgula para representar valores/resultados/números com 
            casas decimais. isto ocorre porque a linguagem de programação utilizada usa o
            idioma inglês como lingua nativa e no sistema inglês/norte americano utiliza-se
            o ponto para representar valores fracionários/decimais e a vírgula para unidades
            de milhar ao contrário do padrão brasileiro.
            EXEMPLOS: sietema americano 10,000 dez mil
            0.1 zero ponto um (zero vírgula um no Brasil).
            Porém o resultado exibido será o valor convertido para o sistema nacional, porque
            durante o processo de complilação entende-se a região onde você está desenvolvendo
            seu programa, ou seja, se o seu computador está no Brasil, na África, na China ou no Canadá por exemplo.

            Operações matemáticas:
            int opAdd = 10 + 10;
            int opSub = 10 - 10;
            int opMul = 10 * 10;
            int opDiv = 10 / 10;
            int opDiv2 = 10 / 11;
            float opDiv3 = 10f / 11;
            float opDiv4 = 10 / 11f;

            Console.WriteLine(opAdd);
            Console.WriteLine(opSub);
            Console.WriteLine(opMul);
            Console.WriteLine(opDiv);
            Console.WriteLine(opDiv2);
            Console.WriteLine(opDiv3);
            Console.WriteLine(opDiv4);*/

            /* Percebam que para as operações "int opDiv, 2, 3 e 4" linhas 107 a 110 eu extrapolei
             as possibilidades, para poder demonstrar os resultados que podem surgir. Na primeira
            operação para divisão estamos dividindo dez por dez e isto resulta em 1, um número inteiro,
            notem que no início da variável eu a declarei como inteira "int" e ao efetuar divisões que
            resultam em números inteiros isto não será um problema 4/2, 10/2, 10/10 etc. Porém ao efetuarmos
            calculos que exigem uma precisão maior teremos resultados incertos, por exemplo 10/11 = 0 na
            linha 108, uma vez que, 10/11 resulta aproximadamente 0,90. O rsultado 0 obtido neste caso é
            devido ao modo como declaramos a variável, ao declarar variável do tipo int e efetuar operações
            que resultam em valores do tipo float (decimal) ao arredondar o número a ferramenta a qual 
            estamos utilizando (c#) ignora todos os demais valores depois da vírgula (à direita da vírgula)
            por exemplo os dígitos 9090909.
            Para solucionar e evitar este imprevisto e proporcionar resultados mais exatos utilizamos variá-
            veis do tipo float para divisão e escrevemos a letra "f" em um dos valores envolvidos na operação.*/

            //9. CONDIÇÕES

            /*As condições são represantadas por sinais como:
             > maior que;
            < menor que;
            >= maior ou igual;
            <= menor ou igual;
            == igual;
            != diferente.
            Estes símbolos representam uma verificação e resultam em um valor lógico,
            podendo ser verdadeiro ou falso. É importante durante este aprendizado utilizar
            os modelos a partir do fluxograma, pois estes ajudam a entender como estas condições atuam.
            Exemplos: 1<2 verdadeiro;
            10<2 falso e assim por diante.*/

            //10.ESTRUTURAS CONDICIONAIS
            /* As estruturas condicionais são utilizadas para verificar se uma linha de comandos
             é verdadeira.
            Utilizamos as seguintes estruturas condicionais:
            if (se);
            else (senão);
            else if (senão se); 
            para o comando Console.WriteLine() utilizar o bloco {}
            Exemplos:
           
            if (10 <= 0) 
            {
                Console.WriteLine("Verdadeiro, dez é maior que zero."); 
            }

            if (10 < 2)
            {
                Console.WriteLine("verdadeiro, dois é menor que dez.");
            }

            else if é colocado antes de else

            else if (2 == 1)
            {
                Console.WriteLine("else if acionado, 2 é igual a 2");
            }
            else if (5 != 5)
            { 
                Console.WriteLine("else if acionado, 5 é diferente de 9");
            }

            //o else é utilizado quando o if resulta em um valor falso.
            else
            {
                Console.WriteLine("Falso, dez não é menor que dois");
            }*/

            /* nós também podemos declarar variáveis antes destas estruturas que ajudam
            a facilitar durante a codificação
            exemplo
            int a = 10;
            int b = 20;
            int c = 30;
            float d = 12.48f;

            if (a == d)
            {
                Console.WriteLine("verdadeiro");
            }
            else
            {
                Console.WriteLine("a variável d é um número decimal = 12,48");
            }*/

            //11.OPERADORES CONDICIONAIS "E" E "OU"

            /* Os operadores condicionais "e" e "ou" são utilizados para impor mais de uma
              condição para que uma nova ação seja encadeada. Antes de ver isto em prática
            vamos analisar quais as possibilidades temos ao utilizar estes operadores condicionais:
            o operador e é representado por &&;
            o operador ou é representado por ||.
            POSSIBILIDADES:
            E
            v e v = v
            v e f = f
            f e v = f
            f e f = f
            note que para o resultado ser verdadeiro as duas condições precisam ser verdadeiras. Se para
            desenvolver um motor gráfico por exemplo você precisar de um computador e uma linguagem de
            programação, caso você não tenha um destes dois requisitos (v e v) o resultado será falso :(,
            não sendo possível o desenvolvimento de um motor gráfico. Porém se você tiver o computador
            e acesso a uma linguagem de programação o resultado será verdadeiro (v e v = v) :).
            Portanto uma das duas condições for falsa o resultado também é falso, devido ao operador
            "e", este operador exige que uma condição E outra condição sejam verdadeiras para
            um resultado verdadeiro.

            OU
            v ou v = v
            v ou f = v
            f ou v = v
            f ou f = f
            Já no operador condicional "ou" basta que uma condição seja verdadeira
            para que o resultado tembém seja verdadeiro, exemplo imagine que você precisa ir
            comprar pão e existem duas possibilidades (duas padarias) a padaria 1 e a padaria 2.
            Para que você consiga comprar seus pães existem duas possibilidades a padaria 1 OU a
            padaria 2, se em uma padaria já estiver acabado os pães você pode ir na outra. Porém
            caso não haja pão em nenhuma das duas (f ou f) o resultado será falso e você não conseguirá 
            comprar pão.*/

            /*int a = 10;
            int b = 20;
            int c = 30;
            float d = 10.02f;

            if (a < b && c > d)
            {
                Console.WriteLine("verdadeiro");
            }
            else
            {
                Console.WriteLine("falso");
            }*/


            /*int a = 10;
            int b = 20;
            int c = 30;
            float d = 10.02f;

            if (a < b || c == d)
            
            //a é menor que b (10 < 20) verdadeiro
            //mas c não é igal a d (c = 30) (d = 10,02),
            //porém como utilizamos o operador || (ou) o resultado é verdadeiro
           
            {
                Console.WriteLine("verdadeiro");
            }
            else
            {
                Console.WriteLine("falso");
            }*/



            Console.ReadLine();
        }
    }
}
 
