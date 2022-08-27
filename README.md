# YardiRepo
Words assignment for Yardi

Author:Rupinder Deol

Project: Dictionary Assignment for Yardi

Solution: The solution was first implemented using dictionary and SortedSet data structure for storing words. Reading from file and loading into the data
structure turned out be fast but bottlenecks were identified while retreiving the combination words of length 6 or higher which took
over 12 seconds.

Improvements: After some research I learned that using Trie data could be provide faster performance. I used code and direction provided
by Arnaldo Pérez Castaño and implemented a solution that combined sorted sets and Trie which improved performance by almost 50% (7 seconds).
