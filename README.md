cloning_simulation
==================

Simulates sample of barcoded cells.

We start with 300,000 cells barcoded with one of 14000 unique identifiers. The cells are evenly divided between the identifiers.

After this, we repeatedly perform the following:

* Grow the cell population. The number of cells of each population is increased to reflect exponential growth of the population. We use rate consistent with a doubling every 19 hours- this yields a ~13x growth across 3 days.
* After 3 days, randomly select 300,000 cells from the population (should be around 4,000,000 after 3 days of growth).
* Report the number of unique barcodes present in the 300,000 selected cells.

The above is simulated for 25 cycles (or 75 days).
