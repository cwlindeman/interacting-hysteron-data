# interacting-hysteron-data

All files are tab-delimited txt files. Here are the parameters used to generate each file:

FIGURE 1

noninteracting.txt: midpoints drawn from [-25,25] and lengths drawn from [0,20]. A = 0, gamma = 8, N=11. Average over 450,000 configurations


FIGURE 2

periodicity.txt: midpoints drawn from [-25,25] and lengths drawn from [0,20]. A = .5 and strain amplitude = 8. Average over 10,000,000 (N=2 and N=3), 2,500,000 (N=6), and 1,000,000 (N=10) configurations

trainingtime.txt: midpoints drawn from [-25,25] and lengths drawn from [0,20]. A = .5 and strain amplitude = 8. Average over 10,000,000 (N=2 and N=3), 2,500,000 (N=6), and 1,000,000 (N=10) configurations


FIGURE 3

interacting.txt: midpoints drawn from [-25,25] and lengths drawn from [0,20]. A = .1, N=11, gamma_1 = 8 and gamma_2 = 4. Average over 450,000 configurations

memory.txt: midpoints drawn from [-25,25] and lengths drawn from [0,20]. A = .1, N=11, and gamma_2 = 8. Average over 500,000 configurations


FIGURE 4

fix-and-range.txt: 

for "fix" column: midpoints drawn from [-25,25] and lengths drawn from [5,20]. Interactions drawn randomly from {-1.5,1.5} (ie, equal exactly to \pm 1.5). N=2, gamma_1 = 0, gamma_2 = 8. Average over 7,500,000 configurations

for "range" column: midpoints drawn from [-25,25] and lengths drawn from [5,20]. Interactions drawn randomly from [-2,-1]U[1,2]. N=2, gamma_1 = 0, gamma_2 = 8. Average over 7,500,000 configurations


FIGURE 5

simulation.txt: midpoints drawn from [-0.01,0.01] and lengths drawn from [9.99,10.01]. A = .1, N = 3, gamma_max = 5. Average over 10,000,000 configurations. 

calculation.txt: calculated as described in the paper.


FIGURE 7

smallinteractions-2.txt: midpoints drawn from [-25,25] and lengths drawn from [0,20]. A = .05, N=2, gamma_1 = 0, and gamma_2 = 8. Average over 10,000,000 configurations

smallinteractions-11.txt: midpoints drawn from [-25,25] and lengths drawn from [0,20]. A = .05, N=11, gamma_1 = 0, and gamma_2 = 8. Average over 1,800,000 configurations
