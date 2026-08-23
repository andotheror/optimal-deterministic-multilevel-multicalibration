# Optimal Deterministic Multilevel Multicalibration

## Abstract

Multilevel multicalibration asks one predictor to calibrate a sequence of dependent distributional properties, such as a mean followed by a variance and a skewness. A recent sharp characterization gives sample complexity $\widetilde\Theta(\varepsilon^{-(k+2)})$ for $k$ levels, but its optimal upper bound outputs a randomized predictor. This leaves open whether the randomization gap, recently closed for scalar mean multicalibration, returns when calibration conditions jointly bucket a vector prediction. We prove that it does not. Under exactly the regularity conditions of the randomized theorem, a learner outputs a deterministic predictor using

$$\widetilde O\\\\\\!\left(\frac{\varepsilon^{-k}+\log |\mathcal G|}{\varepsilon^2}\right)$$

samples. The rate matches the lower bound for randomized predictors up to logarithmic factors. The proof requires more than applying scalar derandomization coordinatewise. We learn confidence sets for entire conditional outcome laws using only their finite grid-residual vectors, restrict the randomized learner to actions compatible with those sets, and purify its output using one shared seed per data-dependent context cell. A singleton support rule on accurately learned atoms removes a grid-scale variance floor that would otherwise overwhelm the exponentially many signed calibration tests. The theorem applies to every bounded sequentially conditionally identifiable property covered by the randomized theory, including mean and mean absolute deviation, mean, variance, and skewness, and quantile and conditional value at risk.

## Contributions

- A deterministic-output upper bound of $\widetilde O((\varepsilon^{-k}+\log|\mathcal G|)/\varepsilon^2)$ under the same regularity assumptions as the optimal randomized upper bound.
- A confidence-law support lemma that preserves the multilevel minimax game while forcing accurately learned atoms to have singleton support.
- A residual purification theorem whose variance depends on conditional-law uncertainty rather than the prediction-grid width.
- Matching deterministic minimax rates, up to logarithmic factors, for mean and mean absolute deviation, mean, variance, and skewness, and quantile and conditional value at risk.

## Keywords

optimal, deterministic, multilevel, multicalibration, asks, predictor, calibrate, sequence, dependent

## Files

- `main_old_2026-08-13.pdf`, the paper as first published, with its OpenTimestamps proof `main_old_2026-08-13.pdf.ots`.
- source: `iclr2027_conference.bst`, `iclr2027_conference.sty`, `main.tex`, `references.bib`.
- also: `main.bbl`.
