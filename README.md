# Detailed illustration of each step
Image shown in (darwin_details.pdf)

At each mutation cycle, a candidate instruction is sampled from the archive and mutated into n instructions. Reward-guided replacement is performed for every *m* tokens until all the states have reached the end. The top-*k* instruction is computed and updated in the archive, replacing the candidate instruction if the new output receives a higher reward.


# Tree search conducted by DARWIN to obtain an aligned output
Image shown in (darwin_tree.pdf)
