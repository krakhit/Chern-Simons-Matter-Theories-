# Chern Simons Matter Theories
I have uploaded some of the Mathematica Codes I wrote during my research, to compute various physical observables in 3d supersymmetric SU(N)
Chern-Simons matter theories. These computations are performed at the 't Hooft large N limit, simultaneously taking the Chern-Simons level 'k' to be large and holding the 't Hooft coupling \lambda= N/k held fixed. The results presented here are exact to ALL orders of perturbation in the 't Hooft coupling, these are examples of exact solutions in Quantum Field Theory and are quite rare.

A fundamental aspect of pure Chern-Simons (CS) theories is the Level rank duality. One version of it is a CS theory at a given level k and rank N is dual to another CS theory with the parameters Level and Rank swapped. When coupled to matter, these theories exhibit the duality in a intriguing way that maps entire RG (Renormalization Group) flows to dual RG flows including the theories at the critical points, in particular it maps theories at strong coupling to theories at weak coupling (strong-weak duality). The theories we study are often at the weakly coupled fixed points, so we can do perturbative expansions. However, to test the duality one need to extrapolate the results to the strongly coupled fixed point, and such a test is only possible if we were able to compute our results to all orders in perturbation. 

At finite N and k, these theories are realistic models that exhibit quantum hall effect. However, most of our computations are still far from the finite regime. However, the duality itself is expected to hold, thus testing it rigorously and sharpening the statement of the duality is a precursor for practical applications. Besides, it is really, really, really hard to solve a quantum physics problem in gauge theories exactly even in the 't Hooft limit. I just feel lucky, we had the right tools,patience and perseverance to make a small dent in this area of human knowledge. Thanks to all my collaborators who walked with me in this journey

Prof Shiraz Minwalla (DTP, TIFR), 
Dr Sachin Jain (IISER Pune),
Dr Umesh Vijayashankar 
Dr Pranjal Nayak (Uni Geneva),
Dr Ashish Shukla (Perimeter Inst),
Dr Lavneet Janagal (KIAS)
DR Tarun Sharma (NISER)

Some of our contributions to this amazing subject are

1. Scattering amplitudes in N=3 theory and checks of Duality. (This was very painful, but satisfactory :) 
    1. https://arxiv.org/abs/2001.02363
    2. https://arxiv.org/abs/1908.08119

2. Correlation functions in N=1,2 theories https://arxiv.org/abs/1907.11722

3. Some cool stuff (I had super fun writing these :) )
    1. Recursion relations for n point tree level amplitudes in N=2 Chern-Simons theories https://arxiv.org/abs/1710.04227
    2. Dual superconformal symmetry of N=2 Chern-Simons theories and tree level exactness of the 4 point amplitude
  https://arxiv.org/abs/1711.02672

4. The first paper where we did the computation of exact four point correlators of N=1 superfields to all orders in coupling, computed the S matrices, and rigorously demonstrated he duality by mapping bosonic S matrices and fermionic S matrices.
https://arxiv.org/abs/1505.06571

On the software side: I am sure that the existing Grassmann package can be enhanced significantly to do much more symbolic manipulations with susy in mathematica, similar to applying variational techniques on software such as Cadabra. 

Some open questions:
1. Rigorous proof of Modified crossing symmetry in CS matter theories. More generally, a general crossing formula for scattering of anyonic particles. 
2. Exact scattering amplitude (in 't Hooft limit) for ABJM theory (Low energy limit of M theory)
3. a formula for expressing physical observables such as resistivity or conductivity in terms of the exact scattering amplitudes.
