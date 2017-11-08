I have used Microsoft visual studio for this program and written code using .Net

Please include your path where you have placed the .txt file which we are using as input to validate
Use your local path of file in the code :
string[] listOfWords = File.ReadAllLines("C:\\Users\\nelaval\\Desktop\\NET Test 00.txt");

// The output will show following things
1) The 1st longest words that can be made of other words
1) The 2nd longest words that can be made of other words
2) Total count of how many words that can be made of other words



Design and Code Steps followed:   

1) First I sort the strings in descending order "Lengthwise".
2) Start with the first string and loop over sorted strings
3) Check if it can be made of other words by dividing strings into all possible combinations and doing same thing for each splits.
4) Retrun true if it is made of other strings and Save that string onto list.
5) Return the top string because that would be the longest string and find the lenght of the longest word and prints it out.
  Console.WriteLine(madeOfWords[madeOfWords.Count - 1] + " - " + madeOfWords[madeOfWords.Count - 1].Length + " letters");
6) Return the 2nd top string because that would be the 2nd longest string and find the lenght of the 2nd longest word and prints it out.
  Console.WriteLine(madeOfWords[madeOfWords.Count - 2] + " - " + madeOfWords[madeOfWords.Count - 2].Length + " letters");
7) The size of array list will give you the total number of words that can be made of other words.
  Console.WriteLine(madeOfWords.Count);

Output when you run the program:

1.The 1st longest words that the program finds
  Output::  phosphatidylethanolamines - 25 letters
  
2.The 2nd longest words that the program finds
  Output::  immunoelectrophoretically - 25 letters

3. The count of words that can be made of other words
  Output::  62260
