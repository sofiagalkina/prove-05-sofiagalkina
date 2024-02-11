**CSE 212 – Programming with Data Structures**

**W05 Prove – Response Document**

------------------------------------------

_It is a violation of BYU-Idaho Honor Code to post or share this document with others or to post it online.  Storage into a personal and private repository (e.g. private GitHub repository, unshared Google Drive folder) is acceptable._

------------------------------------------

**Question 1:**  From Part 1, how did you answer the interview question for the Set Operations problem (should be no more than 30 seconds if spoken aloud)?

If I can't use built-in hashset methods like IntersectWith and UnionWith, for 
Intersection I would write a function using HashSet<T> because it would be best
in terms of time complexity. The function would use the foreach loop to iterate through
both sets and use the Contains method to catch the target value. For the Union problem,
I would create a new HashSet<T> and initialize it to the values of the first set, and
then would use a foreach loop to Add values of the second hashset to the previously
initialized one and return the values. 

**Question 2:**  From Part 2, how did you answer the interview question for the Find Pairs problem (should be no more than 30 seconds if spoken aloud)?

I would initialize two empty hashsets: one to reverse one piece of the string at a
time, and another one as an output hashset to store the symmetric pairs. There would be
a for each loop to sift through the set and see whether the reverse of this word is 
already there using the Reverse() and Contains() methods. If the two letter reversed 
string is in the set, I'd store both the original string and reversed string in a new 
hashset. 

------------------------------------------

_Remember:  Make sure all of your changes are committed and pushed to the `main` branch of your_ **prove-05-[username]** _repository_

_Also, submit this document and a link to your repository in I-Learn_
