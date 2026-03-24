## Project Todo

### Definitions:

- Qubit: A quantum bit that holds a superposition state. (A probabilistic mixture of 0 and 1)
- Note: A note is a string of qubits.

### Notes:

The idea is to create unique note that is attributed to a single value that cannot be cloned.
Why? Because we don't want cryptographer nerds cloning money and getting rich.

In other words, we want to ensure that the note is created once and once only.
Why? Because "bank" needs to verify if it is correct or not.

In quantum logic, a state (attributed to a note) has the property of not being able to be cloned.
This can be proven by weisner_guide Theorem 1.1, using the no cloning theorem.

As it is impossible to a certain precision,
this paper focuses on the approach on how in approximation can we get to cloning.

