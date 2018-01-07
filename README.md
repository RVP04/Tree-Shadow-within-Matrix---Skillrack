# Tree-Shadow-within-Matrix-Skillrack

<div class="ui raised segment big"> <p>Certain number of trees are planted in a rectangular matrix field. The trees were planted in an R*C rectangular matrix but certain trees did not grow due to lack of ground water. Hence the cells in the matrix which have the trees are indicated by 1 and the cells which do not have trees in it are indicated by 0.</p>

<p>The shadow of the trees always falls on the adjacent cell depending on the direction of the sunlight (The direction of the sunlight can be left-L, right-R, front-F and back-B of the rectangular field). The shadow of a tree does not fall on the ground within the rectangular field if the adjacent cell has a tree. The program must print the count of trees whose shadow falls within the rectangular field (The trees whose shadow falls outside the rectangular matrix field must not be counted. This happens when the trees are along the border and their shadow is outside the rectangular matrix field).</p>

<p><strong>Input Format:</strong><br>
The first line contains R and C separated by a space.<br>
Next R lines contain C values (either 1 or 0) indicating the presence of trees.<br>
(R+2)th line contains the direction of the sunlight.</p>

<p><strong>Output Format:</strong><br>
The first line contains the count of the trees whose shadow falls within the rectangular matrix field.</p>

<p><strong>Boundary Conditions:</strong><br>
2 &lt;= R, C &lt;= 50</p>

<p><strong>Example Input/Output 1:</strong><br>
Input:<br>
3 5<br>
1 0 0 1 0<br>
0 1 0 1 1<br>
1 1 1 0 0<br>
L</p>

<p>Output:<br>
4</p>

<p>Explanation:<br>
The position of the sun is left with respect to the rectangular matrix field. Hence the trees whose shadow will be to the right of the trees. The trees whose shadow fall on the ground within the rectangular matrix field are indicated by X.</p>

<p>X 0 0 X 0<br>
0 X 0 1 1<br>
1 1 X 0 0</p>

<p><strong>Example Input/Output 2:</strong><br>
Input:<br>
3 5<br>
1 0 0 1 0<br>
0 1 0 1 1<br>
1 1 1 0 0<br>
B<br>
&nbsp;<br>
Output:<br>
3</p>

<p>Explanation:<br>
The position of the sun is behind the rectangular matrix field. Hence the shadow will fall in the opposite direction. Hence the trees whose shadow fall on the ground within the rectangular matrix field are indicated by X.<br>
&nbsp;&nbsp; &nbsp;<br>
X 0 0 1 0<br>
0 1 0 X X<br>
1 1 1 0 0</p>
