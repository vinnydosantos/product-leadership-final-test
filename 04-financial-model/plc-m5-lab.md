# Master Product Financials & Strategic Bets, Module 5 Lab

## Make your evaluation and funding decision
- **What assumption is doing the most work? If this number is 20-30% off, what changes?:** The assumption that bid estimation increases Standard-to-Enterprise upsell from 6% to 8%. Across 400 accounts, that means 8 additional upsells, beyond the 24 expected at baseline. If the projected 8% rate is 25% lower, it becomes 6%, eliminating the assumed incremental upsell benefit entirely
- **What is the structural problem in this case? Look past the headline numbers for something that does not hold up on closer inspection.:** The case attributes all 32 upsells × $28,000 = $896,000 ARR to the feature, ignoring the 24 upsells already expected without it. Only 8 additional upsells could be attributed to the projected lift: at most $224,000 annual revenue uplift before subtracting displaced Standard revenue. The 2.4-month payback therefore does not hold. Even using $224,000, simple revenue payback is approximately 9.6 months ($180,000 ÷ [$224,000 ÷ 12]), assuming all additional contracts are active immediately. Actual payback must account for conversion timing, margins, AI operating costs, and churn. The case also does not explain why a feature included in Standard would cause customers to upgrade
- **Is the kill criterion complete and actionable? Does it name the consequence, or hand the decision back to the room?:** It names a threshold, deadline, and consequence: below 7% by the end of Q3 → pause the feature and reallocate Q4 engineering capacity. It is actionable rather than merely calling for reassessment.
However, it needs a named decision owner and a defined eligible-account cohort and measurement window. At 7%, the lift above baseline is only 4 accounts, or at most $112,000 annual uplift before deductions; reaching the threshold alone does not establish an attractive return
- **Your verdict: FUND / FUND WITH ONE CONDITION / DO NOT FUND. If a condition, name it; otherwise explain in one sentence.:** Do not approve the $180,000 build as presented: its return includes baseline conversions, its upgrade mechanism is unvalidated, and it would compete with Meridian’s field-adoption strategy without evidence sufficient to justify that trade-off

## Write your business case
- **The strategic bet. What specific outcome are you backing, who does it serve, and what is the mechanism that connects the product decision to a financial result?:** We are backing increased recurring use of Meridian by foremen at existing enterprise customers by reducing daily logs from 14 required fields to 4 essential inputs, reusing project data while preserving enterprise reporting requirements. The hypothesis is that lower reporting effort increases field participation, giving office teams more consistent project information and making Meridian more valuable at renewal. The financial return would come from reduced enterprise churn and retained subscription revenue; that link must be validated, rather than assuming greater usage automatically produces revenue
- **The assumptions. List the assumptions your case rests on, then rank them: which one, if wrong, most changes your conclusion?:** Ranked by how much they could change the investment decision; numerical inputs are illustrative assumptions.
1. Field adoption improves retention. Simpler daily logs reduce annual enterprise churn from 12% to 10%. This is the most critical assumption: if usage improves but renewal behavior does not, the modeled revenue benefit disappears.
2. Enough accounts can benefit before renewal. We can reach 400 existing enterprise accounts, each averaging $28,000 ARR, before their renewal decisions. The eligible population and contract values require validation.
3. Simplification removes work rather than shifting it. Four essential inputs, supplemented by existing project data, preserve reporting and compliance needs without creating additional office work.
4. Delivery economics hold. Development and validation cost $60,000, additional annual operating costs are $10,000, and retained revenue carries an 80% contribution margin before those added operating costs.
5. Timing supports the return. Adoption can be assessed within eight weeks, but financial benefits emerge over the first full renewal cycle after rollout—not immediately at launch.
- **The expected return. What does the bet generate and when? Express it at unit level (per customer) and at scale (what volume hits target).:** Per exposed enterprise customer: A churn reduction from 12% to 10%, at $28,000 ARR, generates $560 in expected annual retained revenue and $448 in contribution at an 80% margin.
Across 400 exposed customers: This equates to 8 additional retained accounts, $224,000 in annual retained revenue, and $169,200 in contribution after $10,000 of additional annual operating costs. After the $60,000 build cost, the modeled net benefit is $109,200.
Break-even volume: Approximately 157 exposed accounts at the assumed retention lift cover the $70,000 build-plus-first-year operating cost.
Timing: Adoption signals should emerge within eight weeks; revenue benefits accrue as customers renew over the first full renewal cycle after rollout. Cash payback depends on renewal and payment dates.
- **The kill criterion. Name the specific metric, threshold, timeline, and financial consequence that tells the team to stop. Actionable, not a conversation.:** Release $20,000 for an eight-week pilot and hold the remaining $40,000. At week eight, measure recurring daily-log use: the percentage of eligible foremen submitting logs in at least three of the preceding four weeks, compared with a concurrent comparable group using the existing workflow.
If the lift is below 15 percentage points, the Foundations Product Leader stops further development and rollout, cancels the remaining $40,000 allocation, and reassigns engineering capacity. An inconclusive result does not release additional funding.
This is a proposed adoption gate, not proof of the modeled retention benefit.

## Stress-test and finalize
- **Paste your finalized business case here.:** Meridian Foundations — Final Business Case
Strategic Rock: Simplify daily logs from 14 required fields to 4
All numerical inputs and thresholds are planning assumptions requiring validation.
The strategic bet
Increase recurring Meridian use among foremen at existing US enterprise customers by reducing daily logs to four essential inputs, reusing available project data while preserving enterprise reporting requirements.
Lower reporting effort should increase field participation and give office teams more consistent information. The financial hypothesis is that this added customer value reduces enterprise churn and protects subscription revenue. Greater usage is an early signal, not proof of improved retention.
The assumptions — ranked by sensitivity
1. Adoption improves renewal outcomes: Annual enterprise churn falls from 12% to 10%. If renewal behavior does not change, the modeled revenue benefit disappears.
2. Sufficient eligible reach: 400 existing enterprise accounts, averaging $28,000 ARR, receive the improvement before renewal. These are assumed enterprise figures, not the Standard-account population from the separate class case.
3. Simplification removes work: Required information can be reused or eliminated without compliance gaps or shifting manual work to office teams.
4. Costs and margin hold: One-time development and validation cost $60,000, additional annual operating costs are $10,000, and retained revenue carries an 80% contribution margin before those additional costs.
5. Benefits arrive at renewal: Adoption is measurable during an eight-week pilot; financial benefits emerge over subsequent renewals.
The expected return
Measure	Base-case estimate
Expected annual retained revenue per exposed account	$560
Contribution per exposed account before added operating costs	$448
Additional accounts retained across 400 exposed accounts	8
Annual retained revenue at scale	$224,000
Contribution after $10,000 annual operating costs	$169,200
Net contribution after also deducting the $60,000 build cost	$109,200


The model breaks even at approximately 157 exposed accounts with a two-point churn improvement, or a 0.78-percentage-point improvement across 400 accounts.
If the retention lift is 30% smaller, net contribution falls to $55,440. With no retention improvement, the full investment produces a $70,000 loss before any unmodeled costs.
These are annualized economics once the retention benefit is realized, not immediate launch returns. Cash payback remains unconfirmed until renewal dates, payment terms, rollout timing, and spending are established. No acquisition-cost benefit is included because this initiative serves existing customers.
The funding decision and kill criterion
Approve a maximum $20,000 all-in pilot, included within the $60,000 development estimate. It covers development, research, measurement, and incremental pilot support and operating costs. Reconcile these costs with the full model to avoid double counting. Hold the remaining $40,000.
Before launch, PM 1, Engineering, and Finance must confirm feasible scope, eligible users, comparison sites, sample requirements, and the rule for identifying an inconclusive result.
At week eight, measure the percentage of eligible foremen submitting daily logs in at least three of the preceding four weeks, compared with a concurrent comparable group using the existing workflow.
Stop further development and rollout if:
- The improvement is below 15 percentage points.
- The result is inconclusive under the agreed measurement plan.
- Essential enterprise records cannot be preserved.
The Foundations Product Leader cancels the remaining $40,000 allocation and reassigns engineering capacity. No pilot extension or spending beyond the cap is automatic.
If the pilot passes, funding remains frozen. By week ten, Product and Finance must present verified account economics, delivery costs, renewal timing, and evidence supporting a retention effect. Further funding requires executive-sponsor approval of a conservative case that covers the investment over an explicitly dated horizon. If the evidence is unavailable, close the current funding request.
Recommendation: Approve the $20,000 pilot only. It buys bounded evidence; expansion must earn a separate investment decision.
