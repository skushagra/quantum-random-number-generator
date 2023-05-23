# Quantum Random Number Generator

Pseudo Random Number Generators (PRNG) are algorithms that help to create randomness in programs, but they are not truly random like the randomness obtain from physical processes.

Quantum Random Number Generator uses a Quantum Computer to generate truly random numbers using fundamental properties of Quantum Physics. We use `IBM Qiskit` to create a `QuantumCircuit`. We create three circuits two with independent `RX` and `RY` gates respectively, and one with `RX` and `RY` applied together. Therefore we get three values of counts of `0's` and `1's` which are ultimately multiplied to get a random number. The `shots` of each execution are choosen using pusedo-random number generators, built in to Pyhton's `random` module.
