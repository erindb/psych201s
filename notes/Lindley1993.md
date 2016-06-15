<meta charset="UTF-8">

* Experiment: Binomial with 6 trials
  	* null: P(R)=0.5=P(W)
  	* likelihood of each outcome under the null is 1/64
* Technically then, each is "significant" since unlikely under the null
* So Fisher collapsed to combinations P(RRRRRW) = 6 choose 1 = 6/64 = 0.094 n.s.
* But the *most likely* event under the null is 50-50: p ≈ 0.5
* So Fisher further collapsed values and their more extreme entailments, since they're equivalent under the hypothesis. then p=0.109 n.s.
* But what if the experiment were Poisson (go until wrong)? Then p=0.031*.
* **[Q:]** This is kind of counterfactual-ish, and it's ultimately about the correct causal model, right?
* Anyway, if we model *the data* under the null and under the hypothesis, with a *prior* on the hypotheses, then we can sensibly compare them.
* **[Quote:]** "All evidence does is to change opinions: it does not create them."