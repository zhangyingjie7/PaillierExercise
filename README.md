# PaillierExercise
To test Paillier homomorphic encryption, including
- KeyGen
- Enc
- Dec
- Homomorphic properties
  - When two ciphertexts are multiplied, the result decrypts to the sum of their plaintexts;
  $D(E(m_1)\cdot E(m_2) \pmod {n^2}) $
  - When a ciphertext is raised to the power of a plaintext,the result decrypts to the product of the two plaintexts.


