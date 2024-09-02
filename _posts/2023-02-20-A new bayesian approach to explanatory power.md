---
layout: posts
title: "A new bayesian approach to explanatory power"
description: "A new bayesian approach to explanatory power"
date: 2023-02-20T07:00:00-07:00
category: Epistemology
tags: Epistemology
---
![TE image](/images/ep3.jfif){: style="width:400px; float:center;"}

[Here](https://perrin-ay.github.io/epistemology/2022/12/02/Bayesian-accounts-of-explanatory-power.html){:target="_blank"}, I had introduced explanatory reasoning and explanatory power (EP). I went on to discuss Peirce’s three step inferential pattern (PI) that captures an intuitive sense in which we evaluate EP. I also covered Schupbach and Sprenger’s (S&S’s) proposal which offers a Bayesian approach to accounting EP in the context of PI.

And [here](https://perrin-ay.github.io/epistemology/2023/01/29/Against-Schupbach-and-Sprenger-s-bayesian-account-of-explanatory-power.html){:target="_blank"} I explored the role of surprise in EP within the inferential framework of PI, and following that posed my argument against S&S’s proposal.

Building on the aforementioned posts, I lay out my proposal in this article.

To recapitulate the conclusions I drew concerning the role of surprise in EP:

1) The agent's held beliefs for a given situation, set up her expectations for that situation, as beliefs provide reason to expect certain things and not others. 

2) Then the degree of surprise she finds in E is relative to those beliefs. 

3) The agent finds E surprising when those beliefs do not contain explanations of suitable EP over it and provide little to no reason to expect E.

Following the inferential pattern of PI, discovering a surprising E then consists in updating those previously held beliefs to include H which has suitable EP over E, and thereby reducing the surprise in E. So, primarily what changed with the conclusion of the inferential pattern in PI (and the successful reduction of surprise in E), is the agent's beliefs which updated to include the explanatory hypothesis H.  

Cast in Bayesian probabilistic terms, the agent's degrees of belief in H or the probability distribution which encodes her probability estimates in H have increased and that decreases the surprise in E. Even when the agent directly witnesses E, with degrees of belief in E equal to 1, her beliefs ( Bayesian beliefs) for the situation where and when she encountered E do not have the explanatory hypothesis H in high enough degrees of belief that would have rendered E expected. But updating her Bayesian beliefs by increasing her degrees of belief in H then lessens the surprise in E , since under H ( believing H with high degrees of belief), E is rendered as expected. 

In other words, the agent raises her degrees of belief in H,  P(H) ( probability estimates in H ), which then makes it reasonable for her to expect E and thereby reducing her surprise in E. Her degrees of belief in E are held at probability of 1 and remain unaffected.

*Aside: For an intuitive sense on how probabilities map onto beliefs in the Bayesian framework , let's briefly consider some aspects of probability distributions. The mode or peak of a probability distribution is where the probability mass is most concentrated. In terms of belief, the distribution encodes probability estimates over a set of states that the agent deems possible, where ‘states’ can be anything one might have degrees of belief about, and a sharply peaked distribution corresponds to a single state enjoying the highest degrees of belief. On the other hand, variance or dispersion marks the spread of probability mass in a distribution. High variance in a probability distribution represents a lack of confidence or belief in any particular state, as the probability mass is spread and distributed among all states. If an agent were to hold high degrees of belief in state s1, then the probability mass in the distribution is concentrated over s1. The agent's change in belief, say from state s1 to now strongly believing in s2, is represented by the shifting probability mass from s1 to s2 resulting in a high concentration of probability mass over s2, giving it a high probability estimate and high degrees of belief. Since probability distributions integrate to 1 ( probability estimates sum to 1), an increase in the probability estimates for a state indicates a decrease in probability estimates in other states under the distribution.*

In Lipton’s example , E= “tracks in the snow”, is directly witnessed with degrees of belief in E, P(E) = 1. But when E is encountered by an agent holding very high degrees of belief in H1 = “ no person walked this path” (and very low degrees of belief in H2 = “a person recently walked this path”),  E is surprising as it is inconsistent with her strongly held belief in H1 and gives her no reason to observe E. Following the inferential pattern of PI, upon surprise in E,  the agent updates her belief by increasing her degrees of belief in the hypothesis H2 that has EP over E and renders it “a matter of course” (and decreasing her degrees of belief in H1). Increasing her degrees of belief in H2 (a person recently walked this path) provides a powerful reason to observe E (tracks in the snow), thereby reducing her surprise in E.

Thus, I prima facie contend that the decrease in surprise in E is best captured not by the increase in the agent's degrees of belief in E, as purported by S&S, but in the increase in the degrees of belief in explanatory hypotheses like H, which have suitable EP over E and thereby reduce surprise in E by giving us reasons to expect it. Where S&S take surprise to be straightforwardly related to the agent’s degrees of belief in E, to quote S&S, “insofar as surprise is inversely related to expectedness, it is straightforwardly related to probabilities. Thus, if h decreases the degree to which e is surprising, we represent this with the inequality ```Pr(e) < Pr(e|h)```”, I present an account on the relationship between Bayesian belief probabilities and surprise within the inferential framework of PI, where surprise and reduction of it is not straightforwardly denoted in terms of the agent's degrees of belief in E, but in the agents degrees of beliefs in hypotheses concerning the states of the world that make is reasonable to expect to E.

My proposal avoids the problem caused by casting EP in terms of increase in the degrees of belief in E, which as discussed above already equal one. S&S’s proposal succumbs to this and also to a related problem of adjudicating surprise to all low degrees of belief instances of E. For example, if E were a set of numbers drawn in a lottery, then P(E) is very low since the probability of drawing a particular set of lottery numbers is very low, and our subjective degrees of belief in E ( those particular set of numbers drawn) is also very low. According to S&S’s proposal however, it would mandate a surprise in E, but in general we are not surprised at the set of numbers drawn in a lottery. By my account we are not surprised since our beliefs regarding the lottery and how they are conducted gives us reason to expect a random set of numbers in every drawing of the lottery.  

This introduces the Bayesian approach to formalizing PI and explicating EP in terms of reduction in surprise that I have in mind. In the forthcoming subsections I will forward a fuller Bayesian treatment of this in terms of prior probabilities, likelihoods, models, and marginal probability of E. I will explain how the inferential mechanism of PI can be depicted as Bayesian inference with update in belief from prior ( low degrees of belief in explanatory hypothesis H) to posterior ( high degrees of belief in H). 


## From background knowledge to Bayesian models 
The purpose of this subsection is to motivate Bayesian correlates to an agent's epistemic stance of beliefs and expectations. As noted earlier, the beliefs that an agent brings to bear for any situation represent her epistemic stance and set up her expectations regarding that situation. For example - adding some details to Lipton’s vignette to explain what I mean - concerning the situation of his private outdoor patio with the knowledge of fresh snowfall, Lipton’s may bring to bear beliefs of the kind “ patio is covered in snow”, since he knows that it has been snowing for several hours , and that “no person is walking about on his patio” since he knows its private and to his knowledge has never had trespassers. On the basis of these beliefs, if he were to look out onto his patio, he expects to see no stranger loitering about, and undisturbed snow on the patio grounds with no shoe prints.

Furthermore, it is trivially true that the beliefs and expectations one brings to bear in any given situation are relative to one’s background body of knowledge. Background knowledge mediates our beliefs and the relationship between our beliefs and expectations (Pritchard 2013). Considering the above rendition of Lipton's vignette again, admitting the information of fresh snowfall into his background knowledge, he brings to bear beliefs of the kind  “patio is covered in snow”. And since background knowledge also informs the relationships between his beliefs and expectations, the belief that “no person is walking about on the patio” gives him reason to expect “undisturbed snow on the patio grounds with no shoe prints”, given the background knowledge of what shoe prints look like in the snow, and that walking on snow leaves shoe prints etc. 

Cast in the Bayesian framework, background knowledge is implicitly built -in to subjective Bayesian probabilistic beliefs. This is because conditioning the probability of some hypothesis H on the agent’s background knowledge simply returns the subjective probability of H as the subjective probability of background knowledge P(k) is 1: ```P(H|k) =P(H)``` (Strevens 2006). But my concern with background knowledge in the foregoing passages is slightly different as it is meant to highlight the role of background knowledge in the selection of the set of hypotheses it informs in the form of beliefs for any given situation in an agent, along with its corresponding expected outcomes. For any situation, background knowledge of an agent is the basis for the following: the set of states of the world she believes possible for that situation; the states she believes to obtain at that time; the set of outcomes and observations she finds possible for that situation; how likely are these outcomes given the various states she believes possible; and which outcomes she expects given the states she believes to obtain.

In Lipton’s vignette ( the newer rendition of it in this section), the situation was that of “looking onto his patio” and his background knowledge was the basis for the following: the states he believes possible in this situation could be “patio is covered in snow”, “no person is walking about on his patio” , “someone is or has been loitering in his patio” and so on,  but holds belief in states “patio is covered in snow” and  “no person is walking about on his patio”. The set of possible outcomes could be “undisturbed snow on the patio grounds with no shoe prints”, “shoe prints in the snow” and so on, but he expects to see “undisturbed snow on the patio grounds with no shoe prints”, since he believes that states “patio is covered in snow” and “no person is walking about on his patio” obtain.

And these, the set of possible hypotheses concerning the states of world, along with their set of possible outcomes, find a direct correspondence in subjective Bayesian probability terms:  a set of possible states or hypotheses ‘h’; degrees of belief in h prior to encountering new data  denoted as the prior probabilities of h:  P(h); a set of possible outcomes or observations ‘e’; and the likelihood ```P(e|h)``` of outcomes given states, which represents how well the set of possible states explain the different possible outcomes. In other words, the likelihood represents the subjective probability of encountering an outcome given some state were true.  

In subjective bayesianism,  the set of all possible states h along with their set of possible outcomes/observations e that an agent brings to bear to a situation (based on her background knowledge) can be specified under the joint probability distribution P(e,h) which defines the agents probability distribution over all combinations of  h and e. The agent's joint distribution P(e,h) will be different for different situations and can be thought to represent the sum total of the agent's knowledge regarding a particular situation prior to encountering new data. It is the Bayesian correlate of the agent's epistemic stance concerning a particular situation and specifies the agent's beliefs and expectations for that situation. In Bayesian and computational cognitive science research of predictive processing (Clark 2015) and predictive coding (Hohwy et al. 2008) underwritten by variational schemes (Friston et al. 2007; Beal 2003; Winn & Bishop, 2005), the joint distribution P(e,h) is called the ‘model’ or the ‘generative model’ or the ‘forward model’ of the world that the agent brings to bear for a given situation and required when making Bayesian inference (Friston et al. 2006; Buckley et al. 2017).

This covers my discussions on the Bayesian correlates. To summarize this section, an agent's background knowledge determines her epistemic stance for any given situation. This can be enumerated as her beliefs and expected observations. The Bayesian correlate for this is the agent's joint probability distribution P(e,h) , also referred to as the agent’s model of the world she brings to bear for that situation, as it represents her knowledge on the set of possible states, set of possible outcomes and the probabilistic relations between them. In the next section I will discuss Bayesian inference and how it relates to the agent’s model.


## Bayesian inference 
Per the product rule of probability, joint probability P(e,h) can be decomposed as the product of the prior P(h) and the likelihood P(e|h):

```P(e,h) = P(e|h)P(h)```

Bayes' rule (Gillies 2000) tells us how we should update our beliefs over states h in the event of new data e1 ( where e1 is an observation in the agents set of possible observations e). The rule states that we should combine the priors P(h) and the likelihood of e1 given the set of possible states ```P(e1|h)```, to update prior beliefs ( prior probabilities)  in states to a posterior ( the revised or updated) beliefs ( posterior probabilities) in the states of the world:

```P(h|e1) = P(e1|h)P(h) / P(e1)```

Bayesian inference to posterior belief operationalizes over the joint probability distribution P(e,h) as it requires the agent’s knowledge on the set of possible states, set of possible outcomes and the probabilistic relations between them, for a given situation. This informs the numerator of the bayes rule, and we can calculate ```P(e1|h)P(h)``` for new data e1. 

Bayesian inference from prior to posterior probabilities in the states of the world, involves shifts in the probability mass (or the probability estimates) in the probability distribution over those states. Bayesian inference also results in updating the agent's joint probability distribution P(e,h) since her degrees of belief ( probability estimates) over states have changed. This makes intuitive sense since the joint distribution is taken to represent the agent's model of the situation, and encapsulates her beliefs, which after inference would undergo change. However, note that since Bayes’ rule requires the agent’s joint probability distribution of prior beliefs and likelihoods to operationalize inference, inference is still bounded within the set of possible states that were specified in joint distribution, i.e., the probability mass over states might shift with inference, but the set of possible states remain fixed. To summarize -  performing Bayesian inference requires the agent's model (P(e,h)), and inference updates the degrees of belief over states from prior to posterior and changes the agent's model in the process to reflect this update.

In the next section I will apply the foregoing Bayesian principles to Lipton’s vignette and find the measure of surprise and EP in terms of marginal probability of observation under model.

## Worked illustration of Lipton's vignettes for measuring surprise and explanatory power
Lipton’s model ( or his joint probability distribution of all h and e) for the situation of his patio grounds after fresh snowfall can be formulated as given in figure 1. As a matter of convenience, and while remaining consistent with the vignette, I assume only two possible hypotheses and two possible observations. Prior to looking onto his patio grounds, Lipton holds the strong belief in hypothesis h1 ( No person walked this path) and this gives him reason to expect the observation of e1 ( no shoe tracks in the snow). Setting this up in Bayesian probabilities  corresponds to the prior probability distribution over states h ( prior to encountering new data) with almost all probability mass concentrated over h1. Numerically, I take the probability of h1 to be 0.9, thereby assigning high degrees of belief in h1l. The numerical assignments of likelihoods that I take in his model are self-explanatory, I take the probability of observing “no shoe tracks in the snow” , given ” no person walked this path”  to be high and equal to 0.9, the probability of observing “no shoe tracks in the snow” , given ” some person recently walked this path”  to be low and equal to 0.1, and so on. For all combinations of likelihoods, see figure 1.

![Figure1](/images/fig1.png){: style="width:400px; float:center;"}

Figure 1: Lipton’s model concerning his patio prior to encountering the tracks in the snow.

Lipton vignette expressed as the inferential pattern of PI looks like:

1)The surprising fact, e2=”shoe tracks in the snow, is observed”;

2)But if h2=”some person recently walked this path” were true, e2 would be a matter of course, 

3)Hence, there is reason to suspect that h2 is true

To determine whether the observation of e2 is surprising, we can calculate the marginal probability of e2 (observing tracks in the snow) under Lipton’s model (from figure 1)

Using the sum and product rule of probability, the marginal probability is calculated using the joint probability distribution and then summing over all hypotheses/states under the model.

```P( e=e2=shoe tracks in the snow) = ∑hP(h,e=e2) ( where  ∑h  stands for sum over all states h)
= ∑hP(h)P(e=e2|h)
=P(h1)P(e2 | h1) + P(h2)P(e2 | h2 )
= 0.9x0.1 + 0.1x0.9
=0.18```

The marginal probability of observation e2 under Lipton’s model in figure 1, also called its model evidence for e2 (Anderson, D., & Burnham, K. 2004) is only 0.18. This means that under this model Lipton would only expect to observe “shoe tracks in the snow” 18 times out of 100 observations. Thus, we can surmise that this observation is surprising. By bringing this model to the situation of the patio grounds after fresh snowfall, Lipton is left surprised as the model does a poor job of explaining what he sees. Lipton’s model which holds high degrees of belief in hypothesis h1 “No person walked this path”  has poor EP over e2 “shoe tracks in the snow” and provides little to no reason to expect e2. 

To quantify this measure of surprise, we can borrow the information theoretic notion of surprisal (Mackay 2003) which is just the negative log marginal probability of an observation under the model. Measuring surprise this way is intuitively appealing since a low numerical value of the marginal probability generates a high numerical value of surprisal and vice versa 

Surprise in observing e2 = -ln(P( e=e2=shoe tracks in the snow))
= -ln(0.18)
= 1.7 bits ( the units of the numerical value of surprisal are bits when the log is taken with base 2 and denoted by ‘ln’)

The larger the numerical value of surprisal in an observation , the lower is its marginal probability under the model and worse is the EP of the model over the observation, where the EP of the model corresponds to the EP of the hypotheses held in high degrees of belief ( prior probabilities) in the model. 

Continuing with Lipton's vignette expressed in the inferential pattern of PI, after encountering the surprising observation of e2 “shoe tracks in the snow”  Lipton’s updates his belief over states to hypotheses to h2 “some person recently walked this path” ( in step 2 and 3 of PI). In Bayesian terms this corresponds to shifting the concentration of probability mass from h1 to h2 in the probability distribution over states. In other words, increasing his degrees of belief in h2. Since probabilities need to sum to 1 in a probability distribution, increase in degrees of belief in h2 will also decrease the degrees of belief in h1. As I noted in the previous subsection, updating beliefs in states also brings about a change in the agent’s model (or joint distribution P(e,h)). Figure 2 represents this new model of Lipton’s after inference to h2. 

![Figure2](/images/fig2.png){: style="width:400px; float:center;"}

Figure 2: Lipton’s model after encountering “shoes tracks in the snow” and inferring to “some person recently walked this path” by raising his degrees of belief in it.  

Calculating marginal probability of e2 under Lipton's new model in figure 2: 

```P( e=e2=shoe tracks in the snow) = ∑hP(h,e=e2)
= ∑hP(h)P(e=e2|h)
=P(h1)P(e2 | h1) + P(h2)P(e2 | h2 )
= 0.1x0.1 + 0.9x0.9
=0.82```

Under the new model, the marginal probability of observing the e2 is much higher as under this model which encapsulates high degrees of belief in “some person recently walked this path” Lipton expects to observe “shoe tracks in the snow”  82 times out of 100 observations. 

The measure of surprise in e2 under the new model is:

Surprise in observing e2 = -ln(0.82)
= 0.19 bits

Lipton updates his belief over states by increasing his degrees of belief in h2, and by virtue of belief update, updates to a new model for the situation. Under the new model, high degrees of belief in h2 “some person recently walked this path” has EP over e2  “shoe tracks in the snow” and provide a powerful reason to observe it. This reduces his surprise in e2 from 1.7 to 0.19 bits. The degrees of belief over state h is the only difference between the two models and the reduction of surprise in e2 directly corresponds to the increase in the degrees of belief and probability estimates in h2.


## Concluding remarks
Lipton is surprised because his prior beliefs that make up his model do not have EP over e2  “ tracks in the snow” and provide little to no reason to expect it. Updating his model , by increasing the degrees of belief in h2 “ some person recently walked this path”, Lipton reduces his surprise in e2 since his updated Bayesian belief (posterior with high probability mass over h2) has EP over it. 

The reduction of surprise in e2 (tracks in the snow) was not due to an increase in Lipton’s actual degrees of belief in it, as S&S assert. Contrary to what S&S claim, upon seeing e2, Lipton knows that e2 with degrees of belief in e2 = 1. The reduction of surprise in e2 is from the changes in the probability distribution of states/hypotheses in his model, i.e., the increase in degrees of belief in state h2, that makes it reasonable to observe e2. 

Given my Bayesian approach, the inferential pattern in PI could be reformulated as:

1) If the marginal probability of E under the agent’s model is low, surprise in E is registered. 

2) But if the agent’s model is updated by increasing the probabilities estimates in hypothesis H, then E would be expected and a matter of course. 

3) Hence, there is reason to suspect that H is true and update our model to reflect high degrees of belief in H

And strong analogies can be drawn between my Bayesian approach and what is actually expressed in PI. Peirce notes a surprising ‘fact’ E is observed, suggesting that we know E as a fact that obtains. And the 2nd and 3rd steps in PI address taking the explanatory hypothesis H (which has EP over E) to be true and adopting it, to reduce surprise in E, which corresponds to my approach of locating the lessening of surprise with the increase in the degrees of belief in H and adopting it in ones model. 

For S&S the inequality ```P(E) <P(E|H)``` formalizes the condition expressed in PI that must be met if H were to have EP over E. I have argued that this formalization in terms of the agent's degrees in belief in E, is problematic. Based on my Bayesian probabilistic approach to PI , the condition expressed in PI that must be met if H were to have EP over E, is the marginal probability of E under a model with low degrees of belief in H <  marginal probability of E under a model with high degrees of belief in H. Formulaically this could be represented as:

 ```∑hP(h,e=E) < ∑hP(h,e=E)H```

Where P(h,e=E)H with the subscript H stands for the agent’s model for observation E and high degrees of belief in H, and P(h,e=E) without subscript H stands for the agent’s model for observation E and low degrees of belief in H. 
  
[Here](https://perrin-ay.github.io/epistemology/2022/12/02/Bayesian-accounts-of-explanatory-power.html){:target="_blank"}, I had introduced  EP as the strength or quality of a hypothesis H to explain an explanandum E and as the measure of its explanatoriness over E.

Translated in my Bayesian approach for PI, the measure of EP of H over E is simply the marginal probability of E under a model with high degrees of belief in H.

Formulaically:

```EP(H over E) =  ∑hP(h,e=E)H```


## Corollary: Explanatory reasoning in the context of trigger
Philosophers have traditionally referred to explanatory reasoning as “abduction” or as “inference to the best explanation” (IBE) and have debated about the appropriate place for explanatory considerations in reasoning. One camp has argued for its proper place in the “context of discovery”, where explanatory considerations function to generate (discover) a shortlist of candidate hypotheses, worthy of further assessment, and they call this abduction (Frankfurt 1958;Peirce 1934; Schruz 2008). The inferential pattern of PI falls in this camp. The other camp has argued for its place in the “context of justification”, where explanatory considerations justify inference to the true ( or probably true) hypothesis, a unique and best explanation that is sufficiently good and provides a better explanation than all the alternatives. They call this IBE (Harman 1965; Lipton 2004;Psillos 2002). 

But philosophical literature on explanatory reasoning generally takes the explanandum for granted. Discussions on explanatory reasoning and EP in the contexts of discovery and justification are concerned with the particular notion of EP that underwrites inference to explanans for already established explanandum’s. In either context, EP is solely located in driving inference to explanans as a reaction to a given and assumed explanandum. This was the case with PI as well where the inferential three-step pattern begins with surprise in E that is taken for granted and the notion of EP is only concerned with inference to reduce this surprise. S&S’s paper was also focused on explicating this notion of EP assuming surprise as a given. 
 
However, my Bayesian probabilistic analysis of PI does not take surprise for granted or the explanandum as a given. Following PI, this series of articles explicated an account of surprise as a function of the agents measure of EP, where the degree of surprise in E determines whether E qualifies as an explanandum or not.

A summary of how we get to measure surprise as a function of EP and determine whether some encountered fact is an explanandum as discussed in this and previous articles is as follows:

1) Surprise in an encountered fact E is subjective and determined by the agent's held beliefs representing her epistemic stance and expectations just prior to encountering E.
   
2)The agent finds E surprising and thus an explanandum requiring explanation, when her held beliefs just prior to encountering it, do not contain explanations of suitable explanatory power over it.

3)Based on my Bayesian probabilistic treatment of PI, surprise in E is occurrent  when the agents model encapsulates high degrees of beliefs in hypotheses that have little to no EP over E.

4)The EP of the agent model over E is expressed as the marginal probability of E under that model, where a low numerical value of this quantity corresponds to the poor EP of hypotheses held in high degrees of beliefs in that model, over E.

5)I quantify the measure of surprise as the negative log transformation of marginal probability of E under the agent’s model. A high value of this surprisal quantity represents a high degree of surprise in E and may qualify E as an explanandum.

I do not contend that the measure of surprise in E qualifies E as an explanandum generally , but that it captures at least one familiar sense on how we detect explanandum’s.

Thus, by my account we find explanatory reasoning and our evaluations of EP guiding the measures of surprise and inference to whether encountered facts qualify as explanandum’s. So, then prima facie this is evidence that besides the context of discovery and justification which take explanandum’s for granted and as a given, explanatory reasoning and our evaluations of EP also finds a third proper place which is in evaluating and measuring surprise and determining whether some encountered fact counts as an explanandum. I call this third context of explanatory reasoning the “context of trigger” and in this context the EP is simply given by the foregoing point #4. Formulaically it is:

 ```∑hP(h,e=E)```, and represents the EP of the agent’s hypotheses held in high degrees of belief just prior to encountering E.


## Bibliography

Aliseda, A. (1997). Seeking explanations: Abduction in logic, philosophy of science and artificial intelligence. Ph.D. thesis, Stanford University

Anderson, D., & Burnham, K. (2004). Model selection and multi-model inference. Second. NY: Springer-Verlag, 63(2020), 10.

Beal, M. J. (2003). Variational algorithms for approximate Bayesian inference. University of London, University College London (United Kingdom).

Bovens, & Hartmann, S. (2003). Bayesian epistemology / Luc Bovens and Stephan Hartmann. Clarendon Press.

Buckley, C. L., Kim, C. S., McGregor, S., & Seth, A. K. (2017). The free energy principle for action and perception: A mathematical review. Journal of Mathematical Psychology, 81, 55-79.

Clark, A. (2015). Surfing uncertainty: Prediction, action, and the embodied mind. Oxford University Press.

Cohen, M. P. (2015). On Schupbach and Sprenger’s measures of explanatory power. Philosophy of Science, 82(1), 97-109.

Crupi, V., & Tentori, K. (2012). A second look at the logic of explanatory power (with two novel representation theorems). Philosophy of Science, 79(3), 365-385.

Douven, I. (2022). The art of abduction. MIT Press.

Douven, I., & Mirabile, P. (2018). Best, second-best, and good-enough explanations: How they matter to reasoning. Journal of Experimental Psychology: Learning, Memory, and Cognition, 44(11), 1792.

Eells, E. (1982). Rational Decision and Causality. Cambridge: Cambridge University Press.

Eva, B., & Stern, R. (2019). Causal explanatory power. The British Journal for the Philosophy of Science.

Frankfurt, H. G. (1958). Peirce's notion of abduction. The Journal of Philosophy, 55(14), 593-597.

Friston, K., Kilner, J., & Harrison, L. (2006). A free energy principle for the brain. Journal of physiology-Paris, 100(1-3), 70-87.

Friston, K., Mattout, J., Trujillo-Barreto, N., Ashburner, J., & Penny, W. (2007). Variational free energy and the Laplace approximation. Neuroimage, 34(1), 220-234.

Gillies. (2000). Philosophical Theories of Probability. Routledge. https://doi.org/10.4324/9780203132241

Glass, D. H. (2007). Coherence measures and inference to the best explanation. Synthese, 157(3), 275–296

Glass, D. H. (2018). An evaluation of probabilistic approaches to inference to the best explanation. International Journal of Approximate Reasoning, 103, 184-194.

Good, I. J. (1960). Weight of Evidence, Corroboration, Explanatory Power, Information and the Utility of Experiments. Journal of the Royal Statistical Society. Series B (Methodological) 22(2), 319–331.

Harman, G. H. (1965). The inference to the best explanation. The philosophical review, 74(1), 88-95.

Hohwy, J., Roepstorff, A., & Friston, K. (2008). Predictive coding explains binocular rivalry: An epistemological review. Cognition, 108(3), 687-701.

Klahr, D., & Masnick, A. M. (2002). Abduction, reason, and science: Processes of discovery and explanation.

Koslowski, B. (2017). Abductive reasoning and explanation. In The Routledge International Handbook of Thinking and Reasoning (pp. 366-382). Routledge.

Koslowski, Marasia, J., Chelenza, M., & Dublin, R. (2008). Information becomes evidence when an explanation can incorporate it into a causal framework. Cognitive 
Development, 23(4), 472–487. https://doi.org/10.1016/j.cogdev.2008.09.007

Lipton, P. (2003). Inference to the best explanation. Routledge.

Lipton, P. (2004). Inference to the best explanation (2nd ed.). London: Routledge.

Ma, M., & Pietarinen, A.-V. (2016). A Dynamic approach to an interrogative construal of abductive logic. IfCoLog Journal of Logics and their Applications, 3(1), 73–104.

MacKay, D. J., & Mac Kay, D. J. (2003). Information theory, inference and learning algorithms. Cambridge university press.

McGrew, T. (2003). Confirmation, Heuristics, and Explanatory Reasoning. British Journal for the Philosophy of Science 54, 553–567.

Mirabile, P., & Lombrozo, T. (2019). Explanatory considerations guide pursuit. Proceedings of the 41st Annual Conference of the Cognitive Science Society . Montreal, QC: Cognitive Science Society.

Okasha. (2000). Van Fraassen’s critique of inference to the best explanation. Studies in History and Philosophy of Science. Part A, 31(4), 691–710. https://doi.org/10.1016/S0039-3681(00)00016-9

Peirce, C. S. (1934). The collected papers of charles Sanders Peirce (Vol. 5). Cambridge, MA: Harvard University Press.

Popper, K. R. (1959). The Logic of Scientific Discovery. London: Hutchinson

Pritchard, D. (2013). What is this thing called knowledge?. Routledge.

Pritchard. (2017). Epistemic angst : radical skepticism and the groundlessness of our believing / Duncan Pritchard. Princeton University Press.

Psillos, S. (2002). Simply the best: A case for abduction. In A. C. Kakas & F. Sadri (Eds.), Computational logic: Logic programming and beyond, Vol. 2408 of lecture notes in computer science (pp. 605– 625). Berlin: Springer.

Schupbach, J. N. (2011). Comparing probabilistic measures of explanatory power. Philosophy of Science, 78(5), 813-829.

Schupbach, J. N. (2017). Inference to the best explanation, cleaned up and made respectable. Best explanations: New essays on inference to the best explanation, 39-61.

Schupbach, J. N., & Sprenger, J. (2011). The logic of explanatory power. Philosophy of Science, 78(1), 105-127.

Schurz. (2008). Patterns of Abduction. Synthese (Dordrecht), 164(2), 201–234. https://doi.org/10.1007/s11229-007-9223-4

Sprenger, & Hartmann, S. (2019). Bayesian Philosophy of Science. Oxford University Press, Incorporated.

Strevens. (2006). Bayes, Bayes’ Theorem, Bayesian Approach to Philosophy of Science. In Encyclopedia of Philosophy (Vol. 1, pp. 495–502).

Ströing, P. (2018). Data, evidence, and explanatory power. Philosophy of Science, 85(3), 422-441.

Thagard, P. (1989). Explanatory coherence. Behavioral and brain sciences, 12(3), 435-467.

Winn, & Bishop, C. (2005). Variational Message Passing.










