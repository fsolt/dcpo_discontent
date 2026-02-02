# Response Memo: DCPO Model Section (Appendix)

## Reviewer's core concern

The reviewer worried that the DCPO model resembles a "magic trick" that stitches together fundamentally incomparable surveys, smooths them, and draws strong conclusions---resting on heroic assumptions.

We added a sentence to indicate that there has been a line of methodological literature about bringing various surveys in properly (XXXX).
Also, we elaborated the methodological bases in a specific section in the supplementary material (XXXX).
The section now explains each of the model's three parameter sets functionally---i.e., what specific incomparability problem each one resolves.
In particularlly, difficulty places all survey items on a common scale by estimating how much of the latent trait each response option expresses, even when questions differ in wording and response formats.
Dispersion downweights noisier questions so that poorly performing items do not distort the estimates---directly countering the concern that the model simply averages over incompatible signals.
Finally, country-specific item bias absorbs translation effects, cultural response-style differences, and other country-level idiosyncrasies that make the same question non-equivalent across contexts.

We also address specifically that surveys contributing to a given country-year often differ in sampling design, population definitions, and weighting. It explains that survey weights are incorporated where available, notes the absence of poststratification (unlike Caughey et al. 2019), and characterizes the resulting limitation honestly---pointing readers to the validation appendix for evidence that residual design effects do not undermine the estimates.

Further responding to the reviewer's concern, the revised text explains that item-level missingness reduces the effective sample size entering the beta-binomial likelihood. 
When nonresponse is extensive, posterior uncertainty widens, automatically limiting that observation's influence on the country-year estimate.

We also pointed out two channels through which the model handles sensitivity-induced bias: (a) the dispersion parameter absorbs excess noise from socially desirable responding, effectively downweighting the affected question; (b) the country-specific bias term captures context-dependent sensitivity (e.g., corruption questions being more taboo in some countries). 
We acknowledges that these mechanisms mitigate rather than eliminate sensitivity-related error.
