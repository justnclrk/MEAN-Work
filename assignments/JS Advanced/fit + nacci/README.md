Assignment: Fib + Nacci
The Fibonacci sequence is a sequence where each number is the sum of its two predecessors. The sequence starts off like so: (0), 1, 1, 2, 3, 5, 8, etc. The 0 is in parenthesis because it helps the sequence get started but it is not actually part of the sequence.

Using Closures, make the Fib function with the following specifications:

function fib() {
  // Some variables here
  function nacci() {
    // do something to those variables here
  }
  return nacci
}
var fibCounter = fib();
fibCounter() // should console.log "1"
fibCounter() // should console.log "1"
fibCounter() // should console.log "2"
fibCounter() // should console.log "3"
fibCounter() // should console.log "5"
fibCounter() // should console.log "8"