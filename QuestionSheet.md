#Task Sheet 1

##Question 3(a)

1. GetPlayerName()
2. By using a while loop
3. 

##Question 3(b)
1. UpdateRecentScoress()

##Task 5
1. Time
2. TRecentScore, DisplayRecentScrores
3. 

##Additional Task -  Variable roles
1. Fixed Value - A variable that wont change after it is entered 
   Stepper - A variable used to go through systematic processes such as  iterations
   Most Recent Holder - A Variable that is holding the latest variable that has either
   been came across or has been entered
   Most Wanted Holder - A Variable that is holding the most appropriate value that has
   been came across so far.
   Gatherer - A Variable that accumulates through a sum
   Transformation - A Variable that stores things from calculations
   Follower - A Variable that gets its data from another variable
   Temporary - A Variable that holds a piece of data for a short time only
   
2. Fixed Value - NoOfSwaps (98)
   Stepper - Count (162)
   Most Recent Holder - Choice (197)
   Most Wanted Holder - NextCard (188)
   Gatherer - /
   Transformation - Higher (123)
   Follower - LastCard (187)
   Temporary - SwapSpace (97)
   
##Additional Task - Functions and Parameters
1.When you pass by value into a function the piece of data that you are working on
is coppied so that when you change something you are only changing the copy. This means
that if you want the piece of data outside the function to change you have to return
it then it will change. Whereas if you pass by reference you are passing the data
into the function and working on the original. This means that once you change that
piece of data within the function is automatically changes everywhere else.

2. 	GetRank(RankNo) - By Value
	GetSuit(SuitNo) - By Value
	ShuffleDeck(Deck) - By Reference
	DisplayCard(ThisCard) - By Reference
	IsNextCardHigher - By Value
	GetPlayerName - By Value
	GetChoiceFromUser - By Value
	DisplayEndOfGameMessage(Score) - By Reference
	DisplayRecentScores - By Reference
	UpdateRecentScores - By Reference
	PlayGame - By Reference
	