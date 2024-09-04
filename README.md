# MovieDB
 Java implementation of a movie database


***We need to implement the following Relational Algebra operators***

### Relational Algebra Operators

#### JOIN $\Join$

- **Description:** Combines two relations based on a common attribute.
- **Syntax:** $R \Join S$
- **Example:** If $R$ and $S$ are two relations with a common attribute $A$, then $R \Join S$ will return all pairs of tuples, one from $R$ and one from $S$, where the values of $A$ match.

#### SELECT $\sigma$

- **Description:** Filters tuples from a relation based on a specified condition.
- **Syntax:** $\sigma_{condition}(R)$
- **Example:** $\sigma_{age > 30}(Employees)$ would return all employees older than 30.

#### PROJECT $\Pi$

- **Description:** Extracts specific columns from a relation, removing duplicates.
- **Syntax:** $\Pi_{attribute_1, attribute_2, \dots}(R)$
- **Example:** $\Pi_{name, salary}(Employees)$ would return a relation with just the `name` and `salary` attributes of all employees.

#### UNION $\cup$ (DONE)

- **Description:** Combines the tuples of two relations into a single relation, removing duplicates.
- **Syntax:** $R \cup S$
- **Example:** If $R$ and $S$ are two relations with the same attributes, $R \cup S$ will return all tuples that are in either $R$, $S$, or both.

#### MINUS - (DONE)

- **Description:** Returns tuples from one relation that are not present in another.
- **Syntax:** $R - S$
- **Example:** If $R$ and $S$ are two relations with the same attributes, $R - S$ will return all tuples that are in $R$ but not in $S$.

## Notes

The functions we need to implement are found in `Table.java` at around line 200 and after

`ctrl + f` for "//  T O   B E   I M P L E M E N T E D"


## Copy of the Rubric

|Points| Operation| Completed |
|------|----------|----------|
|20 |Natural Join| |
|20 |Project| |
|20 |Union| |
|20 |Minus| |
|10 |TypeCheck| |
|10 |Java Doc (all interfaces, classes, fields, constructors, methods and parameters must be documented) & README file| |
|100 |TOTAL| |
