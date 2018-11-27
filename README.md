# Fuzzy Logic to measure beacon proximity

```bash
$ ./gradlew clean build
$ java -jar build/libs/fuzzy-beacon-proximity.jar <PARAMETERS>
```

## Parameters
<table>
<tr>
<th>Name</th>
<th>Type</th>
<th>Possible values</th>
</tr>
<tr>
<td>signal</td>
<td>double</td>
<td>-</td>
</tr>
<tr>
<td>distance</td>
<td>double</td>
<td>-</td>
</tr>
<tr>
<td>tnorm</td>
<td>String</td>
<td>min, prod, bdiff, drastic</td>
</tr>
<tr>
<td>aggregation</td>
<td>String</td>
<td>max, min</td>
</tr>
<tr>
<td>implication</td>
<td>String</td>
<td>min, prod, max</td>
</tr>
<tr>
<td>defuzzifier</td>
<td>String</td>
<td>centroid, meanmax, smallestmax, largestmax, bisector, wavgmax</td>
</tr>
</table> 
