# Probability
Binormal
“Binormal distribution” usually means the bivariate normal distribution: the normal (Gaussian) distribution extended to two random variables, X and Y, considered together.

It’s defined by five parameters:

the mean of X and the mean of Y
the standard deviation of X and the standard deviation of Y
the correlation ρ between X and Y

Its key properties:

Each variable on its own is normally distributed.
The joint density looks like a 3D bell or hill. Its contour lines are ellipses centered on the means.
When ρ = 0, the contours are circles (if the standard deviations are equal) or axis-aligned ellipses. For bivariate normal data, ρ = 0 also means X and Y are independent, which is not true of most other distributions.
The larger |ρ| is, the more the ellipse tilts and stretches along a diagonal, meaning the variables move together (positive ρ) or in opposition (negative ρ).
Any linear combination of X and Y is also normally distributed.

Common examples are the heights and weights of people, or two correlated test scores.

Other meanings:

In ROC analysis (medicine, diagnostics, machine learning), the “binormal model” assumes the test scores of two groups, such as diseased and healthy, each follow their own normal distribution. This gives a smooth ROC curve.
It’s sometimes confused with binomial (counts of successes in a fixed number of yes/no trials) or bimodal (a distribution with two peaks, often a mix of two normals).

If you meant one of those, or want the density formula or a visualization, tell me which and I’ll go into more detail.

and give me examples of real life of a binormal model

“Binormal model” most often refers to the ROC version, where two groups each follow their own normal distribution. Here are real-life examples of both senses.

Binormal model (two groups, each roughly normal)

Medical screening: Blood glucose levels in people with and without diabetes. Each group forms its own bell curve, and the curves overlap. A cutoff value trades off catching more true cases against more false alarms.
Radiology: Radiologists rate how suspicious a mammogram or X-ray looks. Scores for scans with cancer and scans without it are modeled as two normal distributions. This is the classic use of the binormal ROC model.
Spam filters and fraud detection: The model assigns each email or transaction a score. Scores for legitimate and fraudulent items are treated as two overlapping normal distributions, and the threshold you pick determines how much real mail gets flagged.
Psychology (signal detection theory): In a hearing test, the “noise only” and “tone present” trials each produce normally distributed internal responses. Where a person sets their decision threshold determines their hits and false alarms.
Quality control: A sensor or inspection test measures a part, and the readings for defective and good parts form two overlapping bell curves.

Bivariate normal (two correlated variables)

Height and weight of adults: positively correlated, with elliptical contours.
Two exam scores from the same students, such as math and physics.
Father and son heights, the data behind Galton’s original work on correlation and regression.
Returns of two related stocks, often modeled this way in finance, though real returns have heavier tails than a normal distribution.
