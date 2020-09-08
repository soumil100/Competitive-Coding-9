# Competitive-Coding-9

## Problem 1: Word Ladder (https://leetcode.com/problems/word-ladder/)
Given two words (beginWord and endWord), and a dictionary's word list, find the length of shortest transformation sequence from beginWord to endWord, such that:

Only one letter can be changed at a time.
Each transformed word must exist in the word list. Note that beginWord is not a transformed word.
Return 0 if there is no such transformation sequence.
Example 1:

Input:



beginWord = "hit",



endWord = "cog",



wordList = ["hot","dot","dog","lot","log","cog"]



Output: 5



Explanation: As one shortest transformation is "hit" -> "hot" -> "dot" -> "dog" -> "cog",



return its length 5.

Example 2:

Input:



beginWord = "hit"



endWord = "cog"



wordList = ["hot","dot","dog","lot","log"]



Output: 0



Explanation: The endWord "cog" is not in wordList, therefore no possible transformation.

## Problem 2: Minimum cost of tickets (https://leetcode.com/problems/minimum-cost-for-tickets/)

In a country popular for train travel, you have planned some train travelling one year in advance.  The days of the year that you will travel is given as an array days.  Each day is an integer from 1 to 365.

Train tickets are sold in 3 different ways:

a 1-day pass is sold for costs[0] dollars;
a 7-day pass is sold for costs[1] dollars;
a 30-day pass is sold for costs[2] dollars.
The passes allow that many days of consecutive travel.  For example, if we get a 7-day pass on day 2, then we can travel for 7 days: day 2, 3, 4, 5, 6, 7, and 8.

Return the minimum number of dollars you need to travel every day in the given list of days.

Example 1:

Input: days = [1,4,6,7,8,20], costs = [2,7,15]

Output: 11

Explanation: 



For example, here is one way to buy passes that lets you travel your travel plan:



On day 1, you bought a 1-day pass for costs[0] = $2, which covered day 1.



On day 3, you bought a 7-day pass for costs[1] = $7, which covered days 3, 4, ..., 9.



On day 20, you bought a 1-day pass for costs[0] = $2, which covered day 20.



In total you spent $11 and covered all the days of your travel.



Note:

1 <= days.length <= 365
1 <= days[i] <= 365
days is in strictly increasing order.
costs.length == 3
1 <= costs[i] <= 1000