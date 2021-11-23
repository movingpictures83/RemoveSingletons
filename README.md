# RemoveSingletons
# Language: Python
# Input: CSV 
# Output: CSV
# Tested with: PluMA 1.1, Python 3.6
# Dependency:

PluMA plugin that removes all taxa with an absolute abundance of '1' from each sample.

The plugin takes as input a CSV file as an abundance matrix.
Entry (i, j) of the abundance matrix corresponds to the absolute abundance of taxon j in sample i.

The resulting abundance matrix with singletons removed is also output as a CSV.
