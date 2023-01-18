/**
 * You can edit, run, and share this code.
 * play.kotlinlang.org
 */
//fun main() {
//println("Hello World")*/// comentário
    /*todo mundo
     * assisnou a
     * lista?
     */
    /*
     println("Qualquer coisa")
     println("Ctrl + a")
     println("crie um google docs")
     println("Ctrl + c lá dentro")
     */
     //comentário
     /*
      * co
      * men
      * tá
      * rio
      */
      //println() -- exibir coisas no console
      /*
    println("Capitão Picolô - Olá tudo bom?")
    println("Todynhu - Salve, na boa coroa")
    println("Capitão Picolô - Sim")
    println("Todynhu - ...")
    println("Clima tenso")
    println("♫ msc de faroeste ♫")
    */
    // Variáveis - guardam valores
    // 
    // var - mutável - seu valor pode ser alterado
    // val - não mútavel - seu valor não pode ser alterado
    // 
    // TIPOS DE VARIÁVEIS(principais ☻)
    // 
    // string --> tipo de variável que armazena textos no geral(caracteres) 
    // dentro de aspas
    // Boolean --> verdadeiro ou falso, sim ou não, 1 ou 0
    // Int --> números inteiros
    // Float --> números reais (com um número baixo de casas decimais)
    // Double --> números reais tmb (número alto de casas decimais)
    // Long --> números reais (número altissimo de casas decimais(número completo))
    // 
    /*
    var nome = "Messi"
    var idade = 35
    var theBest = 7
    
    //println(messi)
    
    println("O nome dele é " + nome + ", a idade dele é " + idade +
            ", e ele já foi " + theBest + " vezes o the Best")
    println("O nome dele é $nome , a idade dele é $idade , e ele já foi $theBest vezes o the Best")
    */
    //Exercício
    
    //Faça uma apresentação de si mesmo dizendo nome, idade, país e cidade através de variáveis
    
    //Faça uma apresentação de si mesmo dizendo nome, idade, país e cidade através de variáveis
//
/*
var nome = "Eduardo"
var idade = 19
var pais = "Brasil"
var cidade = "São Paulo"
    
    println("Olá eu sou $nome , tenho $idade anos, meu país é o $pais e minha cidade é $cidade")

    var num1 = 70 
    var num2 = 13 
    var resultado = num1 - num2
    
    println(resultado)
    */
    //Operadores Lógicos
    // - -> subtração
    // + -> adição
    // * -> multiplicação
    // / -> divisão
    // % -> módulo
    //println(6%2)
    //
    // = -> para dar valor a algo
    //
    //Operadores Relacionais
    // == -> igual a algo
    // != -> diferente a algo
    // > -> maior que 
    // < -> menor que
    // >= -> maior ou igual a
    // <= -> menor ou igual a
    // 
    // ++ -> adiciona 1
    // -- -> subtrai 1
    // 
    /*
    var num = 0
    num++
    println(num)
    
    
    if e else simples
    Estrutura:
    
    if(condição){
    ações
    }else{
    ação
    }
    */ 
    /*
    var dia = 26
    
    if(dia <= 21){
        println("Hoje tem aula")
    }else{
        println("Hoje não tem aula")
    }
    
    // if e else composto
    // 
    // if(condição){
    ações
    }else if(condição){
    ação
    }else if(condição){
    ação
    }else{
    ação
    }
    
    var vidas = 10
    
    if(vidas <= 0){
        println("tu ta morto")
    }else if(vidas == 1){
        println("tu ta morrendo!!")
    }else if(vidas == 2){
        println("ce não ta muito bem, se cuida ae")
    }else if(vidas == 3){
        println("tu ta ok, só come menos miojo")
    }else if(vidas == 4){
        println("ce ta de boa, vai curtir")
    }else{
        println("Tu ta ÓTIMO!!! Parabéns!")
    }*/
    

   // 1 - faça um programa usando duas variaveis que representem cada uma, um número.
    //ele(programa) deve verificar qual dos dois é o maior número e imprimi-lo no console
    //
    /*
    var numero1 = 10
    var numero2 = 10 
    
    if(numero1 > numero2){ //verificando se o n1 é maior que o n2
        println(numero1)
    }else{
        println(numero2) //verificando se o n1 não é maior que o n2
    }
    */
    //faça um programa que verifique se o valor de uma variável é 
    //maior, igual, ou menor que 0
    /*
    var numero = 0
    
    if(numero > 0){
        println("o número é maior que zero")
    }else if(numero < 0){
        println("o número é menor que zero")
    }else{
    	println("o número é igual a zero")
    }
    */
    
    
    //----------------------------------//
    //Operadores Lógicos
    // && -> e
    // || -> ou
    /*
     var coracoes = 0
    var vidas = 2
     
    if(coracoes <= 2 || vidas <= 3){
        println("game over")
    }else{
        println("jogo vai ser reiniciado")
    */
    //
    //V - verdadeiro
    //F - falso
    //
    // &&
    //VV  - Executa
    //VF  - Não executará 
    //FV  - não executará 
    //FF  - não
    //
    // ||
    //VV  - Executa
    //VF  - Executa
    //FV  - Executa
    //FF  - não executará
    
    // When - quando
    //
    /*
    var mes = 3
    
    when(mes){
        1 -> {println("Janeiro")}
        2 -> {println("Fevereiro")}
        3 -> {println("março")}
        4 -> {println("abril")}
        5 -> {println("maio")}
        6 -> {println("junho")}
        7 -> {println("julho")}
        8 -> {println("agosto")}
        9 -> {println("setembro")}
        10 -> {println("outubro")}
        11 -> {println("novembro")}
        else -> {println("dezembro")}
    }
*/
 // When - quando
    /*
    var mes = 3
    
    when(mes){
        1 -> {println("Janeiro")}
        2 -> {println("Fevereiro")}
        3 -> {println("março")}
        4 -> {println("abril")}
        5 -> {println("maio")}
        6 -> {println("junho")}
        7 -> {println("julho")}
        8 -> {println("agosto")}
        9 -> {println("setembro")}
        10 -> {println("outubro")}
        11 -> {println("novembro")}
        else -> {println("dezembro")} 
}
*/
    //Laços de Repetição - repete uma ação quando uma determinada
    // condição for verdadeira
    //
    // while -> enquanto
    // 
    // do.. while -> faça..enquanto
    //  
    // for -> para
    //   
    // repeat -> repita
    // 
    // ----------------------------------
    //
    //  repeat - repita
    //  
    //  estrutura do repeat 
    //  
    //  repeat(vezes q vai ser repetido){
    //  ações
    //  }
    /*
    repeat(10){
        println("por ordem dos peaky blinders")
    }
    */
    //Laço While - enquanto
    //
    //Estrutura while
    //
    //while(condição){
    //ações
    //}
    /*
    var dia = 360
    
    while(dia <= 365){
        println(dia)
        dia++
    }
    */
    
    
    //Laço do.. while -> faça enquanto
    //
    //executa a ação enquanto for verdadeira
    //
    // estrutura do do..while
    // 
    //  do{
    //  ação
    //  }while(condição)
    //  
    /*
    var dia = 360
    
    do{
        println(dia)
        dia++
    }while(dia > 365)
    */
    //exercício - Faça um programa, utilizando while,
    // que mostre no console os número de 0 a 100
    // 
    /*
    var num = 0 
    
    while(num <= 100){
        println(num)
        num++
    }
*/
    //Faça um programa utilizando 2 variáveis, e que mostre no console, os números de 0 até N,
    //onde N(você decide o valor) é o valor de uma das variáveis
  
 //Faça um programa utilizando 2 variáveis, e que mostre no console, os números de 0 até N,
    //onde N(você decide o valor) é o valor de uma das variáveis
/*
    var sla = 0
    var n = 5
    
    while(sla <= n){
        println(sla)
        sla++
    }
    */
    // Laço for - para
    // Estrutura do for
    // 
    // for(i in interválo/conllection)
    // {
    // ações
    // }
    
    /*
    for(lugar in 1..19){
        println("feliz carnaval")
    }
    */
     //Faça uma tabuada de um número(que não seja a do 1 e do 0)
     //até o décimo multiplo usando, o laço for
     /*
     for(i in 1..10){
         println(i*8)
         //Objetos - possui Estados(nome, idade, endereço, altura e etc),
   // comportamentos(andar, correr, dormir, comer etc)
   // 
   //a POO é dividida:
   //
   //Classes - São modelos que servem para a construção de objs derivados dele mesmo(Ex Classe pessoa)
   //as classes recebem atributos(os Estados)
   //
   //Métodos - será as instancias da classe, as formas de agir
    //Estrutura de uma classe
    //  class Nome(){ocorridos de um obj}
    /*
    val ricardo = Pessoa() //instanciando um obj
    ricardo.nome = "Ricardo Franco de Oliweira"
    ricardo.altura = 2.15
    ricardo.corDosOlhos = "verde"
    ricardo.peso = 100.0
    println(ricardo.altura) //para exibir um atributo em específico
    */
    val convidado1 = Pessoa("Messi", 1.79, "castanho", 183.0)
    val convidado2 = Pessoa("Tobey Miguire", 1.5, "azul", 53.5)
    //Exercício: Criem um churras e exiba a lista de convidados no console, no min 6 pessoas
    val convidado3 = Pessoa("Franco", 1.80, "castanhon escuro", 70.0)
    val convidado4 = Pessoa("Vini Jr", 1.76, "castanho escuro", 73.0)
    val convidado5 = Pessoa("Eu", 1.80, "castanho", 80.0)
    val convidado6 = Pessoa("Pelé", -1.5, "fechados", -3.0)
    println("Lista de convidados do churras:")
    println("convidado 1: " + convidado1.nome)
    println("convidado 2: " + convidado2.nome)
    println("convidado 3: " + convidado3.nome)
    println("convidado 4: " + convidado4.nome)
    println("convidado 5: " + convidado5.nome)
    println("convidado 6: " + convidado6.nome)
    
}
class Pessoa(val nome: String,
             val altura: Double,
            val corDosOlhos: String,
            val peso: Double){
    //declarando atributos para a classe
    
    var nome = ""
    var altura = 0.0
    var corDosOlhos = ""
    var peso = 0.0
    
     }
    
    
        fun main() {
        var hamster = Animal("roedor",'F',"A sete palmos ebaixo da terra","herbivoro",9,false)
    
          //println("Meu biximho e um "+hamster.especie+" ele e "+hamster.dieta+" e ele mora "+hamster.habitat+" e ta sem cabeça" )
          // hamster.Pacifico(false) 
             hamster.Pistola(true)
        
        }
    class Animal(val especie: String, val genero: Char, val habitat: String,
                val dieta:String, val idade: Int, val voa: Boolean){
   
         
     fun Pacifico(Pacifico:Boolean){
         if(Pacifico == true){
             println("animal morto")
         }else{
             println(" animal comendo não atrapalhe")
             
         }*/
         
fun main(){
    var hamster = Animal("roedor",'F',"A sete palmos ebaixo da terra","herbivoro",9,false)
    hamster.Pistola(true)
}

        class Animal(val especie: String, val genero: Char, val habitat: String,
                val dieta:String, val idade: Int, val voa: Boolean){  
     fun Pistola(Pistola:Boolean){
         if(Pistola == true){
             println("animal morto com cara de bravo")
         }else{
             println(" animal morrendo de felicidade")
             
         }
         
         
         
     }
         
     }
    
    

    
    
    

    
    
    
    
    
