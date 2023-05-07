Download Link: https://assignmentchef.com/product/solved-ir-assignment-1
<br>



Information Retrieval in High Dimensional Data







Please hand in your solutions via Moodle as an IPYTHON (Jupyter) notebook.

Solutions can be handed in by groups of four to five people. Please state the names of your group members at a prominent place in your submission. (For example, at the beginning of your provided notebook or in a separate text file.)

<h1>Curse of Dimensionality</h1>

Task 1: [2 Points] Let denote the <em>p</em>-dimensional hypercube of edge length <em>d</em>, centered at the origin.

<ul>

 <li>Assume <em>X </em>to be uniformly distributed in C<sub>1</sub>. Determine <em>d </em>in dependence of <em>p </em>and <em>q </em>∈ [0<em>,</em>1], such that</li>

</ul>

Pr(<em>X </em>∈ C<em><sub>d</sub></em>) = <em>q</em>

holds.

<ul>

 <li>Let the components of the <em>p</em>-dimensional random variable <em>X<sup>p </sup></em>be independent and have the standard normal distribution. It is known that Pr(|<em>X</em><sup>1</sup>| ≤ 2<em>.</em>576) = 0<em>.</em>99. For an arbitrary <em>p</em>, determine the probability Pr(k<em>X<sup>p</sup></em>k<sub>∞ </sub><em>&gt; </em>2<em>.</em>576) for any of the components of <em>X<sup>p </sup></em>to lie outside of the interval [−2<em>.</em>576<em>,</em>2<em>.</em>576]. Evaluate the value for <em>p </em>= 2, <em>p </em>= 3 and <em>p </em>= 500.</li>

</ul>

Task 2: [10 Points] Provide the PYTHON code to the following tasks (the code needs to be commented properly):

<ul>

 <li>Sample 100 uniformly distributed random vectors from the box [−1<em>,</em>1]<em><sup>d </sup></em>for <em>d </em>= 2.</li>

 <li>For each of the 100 vectors determine the minimum angle to all other vectors. Then compute the average of these minimum angles. Note that for two vectors <em>x, y </em>the cosine of the angle between the two vectors is defined as</li>

</ul>

<em>.</em>

<ul>

 <li>Repeat the above for dimensions <em>d </em>= 1<em>,…,</em>1000 and use the results to plot the average minimum angle against the dimension.</li>

 <li>Give an interpretation of the result. What conclusions can you draw for 2 randomly sampled vectors in a <em>d</em>-dimensional space?</li>

 <li>Does the result change if the sample size increases?</li>

</ul>

<h1>Statistical Decision Making</h1>

Task 3: [10 Points] Answer the following questions. All answers must be justified.

<ul>

 <li>The numbers in Figure 1 show the probability of the respective event to happen (e.g. the probability for the event <em>X </em>= 1 and <em>Y </em>= 1 is 0<em>.</em>02). Is this table a probability table? If so, why?</li>

 <li>Based on Figure 1 give the conditional expectation E<em>Y </em><sub>|<em>X</em>=2</sub>[<em>Y </em>] and the probability of the event <em>X </em>= 1 under the condition that <em>Y </em>= 3.</li>

 <li>Is the function <em>p</em>(<em>x,y</em>) given by</li>

</ul>

(

1            for <em>p</em>(<em>x,y</em>) =

0    otherwise

a joint density function for two random variables?

<ul>

 <li>For two random variables <em>X </em>and <em>Y </em>the joint density function is given by</li>

</ul>

(2<em>e</em>−(<em>x</em>+<em>y</em>)                 for 0 ≤ <em>x </em>≤ <em>y, </em>0 ≤ <em>y</em>

<em>p</em>(<em>x,y</em>) =

0                    otherwise.

What are the marginal density functions for <em>X </em>and <em>Y </em>respectively?

<ul>

 <li>Let the joint density function of two random variables <em>X </em>and <em>Y </em>be given by</li>

</ul>

for 0 <em>&lt; x &lt; </em>3<em>, </em>0 <em>&lt; y &lt; </em>1

<em>p x,y</em>

0                          otherwise.

Determine the probability for <em>X </em>≤ 2 under the condition that.

Task 4: [3 Points] Show that the covariance matrix <strong>C </strong>of any random variable <em>X </em>∈ R<em><sup>p </sup></em>is symmetric positive semidefinite, i.e. <strong>C </strong>= <strong>C</strong><sup>&gt; </sup>and <strong>x</strong><sup>&gt;</sup><strong>Cx </strong>≥ 0 for any covariance matrix <strong>C </strong>∈ R<em><sup>p</sup></em><sup>×<em>p </em></sup>and any <strong>x </strong>∈ R<em><sup>p</sup></em>.

Figure 1: Task 3