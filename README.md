# Detailed illustration of each step

At each mutation cycle, a candidate instruction is sampled from the archive and mutated into n instructions. Reward-guided replacement is performed for every *m* tokens until all the states have reached the end. The top-*k* instruction is computed and updated in the archive, replacing the candidate instruction if the new output receives a higher reward.

<img width="421" alt="Screenshot 2024-07-27 at 8 30 54 PM" src="https://github.com/user-attachments/assets/02f30619-4b22-4465-86d6-81d9089a5593">

# Tree search conducted by DARWIN to obtain an aligned output
<img width="431" alt="Screenshot 2024-07-27 at 8 32 02 PM" src="https://github.com/user-attachments/assets/7eb24452-6571-4fbc-9294-040290b2857a">
