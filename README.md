# Cryptography-and-Encryption
Project for Linear Algebra


Cryptography & Encryption
Presented by Justin
5/5/2015
Abstract:
Cryptography is a message written according to a secret code. It is often used as one of many linear algebra applications.  To begin, assign a number to each letter in the alphabet (with 0 assigned to a blank space).  Based off of an n x ninvertible matrix A, you are able to encrypt and decrypt any code in order to store it so that no one else knows the code but you personally.  First, you will need to encode a message.  Each letter in the message will be represented with a 3x1matrix.  A set of 3x1matrices are known as uncoded row matrices.  For every uncoded matrix, multiply it with the given invertible matrix to obtain a coded row matrix.  After, this forms a sequence of coded row matrices.  However, for this application you must remove the matrix notation to produce a cryptogram.  From here you will be using Gauss-Jordan Elimination in order to find the inverse of the matrix to produce a message.














Introduction
           Encryption is the science of changing data so that it is unrecognizable and useless to an unauthorized person.  Decryption is changing it back to its original form.  The most secure techniques use a mathematical algorithm and a variable value known as a 'key'.  If the key, known as the password, is only known by authorized individual(s), the data cannot be exposed to others.  Only those who know their password can decrypt it.  This is known as 'private key' cryptography.  Many corporations and government agencies use encryption to prevent others from hacking their computing systems.  Because of heavy use of the internet to conduct business, internet security is of the utmost importance.  Suppose a different company should receive confidential information such as passwords, personal identification numbers, credit card numbers, social security numbers, bank account details, the effects can be damaging.  Encryption will prevent from this. 
History
           Invented by Julius Caesar around 200 BC, and comes from greek, meaning “hidden, secret writing”.  Later was called cryptography.  This was the practice and study of techniques for secure communication and was used as a public field in the United States until World War I, when the Army & Navy realized it was a value to national security.  Hill Cipher was invented by Lester S. Hill in 1929, based on linear algebra and matrix theory.  Lester came up with the fact that a plain-text could be encrypted to form a cipher-text.  This text could only be seen by the user.  Through the early 1970s, cryptography was dominated by the government because computers were very expensive and the government released very little information.  The increase in demand for cryptography was driven by industry and individual interest.  Digital communications were obvious candidates for encryption.  It started becoming bigger and bigger as days passed by.  

During WWII, the British “Ultra” project achieved one of the greatest intelligence triumphs in the history of warfare, breaking many Axis codes.  One major target was the German device whose users were convinced it to be unbreakable called the Enigma cipher machine.  The American “Magic” project had some success against Japanese codes.  By the end of the war, Allied-code breakers were experts.  This issue had to stop so the wartime innovations were enthusiastically adopted by post-war and Cold War signal agencies. Presumably many nations now have some agency capable of sophisticated attacks on communications security.
America's National Security Agency (NSA), for example, is said to be the world's largest employer of mathematicians and the world's largest purchaser of computer equipment.  Such claims may be somewhat exaggerated, but beyond doubt the NSA have some excellent mathematicians, lots of powerful computers, sophisticated software, and the organization and funding to apply them on a large scale.  Changes in the world communications systems’ since WWI have provided these agencies with new targets to stop any sort of hacking by cracking the codes used on an enemy's military or diplomatic communications.  Extensive use of radios in war made large-scale attacks such as Ultra possible.  Modern communications made it possible to go far beyond that.  Consider listening on cell phones or receiving electronic mail. None of these targets existed in 1950. But now, all of them can be attacked today and this application can stop from hackers stealing personal information.
Cryptography was primarily a concern of governments, especially of the military, and diplomats.  In recent years, that has changed a great deal.  With computers and networking being on the rise, cryptography is now important to almost everyone among the developments since the 1970s:
•	The US government established the Data Encryption Standard, DES, a block cipher for cryptographic protection of unclassified documents.
•	DES also became widely used in industry, especially regulated industries such as banking.
•	Public key cryptography was invented by Diffie and Hellman.
•	Academic conferences such as Crypto and Eurocrypt began.
•	Several companies began offering cryptographic products: RSA, PGP, the many vendors with PKI products.
•	Cryptography appeared in other products: operating systems, word processors, etc.
•	Network protocols based on crypto were developed: SSH, SSL, and IPsec.
•	Cryptography came into widespread use to secure bank statements, security information, etc.
•	The US government replaced DES with the much stronger Advanced Encryption Standard, AES.
Here is a diagram of the basic use of encryption.
 



Background Information
Back in the old days, many people used cryptograms where they would have messages that are coded and then they had to use different cryptograms to decipher each code.  For cryptography you will need use many linear algebra applications in order to encode your message.  
If you assign a number to each letter, then the message is converted to numbers and partitioned into uncoded row matrices.  Pick any message to write the uncoded matrices of a dimension that is 1x3.  The three characters are places in the 1x3 matrix including all spaces, which are represented as a 0.  To encode a message, use the techniques demonstrated above to choose a nxn invertible matrix that can be row reduced.  You will need the ability to multiply the 1x3 uncoded row matrices with the encoding matrix ‘A’ to get the coded row matrices using matrix multiplication.  After you get the coded row matrices, you will then have to find the inverse of the invertible nxn matrix. 
You will find the inverse by using the Gauss-Jordan elimination method in order to decode a message.  When you use the Gauss-Jordan elimination, you will need to row-reduce.  Also known as a matrix in row-echelon form.  The row-echelon form has the properties where any rows consisting entirely of zeros occur at the bottom of the matrix, for each row that does not consist of zeros, the first nonzero entry is a leading 1, and lastly for two successive nonzero rows, the leading 1 in the higher row is farther to the left that the leading 1 in the lower row.  This will get you the form of a matrix that contains a diagonal set of leading 1s along with zeros above and below each of the leading 1s.  When you row-reduce your invertible nxn matrix, you will include the row-echelon form into your invertible matrix to form a larger matrix (AI).  Lastly, by doing some linear algebra computation, you will receive your inverse matrix (IA^-1).  By doing matrix multiplication with the coded row matrices and the inverse matrix, this will get you your sequence of decoded row matrices.  These decoded row matrices that you received should match with your message.  If not, you have made some sort of math calculation error using matrix multiplication.
Linear Application
-encoding process
-0-26 (A-Z)
-pick any message
-match each letter with the corresponding numbers (0-26) to produce sets of 3x1 matrices called the uncoded row matrices
-multiply each uncoded row matrices with the encoding matrix (needs to be an nxn matrix and must fully row reduce)
-this answer gives us the coded row matrix
-put the coded row matrices in a sequence
-multiply the coded row matrix by the inverse of the invertible matrix (given)
-remove all matrix syntax
-figure out the message

Solution

Conclusion

Acknowledgments


References
