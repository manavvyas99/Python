Hill Cipher

Name: Manav Vyas

Module Info: Module 12 Hill Cipher. The due date was 11/13/2022 at 11:59 pm

Approach: 
hill.py: To start with the assignment i imported numpy so that we calculate mathematically. After that, i made 3 keys or arrays in which the first array is 3 x 3 form and the other two are in 2 x 2 form. Later, i created a function to calculate the determinant of our matrix. To calculate, i used the np.linalg.det(). To check if matrix is inverstible or not, i created a function using called invertible which would check using determinant function. After that the inverse function was used to find the inverse of our key matrixes for which a variable was assigned a value of -1. Thereafter a loop for 26 time was created in which the index of character will be multiplied with the determinant. If it results in the remainder as 1, the inverse will be equal to the current index charachter. Then, a function was made which would convert the text into vector. Loop till the lenght of the string. Then a formula was used to find the integerof the character. i+=2 was used so it doesnt repeat after 2. Next i used an encryption function for argument purpose from vectors nd keys. Then a formula type code is made to multiply the vectors to the first row of key and later finds integer for our encrypted character.Similarly, we do it to the second row of our keys.When it comes to the decryption, just like encryption, the function took vectors and keys as an argument. We need the determinant so a variable is created for that. Using determinant, we will be able to find multiplicative inverse of our key. Later, we swap/change/replace the values. After getting the above values, we will be multiplying the vector to first column of the key and similarly to the second column. Later, just like encryption, we will be able to find the integer from the said multiplications. A for loop was created for our three matrixes and later check if they are inversible or not. The plain text was encrypted and decrypted using encryption function. After that, the text was converted to vectors and will print it. At the end if our results show that it not an integer, the matrix wont be a square else the determinant will be 0

References: 
Although very different from our assignment, GitHub helped me understand the concept in a very easy way (EppuHeilimo as well as https://www.codespeedy.com/hill-cipher-implementation/  which is the same). 
I learned the concept during the Wednesday office hour of that week when we were split into groups about this method but just wanted to cite it: https://www.geeksforgeeks.org/how-to-calculate-the-determinant-of-a-matrix-using-numpy/
https://www.geeksforgeeks.org/multiplicative-inverse-under-modulo-m/
https://www.geeksforgeeks.org/check-if-a-matrix-is-invertible/

Bugs: No bugs
