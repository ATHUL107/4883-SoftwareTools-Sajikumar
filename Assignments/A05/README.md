## Assignment 5 - FamilyTree via Graphviz
### Athul Sajikumar
### Description:

This assignment involves creating a family graph for family data that include clans. The family tree data was generated using the [site](http://mcdemarco.net/tools/family-tree-generator/lineage.html) discussed in the class. Names of the data were replaced with names from the name files provided, as the names generated are random and un-real. The `dot` and `image` of the family graph are generated using the **Graphviz** python library. All the files are included in the repo.

### Files


|   #   | File            | Description                                        |
| :---: | --------------- | -------------------------------------------------- |
|   1   |[Edit.py](./Edit.py)        | Python code used to edit the family tree data      |
|   2   | [Dot_file.py](./Dot_file.py)  | Python code which generated the dot file and the family graph tree        |
|   3   | [family_tree.dot](./family_tree.dot) | Dot file containing the family graph tree |
|   4   | [family_tree.png](./family_tree.png) | PNG image of the family-graph tree |
|   5   | [family_tree_data.csv](./family_tree_data.csv) | Family tree data after editing  |
|   6   | [tree.csv](./tree.csv) | Family tree generated from the [site](http://mcdemarco.net/tools/family-tree-generator/lineage.html) |

### Instructions

- Make sure you install the python libraries `graphviz` and `colorsys`
- Iclude the `mock_names.csv` in the current directory, it is used to rename.
- Include the graph data generated in the current directory and rename it as `tree.csv`
- First run the `Edit.py`, then `Dot_file.py` to edit the family data and create the dot file.

### Common Errors

- Common Errors / Reasons for projects not to run
    - Install the required libraries
    - Set correct path to access Files
    - Set correct file names and extensions to avoid errors