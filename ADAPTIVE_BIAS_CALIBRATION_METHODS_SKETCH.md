# Adaptive Bias Calibration (ABC)

## A generalised scenario-based method for training context-sensitive cognitive and behavioural policies

**Status:** Methods/concept paper sketch v0.1  
**Date:** 29 September 2026  
**Working target journal:** *Applied Psychology: An International Review*  
**Method name:** **ABC — Adaptive Bias Calibration**

---

## Abstract

Many psychological interventions teach people what to think, what strategy to use, or what sequence of steps to perform. A harder transfer problem concerns **when a particular policy should control responding**. Cognitive Bias Modification for Interpretation (CBM-I) provides an important precedent: repeated resolution of ambiguous scenarios can alter interpretation tendencies. However, conventional bias-modification paradigms often train a preferred directional interpretation, and change on the trained cognitive process does not by itself establish transfer to new situations or everyday behaviour.

We propose **Adaptive Bias Calibration (ABC)**, a generalised scenario-based intervention framework designed to train **context-sensitive policy calibration** rather than replace one fixed bias with another. ABC presents systematically constructed situations in which bias-driving cues compete with information that is more or less diagnostic of the current goal. During training, participants make simple binary YES/NO judgements and receive immediate audiovisual correct/incorrect feedback plus a brief explanation. Matched reversal cases ensure that the same salient cue is sometimes relevant and sometimes irrelevant, so successful performance requires discrimination rather than response habit. Training can then concentrate adaptively on an individual's systematic error patterns while preserving counterexamples and held-out assessment items.

ABC extends beyond laboratory calibration through a **Reality Loop**. The trained policy is linked to an authentic cue using an implementation intention, an outcome prediction is recorded, and later experience is examined through a brief Reality Review. The complete method therefore links ambiguity resolution, bias modification, psychometric item construction, transfer-of-training principles, implementation intentions, feedback, error-based learning and structured reflection. ABC is proposed as an evidence-informed but presently unvalidated framework with potential applications in health psychology, organisations, education, human-AI interaction and cognitive strategy training.

---

# 1. The problem: policy knowledge is not policy calibration

Interventions frequently teach explicit rules, strategies or scripts successfully without establishing reliable deployment outside the training context.

A learner may know:

- how to check an argument;
- how to respond to a symptom;
- how to prioritise competing work;
- how to verify an AI output;
- how to manage interruption;
- how to generate alternatives;
- or how to make a decision under uncertainty;

yet still fail to recognise **when** the relevant policy should be used, apply it where it should not be used, or retain it when diagnostic evidence indicates that it should change.

This distinction can be expressed as:

> **Policy knowledge:** What strategy or response is available?

versus:

> **Policy calibration:** Under which configuration of cues, evidence, goals and constraints should this policy control responding?

ABC targets the second problem.

The central proposal is that many biases can be operationalised as **systematic distortions in the mapping between cue structure and selected policy**.

A single response is not itself a bias. In ABC, a bias is provisionally defined as:

> **A systematic shift in responding across a family of matched situations when a theoretically bias-driving cue is manipulated independently of the information that should normatively control the response.**

The target is therefore **calibration**, not global elimination of urgency, salience, persistence, caution, threat sensitivity, novelty seeking, closure or any other response tendency.

The same cue can be adaptive in one context and maladaptive in another.

---

# 2. Intellectual lineage: from CBM-I to ABC

ABC develops most directly from **Cognitive Bias Modification for Interpretation (CBM-I)**.

Mathews and Mackintosh (2000) showed that repeated exposure to ambiguous scenarios resolved in systematically threatening or benign directions could alter subsequent interpretation tendencies. Later CBM-I paradigms commonly used ambiguous scenarios followed by a constrained interpretation and YES/NO comprehension judgement with immediate corrective feedback.

Meta-analytic work suggests that CBM-I can alter the cognitive process it directly targets, although effect sizes are heterogeneous and broader symptom or transfer effects are less consistent (Menne-Lothmann et al., 2014; Martinelli et al., 2022).

Health psychology provides an important translational lineage. Jones and Sharpe (2014) adapted ambiguity-resolution training to pain-related interpretation. Gaffiero et al. (2022) developed and validated adult ambiguous-pain scenario sets using free-response and likelihood-based formats, demonstrating how scenario materials can be constructed for a specific applied domain. Sharpe et al. (2023) reported that online CBM-I changed pain-related interpretation bias and some pain outcomes in people with chronic pain, while notably failing to show improvement on an independent near-transfer interpretation task.

ABC takes that transfer problem seriously.

The proposed progression is:

```text
CBM-I
ambiguous situation
→ constrained resolution
→ corrective feedback
→ altered interpretation tendency
```

extended to:

```text
ABC
ambiguous situation
→ spontaneous resolution tendency
→ binary discrimination
→ diagnostic reveal / feedback
→ calibrated policy
→ changed-context test
→ implementation intention
→ real-world action
→ outcome
→ Reality Review
```

The novelty is not the claim that scenario feedback can modify cognitive bias. The central hypothesis is that **balanced conditional calibration plus explicit reality-loop deployment may improve policy portability**.

---

# 3. The core ABC principle

ABC does not train:

> “always choose the benign interpretation”

or:

> “always ignore interruptions”

or:

> “always persist”

or:

> “always generate more options”.

Instead, it trains:

> **Is this policy appropriate under these conditions? YES or NO.**

For example, an urgency-calibration family deliberately includes all four combinations:

| Urgency cue | Diagnostic relevance | Calibrated response |
| --- | ---: | --- |
| High | High | YES |
| High | Low | NO |
| Low | High | YES |
| Low | Low | NO |

This allows the task to separate:

- good discrimination;
- general YES responding;
- general NO responding;
- urgency capture;
- failure to notice quiet but important information.

The same logic can be applied to threat, novelty, familiarity, social authority, prior investment, default options, emotional salience, confidence, source prestige, information sufficiency or other theoretically specified bias-driving cues.

---

# 4. The ABC training cycle

## 4.1 Specify the policy and the bias family

Before scenarios are written, define:

- the target policy;
- the bias-driving cue;
- the genuinely diagnostic dimension;
- the goal against which relevance is judged;
- the conditions under which the policy should apply;
- the conditions under which it should not;
- plausible boundary cases;
- and the expected biased response.

Example:

> **Urgency capture:** disproportionate allocation of attentional or behavioural priority to time-pressured cues after controlling for their diagnostic relevance to the current goal.

This makes the construct falsifiable.

## 4.2 Build scenarios from a latent item structure

Scenario prose should be generated from a structured item representation rather than written first and rationalised later.

A generic ABC item should be able to store:

```text
item_id
bias_family
target_policy
domain
wrapper

current_goal
candidate_cue

surface_salience
diagnostic_relevance
urgency
novelty
emotionality
social_status
prior_investment
default_strength

information_sufficiency
cost_of_missing
cost_of_switching

correct_response
bias_consistent_response

difficulty_target
parallel_item_family
assessment_or_training_status
```

The scenario should contain enough information for the keyed answer to be defensible, but should not make that answer obvious by using words such as “irrelevant”, “unimportant” or “clearly correct”.

## 4.3 Initial probe

Before corrective training, administer a brief set of scenarios without strong teaching.

The purpose is not diagnosis. It is to identify **candidate response tendencies** across multiple matched items.

A single answer must never be interpreted as evidence that a person “has” a bias.

## 4.4 Binary discrimination training

The canonical ABC trial is:

```text
AMBIGUOUS / COMPETING-CUE SCENARIO
→ candidate resolution
→ YES / NO
→ audiovisual correct / incorrect feedback
→ one-sentence explanation
→ next trial
```

This keeps the motor and decision format simple while allowing the item content to carry the relevant complexity.

A training item might ask:

> “Should this cue control your response now?”

or:

> “Is this interpretation sufficiently supported?”

or:

> “Do you have enough information to act?”

The exact wording changes with the domain, but the response architecture remains binary.

## 4.5 Contrast, reversal and uncertainty cases

Each bias family should contain:

1. **Canonical cases** — relatively clear examples.
2. **Near-miss cases** — the bias-driving cue is attractive but non-diagnostic.
3. **Reversal cases** — the same cue genuinely matters.
4. **Insufficient-information cases** — the appropriate resolution is not yet to commit.
5. **Changed-context cases** — the same policy relation appears in a different surface or domain.

This structure prevents the learner from replacing one crude heuristic with another.

## 4.6 Adaptive calibration

ABC may adapt the distribution of training cases according to systematic errors.

For example, if the learner disproportionately chooses urgent but irrelevant cues, subsequent training can increase urgency-discrimination items.

However, counterexamples remain mandatory.

An individual showing urgency capture must still encounter:

- urgent + irrelevant → NO;
- urgent + relevant → YES;
- quiet + relevant → YES;
- quiet + irrelevant → NO.

The aim is better discrimination, not response suppression.

## 4.7 Changed-context check

After training, held-out scenarios sample the same underlying bias relation through changed wording, examples and domains.

These items should not simply recycle trained cases.

Improvement here is **app- or protocol-native portability**, not proof of real-world transfer.

---

# 5. Psychometric architecture

ABC should be developed simultaneously as an intervention method and a measurement research programme.

## 5.1 Separate banks

Use one item ontology and generator, but maintain separate banks:

```text
                    ABC ITEM FOUNDRY
                          │
            same latent scenario grammar
                          │
          ┌───────────────┼───────────────┐
          ▼               ▼               ▼
      ABC MEASURE      ABC TRAIN       ABC TRANSFER
      no feedback      feedback        held-out
      estimate bias    recalibrate     test portability
```

Training items must not double as the principal outcome measure.

## 5.2 Signal-detection formulation

Binary items permit a signal-detection model.

For a particular bias family:

- **Hit:** YES when the cue genuinely warrants control.
- **Miss:** NO when it genuinely warrants control.
- **False alarm:** YES when the cue is bias-driving but non-diagnostic.
- **Correct rejection:** NO when it is non-diagnostic.

This allows separation of:

> **sensitivity to diagnostic information**

from:

> **response criterion / tendency under uncertainty**.

This is preferable to reporting percentage correct alone.

## 5.3 Item-development programme

Candidate items should be evaluated for:

- clarity;
- realism;
- keyed-response defensibility;
- alternative reasonable interpretations;
- item difficulty;
- discrimination;
- YES/NO balance;
- domain effects;
- response time;
- unintended cultural assumptions;
- construct contamination.

Cognitive interviewing should ask participants why they answered as they did.

Parallel item twins should be created so that the same surface feature can sometimes be relevant and sometimes irrelevant.

Binary IRT or Rasch-family models can later estimate item and person parameters, but experimental contrasts should remain visible because the theoretically important quantity is the response to the manipulated bias cue.

---

# 6. Crossing the Reality Boundary

Scenario calibration alone does not establish transfer.

ABC therefore adds a **Reality Loop**.

## 6.1 Implementation intention

The learner identifies a real situation in which the trained policy could matter and creates a cue-linked plan:

> **If X occurs, then I will use policy Y.**

Implementation intentions have a substantial evidence base for supporting goal enactment (Gollwitzer & Sheeran, 2006).

Example:

> If an apparently urgent request arrives while I am working on a high-priority task, then I will ask whether it changes the goal, deadline, evidence or consequences before switching.

## 6.2 Prediction

The learner records what they expect to happen if the policy is used.

This turns application into an informative test rather than simple homework.

## 6.3 Real-world opportunity

The person encounters, or does not encounter, the relevant situation naturally.

ABC does not assume the trained policy must always be enacted. Missing authority, safety, resources, information or opportunity may legitimately alter behaviour.

## 6.4 Reality Review

The review remains deliberately simple:

1. **Did the situation occur?**
2. **What captured or influenced you first?**
3. **What did you do?**
4. **What actually happened?**
5. **What did you learn?**

The method does not require a separate user-facing taxonomy of “retain / refine / reopen / replace”.

The important object is prediction-outcome comparison and the learning generated by real experience.

---

# 7. Why the Reality Loop is plausible

The Reality Loop integrates several adjacent evidence bases.

## Transfer of training

Transfer depends on more than acquisition inside the training environment. Meta-analytic evidence indicates relationships between transfer and trainee, training-design and work-environment factors (Blume et al., 2010).

## Behaviour modelling

A meta-analysis of behaviour modelling training found stronger transfer under conditions including contrasting positive and negative models and trainee-generated scenarios (Taylor et al., 2005).

## Implementation intentions

Cue-linked if-then planning can increase accessibility of the intended opportunity and initiation of goal-directed responses (Gollwitzer & Sheeran, 2006).

## Error-management training

Error-management training encourages active exploration and learning from errors. Meta-analytic evidence suggests benefits for post-training and adaptive transfer (Keith & Frese, 2008).

## Feedback plus reflection

Feedback can become more useful when learners explicitly reflect on its implications. Anseel et al. (2009) reported greater subsequent performance improvement when feedback was combined with reflection than when feedback was provided alone.

## Debriefing / after-action review

Structured debriefs have shown positive effects on subsequent effectiveness across individuals and teams (Tannenbaum & Cerasoli, 2013).

ABC combines these ingredients but should not claim that the combined architecture has already been validated.

---

# 8. Cross-domain applications

ABC is not limited to cognitive training or clinical intervention.

## 8.1 Health psychology

Potential targets include:

- threat versus safety interpretation;
- symptom ambiguity;
- pain-related avoidance;
- adherence decisions;
- reassurance seeking;
- premature symptom dismissal;
- evidence sufficiency before escalation.

Health applications require clinically defensible content and safety boundaries.

## 8.2 Organisational psychology

Potential targets include:

- urgency capture;
- authority/status capture;
- interruption decisions;
- default persistence;
- premature switching;
- sunk-investment effects;
- source credibility;
- escalation thresholds;
- human-AI reliance;
- verification decisions.

ABC should not define compliance with managerial preference as “unbiased”. Organisational scenarios must allow the possibility that the environment, authority structure or workflow is the problem.

## 8.3 Education and professional learning

Potential targets include:

- familiarity mistaken for mastery;
- premature answer commitment;
- failure to seek disconfirming evidence;
- over-reliance on salient examples;
- inability to tolerate “cannot yet tell”;
- inappropriate persistence with an unsuccessful method.

## 8.4 Human-AI interaction

ABC could train **appropriate reliance** rather than trust or distrust.

Matched items can vary:

- AI confidence;
- actual evidential support;
- source visibility;
- task stakes;
- domain expertise;
- cost of verification.

## 8.5 Cognitive strategy training

The same engine can operate over:

- attentional allocation;
- relation maintenance;
- source/context binding;
- evidence accumulation;
- search versus closure;
- path prediction;
- explicit reasoning.

The represented object changes; the ABC mechanism remains constant.

---

# 9. General ABC process model

```text
SPECIFY
Define the bias-driving cue, diagnostic criterion and policy boundary.

↓
PROBE
Measure the initial resolution tendency.

↓
DISCRIMINATE
Present systematically structured scenarios.

↓
RESOLVE
Require a simple YES / NO judgement.

↓
FEEDBACK
Provide immediate audiovisual correctness feedback plus a short explanation.

↓
CALIBRATE
Concentrate training around systematic errors while retaining reversals.

↓
VARY
Change the surface, domain and context while preserving the underlying policy relation.

↓
CHECK
Test held-out items without contaminating the outcome measure.

↓
CUE
Create an implementation intention.

↓
PREDICT
State the expected consequence.

↓
ACT
Allow the real environment to respond.

↓
REVIEW
Compare what happened with what was expected and record what was learned.
```

ABC therefore contains two nested loops:

### Laboratory calibration loop

```text
ambiguity → resolution → feedback → recalibration
```

### Reality loop

```text
cue → policy → action → outcome → learning
```

---

# 10. Distinguishing ABC from neighbouring methods

ABC is **not simply CBM-I with different content**. Traditional CBM-I often trains a preferred directional interpretation. ABC deliberately reverses the optimal answer across matched cases and trains conditional discrimination.

ABC is **not simply a debiasing lesson**. Explicit instruction may explain the policy, but repeated scenario discrimination is the training mechanism.

ABC is **not simply implementation-intention training**. Implementation intentions help deploy a response. ABC first attempts to calibrate when that response is appropriate.

ABC is **not simply case-based learning**. Candidate scenarios are generated from experimentally specified cue and relevance structures.

ABC is **not simply an after-action review**. Reality Review is the closing component of a process that begins with controlled ambiguity-resolution training.

---

# 11. Testable hypotheses

The framework generates clear empirical predictions.

1. ABC should change responding on **novel matched scenarios from the same bias family** relative to sham-feedback or information-only controls.
2. Training containing both lure and reversal cases should improve boundary discrimination more than unidirectional training.
3. Successful ABC should increase sensitivity to diagnostic information without merely shifting the global YES/NO criterion.
4. Adaptive concentration on recurrent errors should improve training efficiency relative to fixed schedules.
5. Changed-domain scenario performance should provide stronger evidence of policy portability than repeated performance on trained examples.
6. Adding implementation intentions should increase real-world cue-linked enactment relative to ABC alone.
7. Adding prediction plus Reality Review should improve subsequent changed-context performance relative to implementation intention without structured review.
8. Improvement on training scenarios should not automatically imply change in independent functional outcomes.

---

# 12. Proposed research programme

## Study 1 — Item development and psychometrics

Develop a large candidate bank for one bias family.

Use:

- expert review;
- cognitive interviewing;
- item analysis;
- signal-detection modelling;
- IRT/Rasch modelling where appropriate;
- test-retest analysis;
- parallel forms.

Primary question:

> Can the proposed bias tendency be measured reliably and separately from global response style?

## Study 2 — Experimental calibration

Randomise participants to:

- ABC;
- sham feedback;
- information-only control.

Use held-out parallel items as the proximal outcome.

Primary question:

> Can ABC recalibrate the targeted resolution tendency?

## Study 3 — Transfer mechanism dismantling study

Compare:

```text
ABC
vs
ABC + implementation intention
vs
ABC + implementation intention + Reality Review
```

Separate:

- trained-item change;
- held-out scenario change;
- enactment;
- independent functional outcomes.

## Study 4 — Applied field study

Embed ABC in one genuine health, educational or organisational context.

Primary question:

> Does the calibrated policy survive authentic cue conditions and improve meaningful functioning?

---

# 13. Ethical and normative boundary

ABC supplies “correct” feedback. This creates a substantial normative responsibility.

An item should only be keyed as correct where the relevant goal, evidence, constraints and decision criterion are sufficiently specified.

Where reasonable people could defensibly choose either response, the item should:

- provide more information;
- explicitly make information-seeking the target policy;
- allow multiple defensible answers in assessment mode;
- or be excluded from binary training.

Health ABC must not train indiscriminate reassurance or symptom dismissal.

Organisational ABC must not equate compliance with rationality or classify legitimate resistance to harmful conditions as bias.

ABC should therefore be described as:

> **Calibration against explicitly defined evidence and context criteria, not behavioural normalisation.**

---

# 14. Claims boundary

Evidence supports several component propositions:

- ambiguous-scenario CBM can alter targeted interpretation tendencies;
- ambiguous-scenario materials can be developed for applied health contexts;
- implementation intentions can support cue-linked action;
- transfer is affected by training and application conditions;
- error-management and structured debriefing can support subsequent performance.

The complete ABC architecture has **not** yet been validated.

Its defining empirical question is:

> **Does balanced ambiguous-scenario calibration, combined with cue-linked real-world enactment and Reality Review, produce more portable policy learning than bias modification, strategy instruction or implementation planning alone?**

---

# 15. Publication strategy

The initial methods/concept paper should be written as a **cross-domain intervention framework**, rather than as a Synergy IQ product paper.

### Preferred initial journal

**Applied Psychology: An International Review**

Rationale:

- cross-domain applied psychology scope;
- organisational, health, educational and behavioural applications are all legitimate;
- the framework has a clear methodological contribution;
- later empirical papers can move into domain-specific journals.

A short methods proposal to the editors is recommended before preparing a full submission.

### Later empirical outlets

Depending on study:

- *Behaviour Research and Therapy* — CBM/clinical or health-mechanism trials;
- *Applied Psychology: Health and Well-Being* — health-behaviour implementations;
- *Journal of Applied Psychology* or *Personnel Psychology* — organisational policy-calibration trials;
- *Behavior Research Methods* — ABC item-bank / psychometric methods;
- *Computers in Human Behavior* or human-AI journals — AI reliance/verification ABC.

---

# 16. References

Anseel, F., Lievens, F., & Schollaert, E. (2009). Reflection as a strategy to enhance task performance after feedback. *Organizational Behavior and Human Decision Processes, 110*(1), 23–35. https://doi.org/10.1016/j.obhdp.2009.05.003

Blume, B. D., Ford, J. K., Baldwin, T. T., & Huang, J. L. (2010). Transfer of training: A meta-analytic review. *Journal of Management, 36*(4), 1065–1105. https://doi.org/10.1177/0149206309352880

Gaffiero, D., Staples, P., Staples, V., & Maratos, F. A. (2022). Interpretation biases in pain: Validation of two new stimulus sets. *Frontiers in Psychology, 12*, 784887. https://doi.org/10.3389/fpsyg.2021.784887

Gollwitzer, P. M., & Sheeran, P. (2006). Implementation intentions and goal achievement: A meta-analysis of effects and processes. *Advances in Experimental Social Psychology, 38*, 69–119. https://doi.org/10.1016/S0065-2601(06)38002-1

Jones, E. B., & Sharpe, L. (2014). The effect of cognitive bias modification for interpretation on avoidance of pain during an acute experimental pain task. *Pain, 155*(8), 1569–1576. https://doi.org/10.1016/j.pain.2014.05.003

Keith, N., & Frese, M. (2008). Effectiveness of error management training: A meta-analysis. *Journal of Applied Psychology, 93*(1), 59–69. https://doi.org/10.1037/0021-9010.93.1.59

Martinelli, A., Grüll, J., & Baum, C. (2022). Attention and interpretation cognitive bias change: A systematic review and meta-analysis of bias modification paradigms. *Behaviour Research and Therapy, 157*, 104180. https://doi.org/10.1016/j.brat.2022.104180

Mathews, A., & Mackintosh, B. (2000). Induced emotional interpretation bias and anxiety. *Journal of Abnormal Psychology, 109*(4), 602–615. https://doi.org/10.1037/0021-843X.109.4.602

Menne-Lothmann, C., Viechtbauer, W., Höhn, P., Kasanova, Z., Haller, S. P., Drukker, M., van Os, J., Wichers, M., & Lau, J. Y. F. (2014). How to boost positive interpretations? A meta-analysis of the effectiveness of cognitive bias modification for interpretation. *PLOS ONE, 9*(6), e100925. https://doi.org/10.1371/journal.pone.0100925

Rohrbacher, H., & Reinecke, A. (2014). Measuring change in depression-related interpretation bias: Development and validation of a parallel ambiguous scenarios test. *Cognitive Behaviour Therapy, 43*(3), 239–250. https://doi.org/10.1080/16506073.2014.919605

Sharpe, L., Jones, E. B., Pradhan, P., Todd, J., & Colagiuri, B. (2023). A double-blind phase II randomized controlled trial of an online cognitive bias modification for interpretation program with and without psychoeducation for people with chronic pain. *Pain, 164*(4), e217–e227. https://doi.org/10.1097/j.pain.0000000000002784

Tannenbaum, S. I., & Cerasoli, C. P. (2013). Do team and individual debriefs enhance performance? A meta-analysis. *Human Factors, 55*(1), 231–245. https://doi.org/10.1177/0018720812448394

Taylor, P. J., Russ-Eft, D. F., & Chan, D. W. L. (2005). A meta-analytic review of behavior modeling training. *Journal of Applied Psychology, 90*(4), 692–709. https://doi.org/10.1037/0021-9010.90.4.692
