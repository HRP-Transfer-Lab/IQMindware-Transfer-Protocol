# Adaptive Bias Calibration (ABC): A Generalised Scenario-Based Method for Training Context-Sensitive Policies

## From ambiguity resolution to real-world policy learning

### Sketch paper / conceptual methods paper

## Abstract

Many psychological interventions teach people what to think or what steps to perform, but a more difficult transfer problem concerns **when a particular cognitive or behavioural policy should control responding**. Cognitive Bias Modification for Interpretation (CBM-I) provides an important precedent: repeatedly resolving ambiguous scenarios in a particular direction can alter subsequent interpretation tendencies. However, conventional bias-modification paradigms have generally targeted a predetermined directional bias, and improvements on the trained cognitive process do not necessarily generalise to novel tasks or everyday behaviour.

We introduce **Adaptive Bias Calibration (ABC)**, a generalised scenario-based intervention framework designed to train context-sensitive resolution policies rather than replace one fixed bias with another. ABC presents systematically constructed ambiguous situations in which bias-eliciting cues compete with information that is more or less diagnostic of the current goal. During training, participants make simple binary judgements and receive immediate corrective feedback. Matched reversal cases ensure that the same salient cue is sometimes relevant and sometimes irrelevant, making successful performance dependent on discrimination rather than response habit. Training progressively concentrates on an individual's systematic errors, varies scenario surfaces, and tests performance on held-out scenarios.

ABC then extends training across a **Reality Boundary**. A calibrated policy is linked to an authentic cue using an implementation intention, an outcome prediction is recorded, and later experience is examined through a brief Reality Review. The framework therefore connects ambiguity resolution, bias modification, transfer-of-training principles, implementation intentions, feedback, error-based learning and structured reflection within a single intervention architecture. ABC is proposed as an evidence-informed but presently unvalidated general framework with applications across health psychology, organisational psychology, education, cognitive training, human–AI interaction and behavioural intervention research.

## 1. The transfer problem in strategy and policy interventions

Psychological interventions often succeed at teaching explicit knowledge without establishing reliable deployment outside the training situation. A learner may understand a reasoning rule, health-management strategy, communication technique or decision procedure yet fail to recognise when it should be used, apply it where it should not be used, or abandon it when circumstances change.

This distinction can be framed as the difference between **policy knowledge** and **policy calibration**.

Policy knowledge asks:

> What strategy or response is available?

Policy calibration asks:

> Under which configuration of cues, goals, evidence and constraints should this strategy control behaviour?

A conventional procedural intervention may therefore teach:

> If you encounter problem X, perform steps A → B → C.

ABC instead targets the mapping:

> Given the present evidence and context, does this situation actually call for policy P?

The core proposal is that many apparent "biases" can be understood as **systematic distortions in this resolution mapping**. A person may overweight urgency, threat, novelty, familiarity, social pressure, prior investment, default options, positive information, negative information or immediate reward even when those signals are not sufficiently diagnostic of the decision at hand.

A single response is not itself a bias. Within ABC, a bias is operationally defined as:

> **A systematic shift in responding across a family of matched situations when a theoretically bias-driving cue is manipulated independently of the information that should normatively control the response.**

This matched-scenario principle is central to the proposed psychometric architecture.

Importantly, ABC does not assume that urgency, persistence, salience, optimism, caution or rapid closure are intrinsically irrational. Each may be adaptive under some conditions. The intervention target is therefore **calibration rather than elimination of bias**.

---

## 2. Intellectual origin: from CBM-I to Adaptive Bias Calibration

ABC develops most directly from Cognitive Bias Modification for Interpretation.

Mathews and Mackintosh (2000) showed experimentally that interpretation tendencies could be altered through repeated exposure to ambiguous scenarios systematically resolved in threatening or benign directions. The widely used scenario paradigm subsequently evolved into a format in which an ambiguous scenario is disambiguated and followed by a YES/NO comprehension judgement with immediate correctness feedback, reinforcing the trained interpretation.

Meta-analytic evidence supports the ability of CBM paradigms to alter the cognitive biases they directly target. Martinelli et al. (2022), analysing 91 attention-bias modification samples and 70 interpretation-bias modification samples, found medium effects on the targeted biases, including *g* = 0.58 for CBM-I, although heterogeneity was substantial. Earlier meta-analysis also suggested that repeated training, feedback and the inclusion of varied or non-benign training examples may influence cognitive learning effects.

Health psychology provides an especially instructive development path. Jones and Sharpe (2014) adapted ambiguous-scenario bias modification to pain, demonstrating experimentally that pain-related interpretations could be manipulated. Gaffiero et al. (2022) subsequently developed and validated adult ambiguous-pain scenario materials using free-response and likelihood-based formats, demonstrating how a general ambiguity paradigm can be instantiated in ecologically meaningful domain content.

More recent evidence simultaneously demonstrates the promise and the limitation of this approach. In a randomised trial of 288 people with chronic pain, Sharpe et al. (2023) found that online CBM-I changed interpretation bias and improved pain interference and intensity relative to placebo, but did **not** produce improvement on an independent near-transfer interpretation task. A 2025 systematic review concluded that pain-related interpretation biases are robust and modifiable but that intervention evidence remains relatively small.

ABC takes this transfer limitation as its starting point.

The proposed extension is:

**CBM-I**

ambiguous situation  
→ constrained resolution  
→ feedback  
→ modified interpretation tendency

becomes:

**ABC**

ambiguous situation  
→ spontaneous resolution  
→ diagnostic discrimination  
→ corrective feedback  
→ calibrated policy  
→ changed-context test  
→ real-world cue  
→ action  
→ outcome  
→ Reality Review

The novelty is therefore not the claim that scenario-based feedback can alter biases. The stronger hypothesis is that **conditional calibration plus deliberate connection to authentic environmental cues and outcome feedback may produce more portable policy learning**.

---

## 3. What is being calibrated?

ABC defines a **resolution policy** as a mapping between a configuration of information and a candidate cognitive or behavioural response.

Examples include:

- whether a cue deserves attention;
- whether an ambiguous symptom warrants threat interpretation or further sampling;
- whether a manager's urgent request should interrupt the present task;
- whether a familiar explanation should continue to guide judgement;
- whether an AI-generated claim should be accepted or verified;
- whether enough evidence exists to commit to a decision;
- whether additional alternatives should be generated or search should stop;
- whether an organisational problem calls for individual action, escalation or environmental redesign.

The represented object can therefore differ greatly while the learning mechanism remains constant.

ABC does not require all such tendencies to form a single psychological factor. "Bias" is used at the level of the **specific resolution tendency being experimentally manipulated**.

For example, an organisational Attention-ABC intervention might independently study:

**urgency capture**

time-pressure cue × actual relevance;

**social-demand capture**

status of requester × task relevance;

**switching bias**

novelty/change × need to reorient;

**persistence bias**

strength of the established plan × diagnostic evidence supporting change.

A health application might instead manipulate threat, safety, symptom ambiguity, avoidance, expected harm or evidence sufficiency.

A reasoning application might manipulate belief congruence, source familiarity, prior commitment, plausibility or confirmation-consistent evidence.

The general question remains:

> **Should this information or policy control the response under these conditions?**

---

## 4. The ABC intervention cycle

### Stage 1: Construct specification

Before scenarios are written, the target bias must be operationally defined.

For example:

> **Urgency capture is a disproportionate tendency to allocate behavioural or attentional priority to time-pressured cues after controlling for their diagnostic relevance to the current goal.**

This prevents ABC from becoming a collection of intuitive "bias quizzes".

The intervention designer specifies:

- the bias-driving cue;
- the genuinely diagnostic dimension;
- relevant goals and constraints;
- the candidate policy;
- conditions under which the policy should apply;
- conditions under which it should not;
- plausible boundary cases.

### Stage 2: Scenario construction

Scenarios should contain enough information for one response to be defensible without making the answer linguistically obvious.

Poor item:

> You receive an urgent email. Should you respond?

There is insufficient information.

Better item:

> You are correcting a report due in 20 minutes. A colleague marks a message "urgent" about an away day scheduled for next month. Should this message take control of your attention now?

The answer can now be scored, but the urgency cue remains psychologically plausible.

Scenario prose should be generated from an underlying item structure specifying diagnostic relevance, salience, urgency, novelty, emotionality, social status, prior investment, information sufficiency and the costs of switching or missing the cue. The scenario should therefore be the **surface expression of a formal item**, rather than the formal variables being inferred retrospectively from prose.

### Stage 3: Initial probe

Before substantial corrective training, a brief set of scenarios measures the individual's spontaneous pattern.

No personality or diagnostic inference should be made from a single answer.

Instead, the relevant question is whether repeated responses reveal a systematic relationship between the manipulated bias cue and the person's resolution.

### Stage 4: Binary discrimination training

The canonical ABC training trial is intentionally simple.

**Scenario**

→

**Candidate resolution**

→

**YES / NO**

→

**immediate audiovisual correct/incorrect feedback**

→

**brief explanation**

→

**next trial**

The binary format follows a well-established feature of CBM-I scenario procedures, where YES/NO comprehension judgements accompanied by corrective feedback reinforce the trained interpretation.

ABC differs in that it does not systematically reinforce one direction.

Suppose urgency is the bias-driving cue. Training includes all four combinations:

| Urgency | Diagnostic relevance | Calibrated response |
|---|---|---|
| High | High | YES |
| High | Low | NO |
| Low | High | YES |
| Low | Low | NO |

Consequently:

> "Urgent means switch"

cannot solve the task.

Nor can:

> "Ignore interruptions."

The required discrimination is:

> **Does this cue materially alter what matters under the present goal and constraints?**

### Stage 5: Contrast and reversal cases

Each bias family deliberately contains:

**canonical cases**, where the criterion is relatively clear;

**near misses**, where the bias-driving cue is attractive but non-diagnostic;

**reversal cases**, where the same cue genuinely is diagnostic;

**insufficient-information cases**, where immediate resolution is not yet warranted;

and **changed-domain cases**, where the same relation appears under a different surface.

This element connects ABC to behaviour-modelling evidence. Taylor et al.'s (2005) meta-analysis of 117 behaviour-modelling studies found transfer was stronger under conditions including mixed positive and negative models and trainee-generated scenarios, rather than exposure only to ideal examples.

### Stage 6: Adaptive calibration

Training should progressively concentrate on the learner's systematic error patterns.

If a participant consistently allows urgency to dominate relevance, subsequent training can increase the density of urgency-related contrast items.

Crucially, adaptation must preserve counterexamples. An individual showing urgency capture should receive both:

> urgent but irrelevant → NO

and

> urgent and genuinely consequential → YES.

Otherwise the intervention merely replaces one bias with another.

### Stage 7: Changed-context check

After training, held-out scenarios test whether the calibration survives changed wording, domain and contextual detail.

This is an immediate portability test, not evidence of real-world transfer.

The stronger transfer question remains whether the policy becomes available when the training interface is absent.

---

## 5. From calibration to the Reality Boundary

ABC therefore adds a second learning system to scenario training.

Transfer research has long shown that learning inside a training environment and deployment in another context are distinct outcomes. Blume et al.'s (2010) meta-analysis of 89 studies found that transfer was related not only to trainee characteristics and training design but also to the environment in which trained behaviour had to be used.

ABC attempts to construct an explicit bridge.

### Implementation intention

After scenario calibration, the learner identifies an authentic situation in which the trained policy may become useful.

The policy is converted to a cue-linked plan:

> **If X occurs, then I will use policy Y.**

Implementation intentions have a substantial evidence base. Gollwitzer and Sheeran's (2006) meta-analysis of 94 independent tests found an overall medium-to-large effect on goal attainment and evidence that cue-linked plans increase accessibility of the specified opportunity and facilitate initiation of the intended response.

For an organisational urgency bias, for example:

> **If something marked urgent arrives while I am working on a high-priority task, then I will first ask whether it changes the goal, deadline, evidence or consequences before switching.**

For a pain-related threat policy:

> **If a familiar sensation appears during a planned activity, then I will check the agreed clinical/activity cues rather than automatically treating the sensation as evidence that I must stop.**

Any health implementation would, of course, require clinically appropriate content and safety boundaries.

### Prediction

Before the real-world trial, the learner records what is expected to happen.

This turns application into an informative test rather than merely behavioural homework.

### Action

The learner encounters—or does not encounter—the relevant situation naturally.

The method does not assume that the trained policy must always be enacted. External constraints, missing information, authority, safety or changes in circumstances may legitimately prevent or alter action.

---

## 6. Reality Review

The Reality Review closes the loop without requiring the learner to perform another elaborate classification exercise.

It asks only:

1. **Did the situation occur?**
2. **What captured or influenced you first?**
3. **What did you do?**
4. **What actually happened?**
5. **What did you learn?**

The previously recorded expectation provides a natural prediction–outcome comparison.

This component is supported indirectly by several adjacent literatures.

Error-management training explicitly encourages active exploration and learning from mistakes. Keith and Frese's (2008) meta-analysis found a positive overall effect and particularly strong effects on adaptive transfer to structurally different tasks.

Feedback may also become more useful when followed by structured reflection. Anseel et al. (2009), in two large experimental studies, found that reflection combined with feedback produced greater subsequent performance improvement than feedback alone, whereas reflection without feedback did not reliably improve performance.

Similarly, Tannenbaum and Cerasoli's (2013) meta-analysis found that structured debriefs/after-action reviews improved subsequent effectiveness across both individual and team settings.

ABC's Reality Review is deliberately lighter than a full after-action review, but uses the same fundamental principle:

> **Experience becomes more useful for learning when prediction, action and outcome are compared explicitly.**

---

## 7. Psychometric architecture

ABC should be developed simultaneously as an intervention method and as a measurement research programme.

This requires separating **training items** from **measurement items**.

The proposed architecture is:

**ABC Item Foundry**

→ **ABC Measure**

novel items  
no corrective feedback  
estimate resolution tendency

→ **ABC Train**

matched but separate items  
binary response  
immediate feedback  
adaptive calibration

→ **ABC Transfer**

held-out items  
changed surfaces/domains  
test portability

This separation is important because repeatedly training the same items that later constitute the outcome measure would confound genuine policy change with item learning.

Psychometric work on interpretation-bias measures makes this concern substantive rather than hypothetical. Rohrbacher and Reinecke (2014) demonstrated the feasibility of developing psychometrically matched parallel ambiguous-scenario forms for repeated measurement of change. Conversely, Duken et al. (2025) found poor psychometric properties for some commonly used experimental interpretation-bias measures while more explicit measures performed substantially better.

ABC should therefore not assume that an intuitively plausible bias task is automatically a reliable individual-differences measure.

### Signal-detection formulation

The binary ABC architecture creates a useful signal-detection model.

For an urgency-bias family:

**signal present**

the urgent cue genuinely warrants control;

**signal absent**

the cue is urgent but does not warrant control.

Responses produce:

- hits;
- misses;
- false alarms;
- correct rejections.

Sensitivity can therefore be separated from criterion.

A person who says YES to almost everything is different from a person who selectively overweights urgency, and both are different from a person who fails to notice important but quiet signals.

ABC can consequently estimate:

> **How well does the person discriminate diagnostic from non-diagnostic information?**

separately from:

> **What response tendency do they adopt under uncertainty?**

### Item calibration

Candidate items should be generated in large numbers and screened for:

- clarity;
- realism;
- defensibility of the keyed response;
- difficulty;
- discrimination;
- response balance;
- domain dependence;
- alternative reasonable interpretations;
- unintended cultural or occupational assumptions.

Matched item twins should reverse or alter the relation between the bias-driving cue and genuine relevance.

Binary IRT models can later estimate item difficulty and discrimination, while experimental contrasts and signal-detection analyses retain the theoretically important distinction between diagnostic sensitivity and response criterion.

---

## 8. Cross-domain applications

ABC is intentionally not restricted to cognitive training or clinical psychology.

### Health psychology

Possible targets include:

- threat versus safety interpretation;
- symptom ambiguity;
- pain-related avoidance;
- adherence decisions;
- health-information interpretation;
- excessive reassurance seeking;
- premature symptom dismissal;
- over- or under-response to uncertainty.

The crucial principle is calibration. Health ABC should neither train indiscriminate reassurance nor indiscriminate threat sensitivity.

### Organisational psychology

Possible targets include:

- urgency capture;
- authority/status capture;
- escalation thresholds;
- interruption decisions;
- default persistence;
- premature switching;
- sunk-investment effects;
- source credibility;
- human–AI reliance;
- verification and exception handling.

For example:

> Does a request from a senior manager warrant interruption **because it comes from a senior manager**, or because its contents alter the current task's consequences?

### Education and professional learning

Possible targets include:

- familiarity mistaken for mastery;
- premature answer commitment;
- failure to seek disconfirming evidence;
- over-reliance on salient examples;
- inability to tolerate "cannot yet tell";
- inappropriate persistence with an unsuccessful method.

### Human–AI interaction

ABC could train appropriate reliance rather than either trust or distrust.

For example:

> Is this apparently confident AI answer sufficiently grounded to use without further verification?

Matched items would ensure that confident answers are sometimes correct and sometimes unreliable, and tentative answers sometimes contain the strongest evidence.

### Cognitive strategy training

The same architecture can target:

- attentional allocation;
- memory/source binding;
- evidence accumulation;
- search versus closure;
- path prediction;
- explicit reasoning.

The relevant resolution object changes while the ABC mechanism remains the same.

---

## 9. A general process model

The complete proposed intervention can be represented as:

**SPECIFY**

Define the bias-driving cue, diagnostic information and policy boundary.

↓

**PROBE**

Measure the learner's initial resolution tendency.

↓

**DISCRIMINATE**

Present systematically constructed ambiguous scenarios.

↓

**RESOLVE**

Require a simple YES/NO judgement.

↓

**FEEDBACK**

Provide immediate audiovisual correctness feedback and a short causal explanation.

↓

**CALIBRATE**

Concentrate training around systematic errors while retaining reversal cases.

↓

**VARY**

Change surface features, domains and contexts while preserving the underlying discrimination.

↓

**CHECK**

Test held-out items without contaminating the outcome measure through training.

↓

**CUE**

Form an implementation intention connecting a real-world cue to the calibrated policy.

↓

**PREDICT**

State the expected consequence.

↓

**ACT**

Allow the real environment to respond.

↓

**REVIEW**

Compare what captured the learner, what they did, what happened and what was learned.

This produces two nested feedback loops:

**laboratory loop**

ambiguity → resolution → feedback → recalibration;

and

**reality loop**

cue → policy → action → outcome → learning.

---

## 10. Distinguishing ABC from neighbouring interventions

ABC is not simply CBM-I with different content.

Traditional CBM-I often trains a directional interpretation tendency—for example, benign rather than threatening interpretations.

ABC instead requires the optimal answer to reverse across structurally matched cases. The goal is not a preferred interpretation but **conditional discrimination**.

ABC is not simply a debiasing lesson.

Explicit instruction may state the relevant policy, but successful performance requires repeated discrimination across ambiguous and near-miss cases.

ABC is not simply implementation-intention training.

Implementation intentions help a known response become accessible when its cue occurs. ABC attempts first to determine and train **which cue–policy mapping is appropriate**.

ABC is not simply simulation or case-based learning.

The item architecture systematically manipulates theoretically specified bias-driving cues independently of diagnostic relevance and can therefore support psychometric and experimental modelling.

ABC is not simply an after-action review.

The Reality Review is the final component of a learning process that begins with controlled ambiguity-resolution training and prospective prediction.

---

## 11. Testable hypotheses

The framework generates several falsifiable predictions.

First, ABC should alter responding on **novel matched scenarios from the same bias family**, relative to sham training or information-only controls.

Second, calibration training containing both lure and reversal cases should produce better boundary discrimination than unidirectional training.

Third, ABC should increase sensitivity to diagnostic information without merely shifting the overall YES/NO criterion.

Fourth, adaptive concentration on a learner's dominant error pattern should improve training efficiency relative to fixed scenario schedules.

Fifth, changed-domain scenario performance should provide stronger evidence of policy portability than repeated performance on the original training domain.

Sixth, adding an implementation intention should increase real-world policy enactment relative to scenario training alone.

Seventh, adding prediction plus Reality Review should improve subsequent changed-context performance relative to implementation intention without review.

The strongest claim—improved functioning outside the training context—must be tested independently rather than inferred from scenario performance.

---

## 12. Initial empirical programme

A staged research programme is preferable to a single omnibus trial.

**Study 1: Item development and psychometric validation**

Develop a large candidate scenario bank for one bias family, use cognitive interviewing to detect unintended interpretations, and evaluate item difficulty, discrimination, response balance, reliability, factor structure and parallel forms.

**Study 2: Experimental calibration**

Randomise participants to ABC, sham-feedback and information-only conditions. Test target bias change using held-out parallel items.

**Study 3: Transfer mechanism**

Compare:

ABC alone

versus

ABC + implementation intention

versus

ABC + implementation intention + Reality Review.

Primary outcomes should distinguish trained-item performance, held-out scenario calibration, enactment and independent functional outcomes.

**Study 4: Applied field test**

Embed ABC within one genuine health, educational or organisational context and examine whether the learnt policy survives real cue conditions.

This staged programme would separate four increasingly strong claims:

> **Can the bias be measured?**

> **Can it be experimentally recalibrated?**

> **Does calibration travel to new scenarios?**

> **Does the calibrated policy change meaningful behaviour in context?**

---

## 13. Normative and ethical boundary

ABC requires particular caution because a system supplying "correct" feedback can quietly encode the assumptions of its designers.

A response should therefore only be keyed as correct where the relevant goal, evidence, constraints and criterion have been sufficiently specified.

In many real-world situations there is no objectively correct single policy.

Such scenarios should either:

- supply the missing information;
- explicitly train information-seeking as the correct resolution;
- permit more than one defensible response;
- or be excluded from binary ABC training.

Organisational implementations require additional safeguards. The framework should not define compliance with management preference as "unbiased", nor treat employee resistance as a cognitive error where the environment itself supplies reasonable grounds for resistance.

Likewise, health applications must use clinically defensible criteria and must not train people to ignore potentially important symptoms merely in the name of reducing threat bias.

ABC is therefore best characterised as:

> **calibration against explicitly stated evidence and context criteria, not behavioural normalisation.**

---

## 14. Claims boundary

Evidence already supports several constituent propositions.

Scenario-based cognitive-bias modification can alter targeted cognitive biases.

Ambiguous-scenario methods can be adapted to specific health contexts and psychometrically developed.

Training transfer depends on more than acquisition within the training context.

Cue-linked implementation intentions can support goal enactment.

Error-based learning, feedback-supported reflection and structured debriefing can improve subsequent performance.

The complete ABC architecture has **not** yet been validated.

Its defining empirical question is therefore:

> **Does training context-sensitive resolution policies through balanced ambiguous-scenario discrimination, and then connecting those policies to authentic cues, predictions and Reality Review, produce more reliable transfer than bias modification, strategy instruction or implementation planning alone?**

---

## 15. Conclusion

Adaptive Bias Calibration generalises a productive idea from cognitive bias modification.

People repeatedly encounter situations in which several interpretations, cues or policies are plausible. Their responses are not determined only by capacity or explicit knowledge. They are also shaped by systematic tendencies in **how uncertainty is resolved**.

ABC proposes that these tendencies can be studied and trained using controlled scenario families in which bias-driving cues are experimentally separated from genuine diagnostic value.

Its core learning principle is simple:

> **Do not train a preferred answer. Train discrimination about when the answer is appropriate.**

The Reality Loop extends that principle beyond the training interface:

> **Calibrate in scenarios. Bind the policy to a real cue. Let reality return evidence. Learn from what happened.**

If supported empirically, ABC could provide a common intervention grammar linking experimental cognitive-bias research, strategy training, organisational learning, health psychology and real-world behaviour change.

# References

Anseel, F., Lievens, F., & Schollaert, E. (2009). Reflection as a strategy to enhance task performance after feedback. *Organizational Behavior and Human Decision Processes, 110*(1), 23–35. doi:10.1016/j.obhdp.2009.05.003.

Blume, B. D., Ford, J. K., Baldwin, T. T., & Huang, J. L. (2010). Transfer of training: A meta-analytic review. *Journal of Management, 36*(4), 1065–1105. doi:10.1177/0149206309352880.

Duken, S. B., Moriya, J., Hirsch, C., Woud, M. L., Van Bockstaele, B., & Salemink, E. (2025). Reliability and validity of four cognitive interpretation bias measures in the context of social anxiety. *Behavior Research Methods, 57*, Article 48. doi:10.3758/s13428-024-02576-0.

Gaffiero, D., Staples, P., Staples, V., & Maratos, F. A. (2022). Interpretation biases in pain: Validation of two new stimulus sets. *Frontiers in Psychology, 12*, 784887. doi:10.3389/fpsyg.2021.784887.

Gollwitzer, P. M., & Sheeran, P. (2006). Implementation intentions and goal achievement: A meta-analysis of effects and processes. *Advances in Experimental Social Psychology, 38*, 69–119. doi:10.1016/S0065-2601(06)38002-1.

Jones, E. B., & Sharpe, L. (2014). The effect of cognitive bias modification for interpretation on avoidance of pain during an acute experimental pain task. *Pain, 155*(8), 1569–1576. doi:10.1016/j.pain.2014.05.003.

Keith, N., & Frese, M. (2008). Effectiveness of error management training: A meta-analysis. *Journal of Applied Psychology, 93*(1), 59–69. doi:10.1037/0021-9010.93.1.59.

Martinelli, A., Grüll, J., & Baum, C. (2022). Attention and interpretation cognitive bias change: A systematic review and meta-analysis of bias modification paradigms. *Behaviour Research and Therapy, 157*, 104180. doi:10.1016/j.brat.2022.104180.

Mathews, A., & Mackintosh, B. (2000). Induced emotional interpretation bias and anxiety. *Journal of Abnormal Psychology, 109*(4), 602–615. doi:10.1037/0021-843X.109.4.602.

Menne-Lothmann, C., Viechtbauer, W., Höhn, P., Kasanova, Z., Haller, S. P., Drukker, M., van Os, J., Wichers, M., & Lau, J. Y. F. (2014). How to boost positive interpretations? A meta-analysis of the effectiveness of cognitive bias modification for interpretation. *PLOS ONE, 9*(6), e100925. doi:10.1371/journal.pone.0100925.

Rohrbacher, H., & Reinecke, A. (2014). Measuring change in depression-related interpretation bias: Development and validation of a parallel ambiguous scenarios test. *Cognitive Behaviour Therapy, 43*(3), 239–250. doi:10.1080/16506073.2014.919605.

Sharpe, L., Jones, E. B., Pradhan, P., Todd, J., & Colagiuri, B. (2023). A double-blind phase II randomized controlled trial of an online cognitive bias modification for interpretation program with and without psychoeducation for people with chronic pain. *Pain, 164*(4), e217–e227. doi:10.1097/j.pain.0000000000002784.

Tannenbaum, S. I., & Cerasoli, C. P. (2013). Do team and individual debriefs enhance performance? A meta-analysis. *Human Factors, 55*(1), 231–245. doi:10.1177/0018720812448394.

Taylor, P. J., Russ-Eft, D. F., & Chan, D. W. L. (2005). A meta-analytic review of behavior modeling training. *Journal of Applied Psychology, 90*(4), 692–709. doi:10.1037/0021-9010.90.4.692.

Todd, J., Pickup, B., Coutts-Bain, D., Duijzings, M., & Sharpe, L. (2025). Interpretation bias and its relationship with pain: A systematic review and meta-analysis. *Pain, 166*(9), e150–e159. doi:10.1097/j.pain.0000000000003612.
