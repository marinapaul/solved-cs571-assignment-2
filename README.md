Download Link: https://assignmentchef.com/product/solved-cs571-assignment-2
<br>



——————————————————————————————————————————-

<h1>Questions</h1>

——————————————————————————————————————————-




<ol>

 <li><strong>Genetic Algorithm: </strong>

  <ol>

   <li>Implement the 8 puzzle problem using a genetic algorithm.</li>

  </ol></li>

</ol>

Start state (Can take any random order of numbers with B denoting a blank) An Example:

<table width="151">

 <tbody>

  <tr>

   <td width="53"><strong>5 </strong></td>

   <td width="51"><strong>B </strong></td>

   <td width="47"><strong>8 </strong></td>

  </tr>

  <tr>

   <td width="53"><strong>4 </strong></td>

   <td width="51"><strong>2 </strong></td>

   <td width="47"><strong>1 </strong></td>

  </tr>

  <tr>

   <td width="53"><strong>7 </strong></td>

   <td width="51"><strong>3 </strong></td>

   <td width="47"><strong>6 </strong></td>

  </tr>

 </tbody>

</table>

<strong> </strong>

Goal state (fixed):

<table width="151">

 <tbody>

  <tr>

   <td width="53"><strong>1 </strong></td>

   <td width="51"><strong>2 </strong></td>

   <td width="47"><strong>3 </strong></td>

  </tr>

  <tr>

   <td width="53"><strong>4 </strong></td>

   <td width="51"><strong>5 </strong></td>

   <td width="47"><strong>6 </strong></td>

  </tr>

  <tr>

   <td width="53"><strong>7 </strong></td>

   <td width="51"><strong>8 </strong></td>

   <td width="47"><strong>B </strong></td>

  </tr>

 </tbody>

</table>




<ol>

 <li>At each step show the following

  <ol>

   <li>Initial population (assume to be 10)</li>

   <li>Selection (use <strong>Roulette Wheel Selection</strong>​ )​</li>

  </ol></li>

</ol>

<ul>

 <li>Crossover (high probability value to be chosen, usually above 0.6)</li>

</ul>

<ol>

 <li>Mutation (low probability value to be chosen, usually below 0.2)</li>

 <li>Fitness function: No. of misplaced tiles; Manhattan distance</li>

</ol>

<ol>

 <li>Execute for a sufficient number of generations (or, iterations)</li>

</ol>




<ol start="2">

 <li><strong>Simulated Annealing </strong></li>

</ol>

<strong> </strong>

Simulated annealing (SA) is a generic probabilistic metaheuristic for the global optimization problem of applied mathematics, namely locating a good approximation to the global minimum of a given function in a large search space.

<ol>

 <li>Implement <strong>Simulated</strong>​<strong> Annealing Search Algorithm</strong> for solving the 8-puzzle problem. <strong>Your start and Goal state should follow similar guidelines as given in Q.1.a</strong>​ .​</li>

</ol>




<strong>b</strong>.​ <strong>Input</strong>​ :​ Input should be taken from an input file and processed as a matrix. Other inputs are Temperature variable T, heuristic function, neighbourhood generating function, a probability function to decide state change, and a cooling function.




<ol>

 <li>​ <strong>Output</strong>​ :​ All the following results should be stored in an output file:

  <ol>

   <li>The success or failure message​</li>

   <li>Heuristics chosen, Temperature chosen, cooling function chosen, Start state, and Goal state.</li>

  </ol></li>

</ol>

<ul>

 <li>(Sub) Optimal Path (on success),​   Total number of states explored.​        <strong>v.</strong> Total amount of time taken.​</li>

</ul>




<ul>

 <li>​ <strong>Objective functions to be checked:</strong>​

  <ol>

   <li>h1 (n)= Number of displaced titles.​ h2 (n)= Total Manhattan distance.​</li>

  </ol></li>

</ul>




<ol>

 <li>​ <strong>Constraints to be checked:</strong>​

  <ol>

   <li>Check whether the heuristics are admissible.​   What happens if we make a new heuristics h3 (n)= h1 (n) * h2 (n).​                             <strong>iii.</strong> What happens if you consider the blank tile as another tile.​                                                                                                                                 <strong>iv.</strong> What if the search algorithm got stuck into Local optimum? Isthere any way to get out of this?</li>

  </ol></li>

</ol>








