# Hello_World_WD
    /**Name:(Wara) Alesther Duran Huanca
    Program Description: Hello World 
    Date: 3/25/2022 */
fun printMessage(message: String): Unit {                              
    println(message)
}

fun printMessageWithPrefix(message: String, prefix: String = "Info") {  
    println("[$prefix] $message")
}

fun sum(x: Int, y: Int): Int {                                         
    return x + y
}

fun divide(x: Int, y: Int) = x / y                                   

fun main() {
    printMessage("Hello World")                                                                
      // 8
    println(sum(1, 2))                                                  
    println(divide(8, 4))
}
/** Next time use Float */
