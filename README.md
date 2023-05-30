# Electrical_Grid_Stability
in this project we want to classify Electrical Grid Stability into two groups stable or unstable.4-node star system (electricity producer is in the center) implementing Decentral Smart Grid Control concept. we will use two algorithms to figure out which one has higher accuracy in classifing of this dataset. algorithms which we will use : LogisticRegression and Naive_bayes.

# dataset information

Attribute Information:

11 predictive attributes, 1 non-predictive(p1), 2 goal fields:
1. tau[x]: reaction time of participant (real from the range [0.5,10]s). Tau1 - the value for electricity producer.

2. p[x]: nominal power consumed(negative)/produced(positive)(real). For consumers from the range [-0.5,-2]s^-2; p1 = abs(p2 + p3 + p4)

3. g[x]: coefficient (gamma) proportional to price elasticity (real from the range [0.05,1]s^-1). g1 - the value for electricity producer.

4. stab: the maximal real part of the characteristic equation root (if positive - the system is linearly unstable)(real)

5. stabf: the stability label of the system (categorical: stable/unstable)


# datasets source
[dataset_link](https://archive.ics.uci.edu/ml/datasets/Electrical+Grid+Stability+Simulated+Data+)