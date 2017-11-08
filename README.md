# Brahmani
Code fileName:
InputFilename:NET Test 00.txt

1.The 1st and the 2nd longest words that the program finds
  Ans::
------- 1st Longest Word --------
  phosphatidylethanolamines - 25 letters

------- 2nd Longest Word --------
 immunoelectrophoretically - 25 letters

2. The count of words that can be
  Ans::------- Total Count of Words ---------
  62260

3.constructed as an output in the body of the email and any comments you have on the approach you took.
  Ans::

List<string> Words = LongestWords(listOfWords);
            Words = Words.OrderBy(s => s.Length).ToList();
