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


# Response Memo: Validation Part
We thank the reviewer for this thoughtful and careful comments on the validation part, which have helped us improve both the clarity and the prominence of the validation strategy in the revised manuscript.
We fully agree that validation is central to the contribution of the paper, and we have always treated it as such. In the original version of the manuscript, the full set of validation analyses was presented in detail in the appendix, with only a brief summary provided in the main text. In response to the reviewer’s comment, we have revised the paper to move the validation analyses into the main text and to present them more prominently and transparently.

At the outset, we would like to clarify the overall structure of the paper.
All validation of the PPD measure is conducted exclusively in the section titled “Validating Public Political Discontent” and consists of three distinct and standard validation exercises—internal convergent validation, external convergent validation, and construct validation—presented in Figures 2, 3, and 4, respectively.
These three figures together constitute the full set of validation tests for the measure. In the revised manuscript, we now state this structure explicitly in the main text and more clearly signal the purpose of each validation exercise.

With respect to the external convergent validation test, we emphasize that this test compares PPD scores to evaluations of democratic performance drawn from the ISSP, WVS/EVS, and CSES, which were deliberately excluded from the latent-variable estimation.
Because these variables are entirely external to the measurement model, they provide strong benchmarks for assessing whether the PPD measure behaves as theoretically expected.
Consistent with the reviewer’s point about validation, these relationships are presented as bivariate associations without covariates or adjustments, rather than as attempts at causal inference.
We have revised the discussion of Figure 3 to make this role unambiguous.

We would also like to clarify that all validation tests are analytically separate from the analyses presented in the section “Explaining Political Dissatisfaction.”
Any explanatory variables introduced in that later section—shown in Figure 3 in the originally submitted manuscript and now presented in Figure 6 in the revised version—are not used for validation purposes.
The “Explaining Political Dissatisfaction” section instead serves as an illustrative application of the newly constructed dataset, following a common practice in data-oriented contributions to demonstrate substantive utility after validation has been established.
Variables such as election years are therefore introduced solely in this application context and are not intended to function as validation benchmarks.
In response to the reviewer’s comment, we have revised the language and structure of the manuscript to more clearly distinguish the validation section from the subsequent substantive analysis.

Finally, in line with the reviewer’s suggestion—and in full agreement that validation should be prominent—we have moved key validation analyses from the appendix into the main text.
The appendix continues to provide detailed supporting information—including model specifications, survey-item documentation, and full summary and numeric results—to ensure transparency and replicability.
We hope that these revisions address the reviewer’s concern by foregrounding the validation strategy and maintaining a clear separation between validation and the subsequent illustrative analysis.
