# dpbe_l2_pre_registration

## Study Information

### Double Phonemic Boundary Effect in Bilinguals: a Replication Study with L2 Spanish Learners


### Description (optional)

Previous studies (Casillas & Simonet, 2018; Gonzales & Lotto, 2013; Gonzales, Heinlein, & Lotto, 2019) indicate that bilinguals exhibit a double phonemic boundary effect. These studies provide strong evidence for the existence of two language specific phonemic systems in the bilingual mind. This study contributes to prior findings by investigating whether the double phonemic boundary effect can be observed in late second language (L2) speakers when providing only conceptual cues.

*ADD 1/2 SENTENCES PER STUDY*


### Hypotheses 

### Hipothesis 1
Bilinguals cannot adjust their perceptual categorization across language contexts by switching between language-specific phonemic systems when they are only conceptually cued. 

### Hipothesis 2
Proficiency will have no effect on perceptual categorization across language contexts, i.e. more advanced L2 learners will perform similarly to beginner L2 learners.



## Design Plan

### Study type 

- Experiment - A researcher randomly assigns treatments to study subjects, this includes field or lab experiments. This is also known as an intervention experiment and includes randomized controlled trials.


### Blinding (required)

- Parcipants will not be aware of the purpose of the study.
- Researchers will be aware of the purpose of the study.



### Study design

The experiment is a two-alternative forced choice administered in two sessions with at least 24 hours between sessions. There will be one group of English L2 learners of Spanish with different L2 proficiency levels. Proficiency level will be measured through vocabulary size, using a computerized version of the LEXTale test on PsychoPy, and it will be considered a continuous variable. VOT will also be a continuous variable, ranging from -60ms to 60ms in 10ms intervals, including pre-voiced, short-lag, and long-lag VOTs. 

The study has a within-subject design, all participants will complete the same tasks in both modes (English and Spanish). Mode order will be counterbalanced, half of the participants will perform the first session in English and the other half in Spanish.


### Randomization

Participants will be randomly assigned to start with the Spanish or the English version of the experiment.



## Sampling Plan

### Existing Data 

- Registration prior to creation of data 

Pre-registration is occurring before data collection for the intended research. No previous existing data will be analyzed. This research will be confirmatory. The studies taken as reference are discussed right below.

Gonzales and Lotto (2013) cued their early Spanish-English bilinguals perceptually and conceptually in a forced-choice task in which participants had to select whether the pseudo-word containing a sound from the /b/ or /p/ continuum that they were hearing was Spanish or English. Gonzales et al. (2019) cued their early Spanish-English and early French-English bilingual participants only conceptually. In both studies, findings suggest that participants adjusted their phonemic identification boundary according to the language context. Casillas and Simonet (2018) expanded the population by adding beginner and advanced late L2 speakers. These participants were cued perceptually. They found that late bilingual speakers also show evidence of the double phonemic boundary effect, although this effect was more pronounced in more advanced late bilingual speakers.



### Sample size 

This study aims at replicating the results found in the aforementioned articles, and to collect data for an unexplored context: late L2 speakers only conceptually cued. In order to do so, new data will be collected following the same procedure as in prior studies from an adult L2 population on the east coast of the U.S. The population will consist of college-aged subjects, and they will participate as part of the grade for their Spanish courses or voluntarily. We will collect data from approximately 100 participants (L1 English, L2 Spanish) ranging from beginner to advanced proficiency.

### Data collection procedures 

Data collection will last approximately two weeks, and participants will complete the experiment individually at a computer lab in two sessions. There will be at least 24 hours between sessions. 
Participants will perform a two-alternative forced-choice task. For each trial, they will be presented aurally a syllable (paf – baf) from the voiced-voiceless continuum /b/-/p/, spanning from the pre-voiced VOT to long-lag VOT. Aural and written instructions will indicate  English or Spanish mode. The conceptual cue order will be counterbalanced across participants for the two sessions. There will be no extra sounds in the stimuli biasing the responses towards one language or the other. At the end of the first session, participants will fill in the proficiency test. The first session will last approximately 10 minutes and the second 5 minutes.


## Variables

### Manipulated variables (optional)

As in Gonzales, Heinlein, & Lotto (2019), we will manipulate the language context conceptually through the instructions. In one session, participants will be told that they will listen to the beginnings of two words in Spanish. In the other session, participants will be told that they will listen to words in English.


### Measured variables (required)

We will measure the perceptual categorization through a two-alternative forced-choice task in which participants have to indicate whether they hear ‘paf’ or ‘baf’ as they listen to the continuum previously described.



## Analysis Plan

### Statistical models (required)


Responses to the two-alternative forced-choice test will be analyzed. Since data is categorical (ba - pa), hierarquical models will be fit with a binomial distribution using the logit link function, using R (R Core Team, 2018) and the package 'lmer4'. We will include participant as a random effect. Mode and proficiency will be fixed factors. Finally, the criterion will be response to the VOT continuum. 

### Inference criteria (optional)


We will use p-values as indicators of main effects or interactions. The alpha level will be set at 0.05. We will also assess the goodness-of-fit for the models with marginal R^2 ( R^2 m, without mixed effects) and conditional R^2 ( R^2 c, with mixed effects).


### Data exclusion (optional)

We will exclude data according to the following criteria:

- Error during data collection
- Participant's lack of understanding or engagement during the task
