# Aamir-Miguel-Silva-Ricardo-Dias
AamirKhan_MiguelSilva_RicardoDias

Bayesian Networks model conditional dependence between variables, where these variables are connected forming a network [1]. As Brownlee [2] puts it, "Bayesian networks are a probabilistic graphical model that explicitly capture the known conditional dependence with directed edges in a graph model". Bayesian Networks are acyclic, where the nodes correspond to the variables and the arrows represent the dependencies between them. The dependency between features is directed (indicating causality), which contributes to building models that infer the probability of certain events based on previously know variables.

As mentioned before, Bayesian Networks work based on conditional probabilities. For instance, if event A is conditionally dependent on event B, the probability of event A happending is P(A|B) = P(A, B) / P(B). Also, if event C is conditionally dependent on A and B, the likelihood of event C taking place if P(C|A, B) = P(A, B, C) / P(A, B), and so on. This is, therefore, the work basis of Bayesian Networks.
