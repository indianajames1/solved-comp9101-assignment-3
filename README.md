Download Link: https://assignmentchef.com/product/solved-comp9101-assignment-3
<br>
<span class="kksr-muted">Rate this product</span>

<ol>

 <li>After the success of your latest research project in mythical DNA, you have gained the attention of a most diabolical creature: Medusa. Medusa has snakes instead of hair. Each of her snakes’ DNA is represented by an upper- case string of letters. Each letter is one of S, N, A, K or E. Your extensive research shows that a snake’s venom level depends on its DNA. A snake has venom level x if its DNA:• has exactly 5x letters• begins with x copies of the letter S • then has x copies of the letter N• then has x copies of the letter A• then has x copies of the letter K• ends with x copies of the letter E.For example, a snake with venom level 1 has DNA SNAKE, while a snake that has venom level 3 has DNA SSSNNNAAAKKKEEE. If a snake’s DNA does not fit the format described above, it has a venom level of 0. Medusa would like your help making her snakes venomous, by deleting zero or more letters from their DNA. Given a snake’s DNA, can you work out the maxi- mum venom level this snake could have? Your algorithm should run in time O(n log n)Hint: Combine binary search with greedy.</li>

 <li>Rock. Paper. Scissors. The rules are simple. The game is contested by two people over N rounds. During each round, you and your opponent simulta- neously throw either Rock, Paper or Scissors. Rock beats Scissors, Scissors beats Paper, and Paper beats Rock. If your throw beats your opponent’s, you gain one point. Conversely, if their throw beats yours, you lose one point. Your opponent is very predictable. You know that they will throw Rock in the first Ra rounds, throw Paper in the next Pa rounds, then finally throw Scissors in the last Sa rounds, where Ra + Pa + Sa = N. You have1</li>

</ol>

to throw Rock in Rb rounds, Paper in Pb rounds, and Scissors in Sb rounds, where Rb + Pb + Sb = N. However, as you are an experienced player, you may throw these in any order you like. At the beginning of the game, you start with 0 points. How should you play to maximise the number of points you can finish with?

3. You are given a time schedule of arrivals ai and departures di of n trains, so 1 ≤ i ≤ n, during each 24 hour period (note: a train can arrive before the midnight and leave after midnight; each train arrives and departs at the same time every day). You need to find the minimum number of platforms so that each train can stay at a platform without interfering with other arrivals and departures.

4.Youaregivenasetofnjobswhereeachjobihasadeadlinedi ≥1and profit pi &gt; 0. Only one job can be scheduled at a time. Each job takes 1 unit of time to complete. We earn the profit if and only if the job is completed by its deadline. The task is to find the subset of jobs that maximises profit. Your algorithm should run in time O(n2).

5. You have to produce and deliver N chemicals. You need to deliver Wi kilo- grams of chemical Ci. Production of each chemical takes one day, and your factory can produce only one chemical at any time. However, all of the chemicals evaporate, and at the end of each day you loose p percent of the amount you had at the end of the previous day, so you need to produce more than what you need to deliver. Schedule the production of the chemicals so that the total extra weight of all chemicals needed to produce to compensate for the evaporation loss is as small as possible.

Hint: First determine how much of a chemical is left after k many days and then compute how much of it has ben lost, and then apply greedy.