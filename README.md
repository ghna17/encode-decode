# encode-decode
A substitution cipher is a way of encoding a message to make it more difficult to read. In a substitution cipher there is an alphabet and a key:
alphabet = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ .?0123456789'
 key = 'DEFGHIJKLMNOPQRSTUVWXYZ .?0123456789ABC'

To encode a message, each letter in the message is translated into the corresponding letter in the key. For example: CAT is encoded to FDW . The C is looked up in the alphabet and then matched to
the F in the key, which is at the same location. Similarly for the A to D and T to W .
To decode a message, the process is reversed. For example: GRJ decodes to DOG. The G is looked up in the key and then matched to the D that appears at the same location in the alphabet. Similarly
for the R to O and J to G.

Substitution cyphers like the one above in which the key is a rotation of the alphabet are known as Caesar ciphers because they were used by Julius Caesar to encode messages he sent to his military
commanders. While at the time of Julius Caesar such encodings likely provided secure communications, today Caesar ciphers are essentially useless as an encryption technique, though
they are still good for providing exercises for programmers learning about strings! In this project you'll develop some functions and then a program that can encode and decode
messages using a Caesar cipher
