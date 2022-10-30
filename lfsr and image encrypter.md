LFSR and Image Encrypter

Name: - Ethan Wang(ywang480) and Manav Vyas(mvyas1)

Module Info: - LFSR Module 8. Due date is 11/30/2022 at 11:59 pm

Contribution: - 
Ethan: - Coding part, feedback, made sure code runs/updating
Manav: - Comments/annotation, readme file, feedback/organization 

Approach: -
lfsr.py: - First a class was created which is LFSR. After creating the class we added initial states namely seed and tap which converts string to seed and value to tap respectively. Later on, function was created that gives bit at a certain index. After that LFSR itiration was executed which returns new bit and than the first character of seed and tap is calculated. A __name__ was created that calls LFSR which has loop and returns seed from index 1.

image_encrypter.py: - the first part of the assignment was imported. Then PILLOW library was imported along with numpy. A predefined path was given for the umage. Then a variable is created which calls LFSR with an argument seed and tap. Class named ImageEncrypter was created. This class has initial state with lfsr and filename. Object and file name were set. A function was created to open image. The pixelate will convert image into an array. To get height, width, we used self.open_image. Later, a variable was created that which would give us binary value and later on would convert into decimal value. Loop was created for range of width of image which loops for 3 times. pixelated was used to form array and is converted into decimal value. The imagencrypter object was created using 2 previous arguments and was later called. Finally, a loop was created with a range from 0 to 4. The resulting image was saved using save.image().

Bugs: - no bugs
