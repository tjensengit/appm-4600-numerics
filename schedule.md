# Day by day schedule for APPM 4600 Numerical Methods and Scientific Computing

Fall 2025, Instructor: Stephen Becker (Applied Math dept)

# Detailed list of topics
i.e., what we actually covered.  Topics listed for dates in the future are just estimates.

### Week 1, Aug 24-28 2020.  Chapter 1 (preliminaries, floating pt numbers)
- Mon: "Calculus Review" (20 min; [notes](Notes/Ch1_CalcReview.pdf)) and "Floating Point Numbers" (30 min; [notes](Notes/Ch1_FloatingPoint.pdf)), ch 1.1 and 1.2 and other sources
  - [Ch1_SymbolicTaylorSeries](Demos/Ch1_SymbolicTaylorSeries.ipynb) demo
- Wed: "Conditioning" (13 min; [notes](Notes/Ch1_ConditionNumber.pdf)) and "Stability" (13 min; [notes](Notes/Ch1_Stability.pdf)) and "Big-O notation" (26 min; [notes](Notes/Ch1_BigO_notation.pdf)), mostly from Driscoll and Braun, some ch 1.3
  - [Ch1_DataTypes](Demos/Ch1_DataTypes.ipynb) demo
  - [Ch1_ExponentialSummation](Demos/Ch1_ExponentialSummation.ipynb) demo (try the *student* branch version first)
- Fri: "Polynomials and Horner's Rule" (18 min; [notes](Notes/Ch1_PolynomiallConditioning_HornersRule.pdf)), partly from Driscoll and Braun; and "Rates of convergence" (9 min; [notes](Notes/Ch1_ConvergenceRates.pdf)), from ch 2.4
  - [Ch1_Stability_simple](Demos/Ch1_Stability_simple.ipynb) demo (evaluating a quadratic, and relative error; try the *student* branch version first)
  - [Ch1_QuadraticFormula](Demos/Ch1_QuadraticFormula.ipynb) demo (quadratic root finding; try the *student* branch version first)
  - Optional: [Ch1_Extra_Conditioning](Demos/Ch1_Extra_Conditioning.ipynb) is a summary of ch 1 material from Jed Brown's course
  - Optional: [Ch1_RatesOfConvergence](Demos/Ch1_RatesOfConvergence.ipynb)

[//]: # ( The Friday notebooks went much better than others. )

### Week 2, Aug 31-Sep 4 2020.  Chapter 1 and 2
- Mon: "Intro to scalar root-finding" (18 min; [notes](Notes/Ch2_IntroRootfinding.pdf)), "Intro to scalar optimization" (10 min; [notes](Notes/Ch2_IntroOptimization.pdf)), "Condition number of root-finding" (14 min; [notes](Notes/Ch2_AnalysisRootFindingConditionNumber.pdf)), "multiple roots" (8 min; [notes](Notes/Ch2_MultipleRoots.pdf)); some from misc sources or Driscoll and Braun
  - Finish up Friday demos
- Wed: "Bisection Method" (3 videos of 9, 8 and 4 minutes; [notes](Notes/Ch2_BisectionMainIdea.pdf)), from ch 2.1
  - [Ch2_Intersection_GraphingCalculator.ipynb](Demos/Ch2_Intersection_GraphingCalculator.ipynb) demo
- Fri: "Fixed Point Iteration" (3 videos of 9, 12 and 17 minutes; [notes](Notes/Ch2_FixedPointIteration.pdf)), from ch 2.2
  - [Ch2_IntroToBisection.ipynb](Demos/Ch2_IntroToBisection.ipynb) demo
  - [HowToCheckYourAnswerUsingExtendedPrecision.ipynb](Demos/HowToCheckYourAnswerUsingExtendedPrecision.ipynb) and [HowToCheckYourAnswerUsingExtendedPrecision.m](Demos/HowToCheckYourAnswerUsingExtendedPrecision.m)

### Week 3, Sep 9-Sep 11 2020.  Chapter 2 (root-finding, etc)
- Mon (no lecture due to Labor Day)
- Wed: "Newton's Method" (2 videos of 16 and 9.5 minutes; [notes](Notes/Ch2_NewtonsMethod.pdf)), from ch 2.3
  - [Ch2_FixedPointPlots.ipynb](Demos/Ch2_FixedPointPlots.ipynb) demo which uses a nice [geogebra online cobweb plotting app](https://www.geogebra.org/m/uvsfvNDt)
- Fri: "Newton's Method Variants" (secant method, etc.) (2 videos of 21 and 17.5 minutes; [notes](Notes/Ch2_NewtonsMethodVariants.pdf))
  - [Ch2_NewtonsMethod.ipynb](Demos/Ch2_NewtonsMethod.ipynb) demo

### Week 4, Sep 14-Sep 18 2020. Chapter 2 and 3
- Mon: "Aitken Extrapolation" (16 min video; [notes](Notes/Ch2_AitkenExtrapolation.pdf)) and "Zeros of Polynomials and Muller's Method" (8.5 min; [notes](Notes/Ch2_ZerosPolynomialMullers.pdf)), from ch 2.5 and 2.6
  - Note: we switched attendance models, and now use PlayPosit quizzes to record an attendance grade
  - Demo: finish the Newton's method demo from Friday
- Wed: "Intro to Interpolation" (24 min video; [notes](Notes/Ch3_IntroInterpolation.pdf)) and "Lagrange interpolation" (13 min video; [notes](Notes/Ch3_LagrangeAndBarycentricInterpolation.pdf)), from ch 3.1
  - [Ch2_AitkenExtrapolation.ipynb](Demos/Ch2_AitkenExtrapolation.ipynb) demo
- Fri: "Barycentric Interpolation formula" (17 min video; [same notes as before](Notes/Ch3_LagrangeAndBarycentricInterpolation.pdf)) from Driscoll and Braun and [Berrut and Trefethen's 2004 SIAM Review article](https://people.maths.ox.ac.uk/trefethen/barycentric.pdf); and "Lagrange Interpolation Error Bounds" (10 min video; [same notes as before](Notes/Ch3_LagrangeAndBarycentricInterpolation.pdf)) ch 3.2; and "Divided Differences, part 1" (11.5 min video; [notes](Notes/Ch3_DividedDifferences.pdf)) from ch 3.3
  - [Ch3_PolynomialInterpolation.ipynb](Demos/Ch3_PolynomialInterpolation.ipynb) demo, which also links to other demos
  - Further resources on Lagrange interpolation:
    - [8 min youtube video](https://www.youtube.com/watch?v=_zK_KhHW6og) (nice handwriting)
    - [42 min youtube video](https://www.youtube.com/watch?v=M8hF7QChkSY) (with Vandermonde matrix and divided differences) -- this is a standard classroom blackboard lecture from Wen Shen at Penn State (textbook author, nice handwriting)
    - [13 min youtube video](https://www.youtube.com/watch?v=C1Jijw3VaI0)

### Week 5, Sep 21-24 2020. Chapter 3 (interpolation, etc.)
- Mon: "Divided Differences, part 2" (18 min; [same notes as before](Notes/Ch3_DividedDifferences.pdf)) from ch 3.3; and "Hermite Interpolation" (14 min; [notes](Notes/Ch3_Hermite.pdf)) from ch 3.4
  - Demo: continue demo from last Friday
- Wed: "Splines" (part 1, 15 min; part 2, 8 min; part 3, 24 min; [notes](Notes/Ch3_Splines.pdf) ) from ch 3.5 (we'll skip ch 3.6)
  - No Demo, but there's a [midterm review](Notes/Review_Midterm1.pdf) with [answers](Notes/Review_Midterm1.soln.pdf)
- Fri: Review / Q&A for midterm.  Take-home midterm handed out
  - The [written part of the midterm](Exams/Midterm1.pdf) (2 hours, open note, open book), and there was a 45 min true/false or multiple choice section we took via Canvas

### Week 6, Sep 28-Oct 2 2020. Chapter 4 (finite differences)
- Mon: "Intro to numerical differentiation" (19 min; [notes](Notes/Ch4_FiniteDifferencesIntro.pdf)), ch 4.1
  - Demo: [splines](Demos/Ch3_Splines.ipynb)
- Wed: "Finite differences" (32 min; [notes](Notes/Ch4_FiniteDifferences_more.pdf)), ch 4.1
  - Demo: [finite differences](Demos/Ch4_FiniteDifferences.ipynb) which we did together in lecture
- Fri: "Richardson extrapolation" (23 min; [notes](Notes/Ch4_RichardsonExtrapolation.pdf)), ch 4.2
  - Demo: none

### Week 7, Oct 5-Oct 9 2020. Chapter 4 (numerical integration)
- Mon: "Intro to quadrature" (28 min; [notes](Notes/Ch4_quadrature_intro.pdf)), and "Newton Cotes formula" (2 videos, 12 min each; [notes](Notes/Ch4_quadrature_NewtonCotes.pdf)) from ch 4.3
  - Demo: [Misc_speedExamples.ipynb](Demos/Misc_speedExamples.ipynb) and [Ch4_RichardsonExtrapolation.ipynb](Demos/Ch4_RichardsonExtrapolation.ipynb)
- Wed: "Composite quadrature" (29 min; [notes](Notes/Ch4_quadrature_composite.pdf)) from ch 4.4
  - Demo: [Ch4_integration.ipynb](https://github.com/stephenbeckr/numerical-analysis-class/blob/master/Demos/Ch4_integration.ipynb)
  - Note: we are *not* covering Gregory's method; if you're interested, see Bengt Fornberg's talk [Gregory formulas and improving on the Trapezoidal rule](https://www.colorado.edu/amath/sites/default/files/attached-files/2019_unm_0.pdf)
- Fri: "Romberg integration" (31 min; [notes](Notes/Ch4_RombergIntegrationEulerMacLaurin.pdf)) from ch 4.5
  - Demo: [Ch4_CompositeIntegration.ipynb](Demos/Ch4_CompositeIntegration.ipynb)

### Week 8, Oct 12-Oct 16 2020. Chapter 4 (numerical integration)
- Mon: "Adaptive integration" (28 min; [notes](Notes/Ch4_AdaptiveIntegration.pdf)) from ch 4.6
  - Demo: [Ch4_RombergIntegration.ipynb](Demos/Ch4_RombergIntegration.ipynb)
- Wed: "Gaussian quadrature" (2 videos, 21 min and 32 min; [notes](Notes/Ch4_GaussianQuadrature.pdf)) from ch 4.7 and Driscoll and Braun
  - Demo: [Ch4_AdaptiveIntegration.ipynb](Demos/Ch4_AdaptiveIntegration.ipynb)
  - Further resources on Gaussian quadrature:
    - a 4 part youtube video series:
          1. [Preview](https://www.youtube.com/watch?v=k-yUdqRXijo)
          2. [Part 1: Legendre polynomials](https://www.youtube.com/watch?v=65zwMgGZnUs)
          3. [Part 2: Determining the weights](https://www.youtube.com/watch?v=nQZYBWB6q_k)
          4. [Part 3: Explanation](https://www.youtube.com/watch?v=cKKrGr93f6c)
    - Lloyd Trefethen, "[Is Gauss Quadrature Better than Clenshaw–Curtis?](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.157.4174&rep=rep1&type=pdf)"", SIAM Review 50(1), pp. 67–87 (2008)
    - Topics in our class: Gauss-Legendre, Gauss-Laguerre, Gauss-Hermite; *skip* Chebyshev-Gauss. Note that we are *not* covering Clenshaw-Curtis
- Fri: "Multiple Integrals" (26 min; [notes](Notes/Ch4_MultipleIntegrals.pdf)), from ch 4.8
  - Demo: [Ch4_GaussianQuadrature.ipynb](Demos/Ch4_GaussianQuadrature.ipynb)

### Week 9, Oct 19-Oct 23 2020. Chapter 4 (numerical integration) and start Ch 5 (ODE solvers)
- Mon: "Improper Integrals" (40 min; [notes](Notes/Ch4_ImproperIntegrals.pdf)) from ch 4.9
  - Demo: [Ch4_MultidimensionalIntegrals.ipynb](Demos/Ch4_MultidimensionalIntegrals.ipynb)
- Wed: "Introduction to ODEs" (44 min; [notes](Notes/Ch5_IntroToODEs.pdf)), putting them in context (we did *not* discuss DAE; see [Ch5_ODE_resources.md](Notes/Ch5_ODE_resources.md) for a brief discussion we did later), ch 5.1 (ODE theory) and misc.
  - Demo: [Ch4_ImproperIntegrals.ipynb](Demos/Ch4_ImproperIntegrals.ipynb)
  - We are *not* covering PDEs, implicit ODEs, nor [DAEs](https://en.wikipedia.org/wiki/Differential-algebraic_system_of_equations), but we are covering *systems of ODEs*
- Fri: "Euler's Method" (2 videos, intro and error analysis, 10 and 35 min; [notes](https://github.com/stephenbeckr/numerical-analysis-class/blob/master/Notes/Ch5_EulersMethod.pdf)), ch 5.2
  - Demo: [Ch5_ODEs.ipynb](Demos/Ch5_ODEs.ipynb)


### Week 10, Oct 26-Oct 30 2020. Chapter 5 (ODE solvers) and midterm
- Mon: "Systems of ODEs" (32 min; [notes](Notes/Ch5_SystemsOfODEs.pdf)), ch 5.9
  - Demo: [Ch5_EulersMethod.ipynb](Demos/Ch5_EulersMethod.ipynb)
- Wed: "Higher-order Taylor Methods" and local truncation error (26 min; notes), ch 5.3
  - Demo: [Ch5_SystemsOfODEs.ipynb](Demos/Ch5_SystemsOfODEs.ipynb)
- Fri: Review / Q&A for midterm 2. Take-home midterm handed out
  - The written part of the midterm (2 hours, open note, open book), and there is a 45 min true/false or multiple choice section we take on Canvas
  - Here's a [review sheet](Notes/Review_Midterm2.pdf) and the [review sheet solutions](Notes/Review_Midterm2.soln.pdf)
  - We also have a conceptual review sheet from the Driscoll and Braun textbook (PDF on Canvas)

### Week 11, Nov 2-Nov 5 2020. Chapter 5 (ODE solvers)
- Mon: "Intro to Runge Kutta" (2 videos, 23 min and 9 min; [notes](Notes/Ch5_RungeKutta_intro.pdf)), ch 5.4
  - No demo, but we went over [Ch5_ODE_resources.md](Notes/Ch5_ODE_resources.md)
- Wed: "More Runge Kutta" (2 videos, 18 and 15 min; [notes](Notes/Ch5_RungeKutta_part2.pdf)), still ch 5.4, adding in lots of Driscoll and Braun
  - Demo: [Ch5_RungeKutta.ipynb](Demos/Ch5_RungeKutta.ipynb)
- Fri: "Adaptive Runge Kutta" and Runge Kutta Fehlberg (29 min; [notes](Notes/Ch5_AdaptiveRK.pdf)), ch 5.5 and lots of Driscoll and Braun
  - Demo: [Ch5_OrbitDemo.ipynb](Demos/Ch5_OrbitDemo.ipynb) on [Verlet integration](https://en.wikipedia.org/wiki/Verlet_integration)

### Week 12, Nov 9-Nov 13 2020. Chapter 5 (ODE solvers)
- Mon: "Multistep methods" and predictor-corrector (2 videos, 19 min and 7 min; [notes](Notes/Ch5_MultistepMethods.pdf))
  - No demo
- Wed: "Adaptive multistep methods and extrapolation" (15 min; [notes](Notes/Ch5_AdaptiveMultistepMethods_and_Extrapolation.pdf)), ch 5.7 and 5.8; as you can tell from the short video, we're not emphasizing this material much
  - Demo: [Ch5_MultistepMethods.ipynb](Demos/Ch5_MultistepMethods.ipynb)
- Fri: "Stability", definitions of consistency/convergence/stability, and stability/convergence of one-step methods (2 videos, 23 min and 18 min; [notes](Notes/Ch5_Stability_1_definitionsOneStep.pdf)), ch 5.10
  - Demo: [Ch5_MultistepMethods_implicit.ipynb](Demos/Ch5_MultistepMethods_implicit.ipynb) continuing what we did last demo but using Newton's method and others to solve implicit update

### Week 13, Nov 16-Nov 20 2020. Chapter 5 (ODE solvers)
- Mon: "Stability of multistep methods" and the characteristic polynomial (40 min; [notes](Notes/Ch5_Stability_2_multistep.pdf)), ch 5.10 continued
  - No demo
- Wed: "Stability Examples" (30 min; [notes](Notes/Ch5_Stability_3_examples.pdf))
  - Demo: [Ch5_Stability.ipynb](Demos/Ch5_Stability.ipynb)
- Fri: "Stiff Equations and Absolute Stability, part 1" (25 min, [notes](Notes/Ch5_Stability_4_stiff_absoluteStability.pdf)), ch 5.11
  - No demo

### Week 14, Nov 23-Nov 27 2020. Chapter 5 (ODE solvers), then Chapter 6 (linear algebra)
- Mon: "Stiff Equations and Absolute Stability, part 2" (19 min, [notes (same as previous class)](Notes/Ch5_Stability_4_stiff_absoluteStability.pdf), and "Intro/review of linear algebra" (33 min; [notes](Notes/Ch6_LinearAlgebraIntro.pdf))
  - Demo: [Ch5_AbsoluteStability.ipynb](Demos/Ch5_AbsoluteStability.ipynb)
- Wed: Complexity of Matrix Multiplication" (22 min; the last part of the video is optional; [notes](Notes/Ch6_ComplexityMatrixMultiplication.pdf)) and "Systems of Linear Equations and Gaussian Elimination" (31 min; [notes](Notes/Ch6_SystemsOfEquations_GaussianElimination.pdf); we discuss some BLAS)
  - Demo: [Ch6_MatrixMultiplication.ipynb](Demos/Ch6_MatrixMultiplication.ipynb), talk about BLAS and LAPACK
- Fri: no class (Thanksgiving break)

### Week 15, Nov 30-Dec 4 2020. Chapter 6 (systems of linear equations)
In chapter 6, we're roughly covering the material from the book, but adding more (conditioning, more details on LAPACK/BLAS), and doing it in a differentn order
- Mon: "LU factorization" (3 videos of 10--12 min each; [notes](Notes/Ch6_LUfactorization.pdf))
  - Demo: no demo, but examples of numerics in practice
  - COVID
    - [Machine Learning to find antivirals](https://spectrum.ieee.org/artificial-intelligence/medical-ai/can-ai-and-automation-deliver-a-covid19-antiviral-while-it-still-matters)
    - Molecular Dynamic simulations to find a vaccine, [summary](https://pubs.acs.org/doi/10.1021/acscentsci.0c01236#) and [main article](https://pubs.acs.org/doi/10.1021/acscentsci.0c01056)
    - [Modeling the spread of COVID](https://spectrum.ieee.org/artificial-intelligence/medical-ai/why-modeling-the-spread-of-covid19-is-so-damn-hard) via ML, ODE compartmental (SIR) and agent-based models
    - and the timely Nov 30 2020 [DeepMind protein folding breakthrough](https://www.nytimes.com/2020/11/30/technology/deepmind-ai-protein-folding.html)
  - [Border & Becker paper](https://rdcu.be/bMwR2) on heritability
    - Take statistics model, reduce computation time from $O(n^3)$ to $O(n^2)$
    - Solving linear equations (via Lanczos, which you'll learn about next semester)
    - Convert $\log(\det(X))$ to an integral, solve via Gaussian Quadrature, ties in with Lanczos
    - Exploit a lot of linear algebra facts
  - Many examples from CU. Here are just a handful:
    - Alireza Doostan (CU aerospace), [Pass-efficient methods for compression of high-dimensional turbulent flow data](https://arxiv.org/pdf/1905.13257.pdf)
    - Paul Constantine (CU CS), see his [Model Reduction for Complex Systems](https://vimeo.com/159629096) talk (about 5 min we see some applications)
    - John Evans and Kurt Maute (CU aerospace), [Adaptive level set topology optimization using hierarchical B-splines](https://arxiv.org/pdf/1909.10607.pdf). Focus on optimization as well as representing geometries (B-splines)
  - The [Chemical & Physical Oceanography group](https://www.colorado.edu/atoc/research/chemical-physical-oceanography) in the ATOC department (and they involve many researchers outside ATOC too, e.g., applied math)
- Wed: "LU factorization details: pivoting" (26 min) and "LU factorization details: block factorization and special types of matrices" (19 min); both videos have these [notes](Notes/Ch6_LU_details_pivoting_Cholesky.pdf)
  - Demo: [Ch6_LU_vs_Cholesky.ipynb](Demos/Ch6_LU_vs_Cholesky.ipynb) (short)
- Fri: "Conditioning of solving linear systems" (20 min; introduces the spectra norm; [notes](Notes/Ch6_ConditioningOfLinearSystems.pdf)) and "Least Squares" (16 min; normal equations and QR; [notes](Notes/Ch6_LeastSquares.pdf))
  - Demo: [Ch6_conditioning_LeastSquares.ipynb](Demos/Ch6_conditioning_LeastSquares.ipynb) (long) and [Ch6_RepeatedSolves.ipynb](Demos/Ch6_RepeatedSolves.ipynb) (short)
