#AUTHENTICATION BY ENCRYPTED NEGATIVE PASSWORD.

 A password authentication framework that is designed for secure password storage and could be easily integrated into existing authentication systems.
  In this framework, ﬁrst, the received plain password from a client is hashed through a cryptographic hash function (e.g., SHA-256). 
  Then,thehashedpasswordisconvertedintoanegativepassword. 
Finally, the negative password is encrypted into an Encrypted Negative Password (abbreviated as ENP) using a symmetric-key algorithm (e.g., AES), and multi-iteration encryption could be employed to further improve security.
 The cryptographic hash function and symmetric encryption make it difﬁcult to crack passwords from ENPs.
 Moreover, there are lots of corresponding ENPs for a given plain password, which makes precomputation attacks (e.g., lookup table attack and rainbow table attack) infeasible. The algorithm complexity analyses and comparisons show that the ENP could resist lookup table attack and provide stronger password protection under dictionary attack. It is worth mentioning that the ENP does not introduce extra elements (e.g., salt); besides this, the ENP could still resist precomputation attacks. Most importantly, the ENP is the ﬁrst password protection scheme that combines the cryptographic hash function, the negative password and the symmetric-key algorithm,
 without the need for additional information except the plain password.
