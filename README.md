fun main() {

    // Create a list of 1 to 100
    val numbers = (1..100).toList()

    // Filter even numbers
    val evens = numbers.filter { it % 2 == 0 }

    // Map numbers to their squares
    val squares = numbers.map { it * it }

    // Reduce to get the sum of all numbers
    val sum = numbers.reduce { acc, n -> acc + n }

    // Print results
    println("Evens:")
    println(evens)

    println("\nSquares:")
    println(squares)

    println("\nSum:")
    println(sum)
}
