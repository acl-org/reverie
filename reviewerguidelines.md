---
layout: page_toc
title: "ARR Reviewer Guidelines"
permalink: reviewerguidelines
redirect_from: /reviewertutorial
---

The ARR peer review guidelines are a work-in-progress and will be updated as ARR evolves. Before starting an assignment, the reviewers should always check whether the version they are familiar with is still the current one. The biggest recent updates are marked with 🆕.

**Changelog:**

- _21.10.2024_ A major update based on ACL'23 edits (Anna Rogers, Jordan Boyd-Graber), internal ARR documentation, and [NeurIPS paper checklist](https://neurips.cc/public/guides/PaperChecklist). Includes new guidlines related to ACL [publication ethics](https://www.aclweb.org/adminwiki/index.php/ACL_Policy_on_Publication_Ethics) and [anonymity](https://www.aclweb.org/adminwiki/index.php/ACL_Anonymity_Policy) rules, guidance for requesting experiments involving closed-source LLMs, new section on common problems in NLP papers, and codes for common review issues that can be flagged by reviewers. Feedback from Michael White, Noah Smith, Mausam, Marzena Karpinska.
- _15.05.2024_ Anonymity policy updates
- _27.09.2023_ New reviewing page, AI question in the checklist. Comments and corrections by Aurélie Névéol, Amanda Stent, Sebastian Riedel, Preslav Nakov.
- _10.08.2023_ Instructions on access to old reviews
- _02.11.2021_ First version of this document (Anna Rogers, Isabelle Augenstein)

🆕 **Review issue reporting.** Starting in October 2024, ARR will now provide the authors with the opportunity to report common issues with reviews (e.g. rude reviews, 'not novel' criticism without providing references, etc.) The ACs will see such reports, if any, judge their merit, and take them into account when writing the meta-review. Since the reviewer guidelines are also used by the authors during the response period, some sections of these guidelines now have codes for review issues (<span class='reviewIssue'>I1</span>-<span class='reviewIssue'>I12</span>) that can be reported by the authors. More details [here](https://aclrollingreview.org/authors#step2.2).

# What are the confidentiality and anonymity rules for reviewing?

**All the information about submissions and reviews that you receive as part of your assignment is confidential.** This entails the following:

* If you participate in discussions of peer review on social media, please **make sure that your comments/examples are general enough that no submissions can be identified**, and the authors cannot identify you. Do not refer to individual papers. 
* **You should not submit any confidential information to third party services** that may retain and use that information. In particular that includes some popular generative AI services. See the [section on generative AI assistance in reviewing](#q-can-i-use-generative-ai).

**What about review data for research?** After the review process is completed, **anonymized review data can be provided to the research community, given the consent of the willing reviewers and authors**. ARR implemented a framework for proactive data collection from the willing reviewers and authors agreeing to contribute it. We hope that you would consider opting in. This is done in the form where you set your availability for review cycles. The more data we have, the more we can do as NLP experts [to improve peer review](http://arxiv.org/abs/2405.06563). 

**What about the author anonymity?** While [ACL has replaced the embargo period with other measures to incentivize anonymity](https://aclrollingreview.org/anonymity/), the reviewing guidelines are as follows:

> _To preserve the merits of double-blind review, reviewers for *ACL conferences and TACL should be instructed **not to actively try to discover the identity of the authors** and not to let any suspicion or knowledge of author identity affect their judgment of the paper. This should not prevent them from searching for related work, but they should take special care and **postpone such searches until after they have read the paper completely and formed an initial impression of it**. If a reviewer nevertheless uncovers the identity of the authors (or believes they can identify the authors for other reasons), they should inform the area chair or action editor (but not other reviewers) so that this information can be taken into account when making the final acceptance decision._

Hence, we ask for the following workflow: (1) read the paper and get the first impression, (2) search for related work, not deliberately trying to find that particular submission. If you become aware or can guess the authors' identity, you should disclose that in the ARR review form, which contains questions about the reviewers' knowledge of author identity. In [some cases](#expertise-and-coi-check-can-you-review-these-papers) it is appropriate to ask for a reassignment.

# How to get assigned to papers that match your interests well?

When you accept the invitation to review for ARR, please make sure that your **Semantic Scholar profile** is accurate and up-to-date. This information is **used in the automatic paper-reviewer matching**, so the more accurate it is, the more likely you are to get papers in your area. 

Your profile should also include a link to your **DBLP page** and **author page in ACL Anthology**. This information is **used to estimate your seniority and experience with *CL conferences**, used for automatic checks of reviewers who fulfill the [reviewing workload requirement](https://aclrollingreview.org/reviewing-workload-requirement/) for the authors. We are aware that for some authors with common names there are currently some disambiguation issues; in the future ACL Anthology plans to implement ORCID integration. 

Hence, after you have provided your Semantic Scholar ID and pulled in papers from DBLP, go through the papers listed in your profile. **Delete those that do not match your current expertise** (e.g. papers from long ago in areas in which you no longer work, papers that were for a side project). Also **delete any that you did not (co)author.**

# How do I do X in OpenReview?

We have a [tutorial](https://docs.google.com/presentation/d/1CkfR94WxEPEZEyCN--ydC7K3wY4g-5ZiFd2HM8LRSXg/edit#slide=id.gf84c08a109_0_55) for performing common actions on OpenReview: viewing your current tasks, adding reviews, participating in discussion, contacting ACs. We also have a post describing the [ARR review form](https://aclrollingreview.org/reviewform) in detail.

At any stage, you can view your pending tasks by logging in to OpenReview and opening the following link:

https://openreview.net/group?id=aclweb.org/ACL/ARR**/&lt;YEAR>/&lt;MONTH>**/Reviewers#reviewer-tasks

E.g. for NAACL 2024 cycle it is:

[https://openreview.net/group?id=aclweb.org/ACL/ARR/2024/October/Reviewers#reviewer-tasks](https://openreview.net/group?id=aclweb.org/ACL/ARR/2024/October/Reviewers#reviewer-tasks) 

# ✅ **TASK 1. Allocate time in your calendar for reviewing and discussion**

When you accept the reviewing request for an ARR cycle, there will be a kick-off email from OpenReview listing the important dates for this cycle. Usually the email subject is *[ACL RR-(MONTH)] Reviewing period starts ... (DATE)*. 

Please block the time in your calendar for (1) checking the assignments, (2) working on the reviews, and (3) submitting them on time. The kick-off email will contain the timeline for your review cycle. Late reviews mean extra work for the AC and other volunteers — and the authors might not get a fair chance to respond.

How much time will you need for reviewing? That varies by reviewer, paper, and experience. A way of estimating it would be to calculate what your average time for (a) skimming + in-depth reading of a paper is that is as close to your area as the submission, (b) writing and editing about half a page of an article. Ideally, this would be spread over a few days, because the first-impression draft may be tainted by a knee-jerk reaction to the paper's methodology or results. Then, during the discussion period, you need to set aside some time to check the authors' response, discuss and/or update the review as needed.

It would be a good idea to actually clock yourself doing the reviewing work from time to time, so that you know how long it takes (and how much variance there is), and plan accordingly next time.


# ✅ **TASK 2. Assignment check** 


## Expertise and COI check: can you review these papers?

As soon as you get an assignment, skim the paper to check whether this is **something that you are qualified to review**. The assignments are made based on a semi-automatic process, and, even with careful checks by the area chair, you may feel like you are not qualified to review a given submission.

Yet, even in the best-case scenario, the matches will not always be perfect. For very novel work or atypical papers, it is inherently difficult to find available qualified reviewers. The possibility of a very close match also depends on the set of people in the reviewing pool, therefore increasing the chances of a good match for the large, popular subfields. And even large subfields may experience a lack of well-matching reviewers when they are actively growing. Moreover, sometimes a less obvious match may also be a conscious decision on the part of the AC, e.g., to collect reviewers from different perspectives when the paper is interdisciplinary, or when it focuses on less popular topics and languages.

So, the bad news is that, realistically, you will sometimes be asked to review papers that are a bit outside of your own subfield. That is ok as long as you are sufficiently familiar with the core methodology and the kinds of arguments that are typically made in our field’s papers. If your expertise does not cover certain aspects of the submission, your review should specify that, and you will also be able to indicate your confidence score in the ARR form.

The good news is that the less-than-perfect matches also have upsides: you get to expand your repertoire, the authors get feedback on what needs more clarification/explanation, and NLP in general gets more intellectual exchange between subfields.

The second thing to check is whether **you know or can guess who the authors are**. Ideally, ARR peer review should be fully anonymous. The problem with implicit social biases is that they are unconscious; we may be 100% sure that we do not think worse of a paper just because it is written by someone from a group minoritized in computing research and that we are not predisposed to like papers coming from famous labs, but we cannot really trust our conscious selves. If you happen to know who the authors are from personal communication, social media or talks, the review form will contain a field for you to indicate whether you know who the authors are. If you believe that some case is particularly bad and may severely compromise your judgement (e.g. because of a conflict of interest (COI): you know the authors personally, have or will work with them, etc.), please [ask your AC](https://docs.google.com/presentation/d/1CkfR94WxEPEZEyCN--ydC7K3wY4g-5ZiFd2HM8LRSXg/edit#slide=id.gfd16cb95ca_3_0) for re-assignment if possible. 

> If you feel that you are qualified to review some aspects of the paper but not others (e.g. experimental results but not the formal proofs), **please state in the review if you did not check some major parts, such as proofs**. This information is helpful for the AC to tell what aspects of the paper were not reviewed.

The third check is on **academic conflicts of interest**. If the submission looks like something that is very close to your own work about to be submitted, it is best to recuse yourself.

If you feel that this submission is a very bad match on one of these criteria, please [contact your AC](https://docs.google.com/presentation/d/1CkfR94WxEPEZEyCN--ydC7K3wY4g-5ZiFd2HM8LRSXg/edit#slide=id.gfd16cb95ca_3_0).


## Reviewer checklist: should these papers be reviewed or desk-rejected?

Most of the desk rejects happen before the reviewing starts, because the program and area chairs do a cursory check for obvious issues prior to reviewer assignment. Still, only reviewers read the papers in-depth, and so they are also provided with a checklist to flag the problems that other people may have missed. For all your assignments you need to complete the [reviewer checklist](https://docs.google.com/presentation/d/1CkfR94WxEPEZEyCN--ydC7K3wY4g-5ZiFd2HM8LRSXg/edit#slide=id.g29396624085_0_10), which asks you to consider the following issues that may qualify a paper for desk rejection:


* **Appropriateness:** Is this submission appropriate for ARR? If in doubt, consider the scope described in [ARR CFP](https://aclrollingreview.org/cfp) and any relevant conferences (e.g. for October 2024 cycle the NAACL CFP specifies the special theme  ["NLP in a Multicultural World"](https://2025.naacl.org/calls/papers/).
* **Anonymity violations.** As of January 2024, non-anonymous pre-prints are permitted for ARR, but [submissions should still be properly anonymized](https://www.aclweb.org/adminwiki/index.php?title=ACL_Policies_for_Review_and_Citation) (e.g., not containing explicit references to the authors' prior work, acknowledgements, links to non-anonymous repositories or services like Dropbox that may track who opened the link). 
* **Style guides or length violations:** the paper should be desk-rejected if it does not follow the [style guides](https://acl-org.github.io/ACLPUB/formatting.html) or goes over the page limit (4 pages for short, 8 for long papers, excluding the ethical considerations and limitations).
* **Missing Limitations section**
* **Incorrect information in the [responsible NLP checklist](https://aclrollingreview.org/responsibleNLPresearch/).** E.g. some authors just say 'yes' for all questions, or for questions that do not even apply to their work (e.g. 'yes' to questions about human participants when their paper doesn't involve any). For now we ask you to flag it, and starting from December 2024 such violations will qualify for desk rejections. Minor honest mistakes can be excused (e.g. the information is provided in a different section than specified, due to some last-minute editing). 
* **Possible ethics issues.** Ethics issues are not grounds for desk rejection, but they can be grounds for sending the paper for an extra round of ethics reviewing. Here are the [guidelines](https://aclrollingreview.org/ethics-flagging-guidelines/) for identifying the kinds of papers that may need such an extra review.  \
If you flag a paper, you need to provide a justification. Otherwise, enter "None"

Additionally, papers are checked by ARR for the following:

* **Dual submissions.** As a rule, submissions to ARR are not supposed to be under review anywhere else (unless specific exceptions are made due to notification date overlaps). This check is done by ARR, but if we missed it, and you happen to have seen the same paper in a concurrent review cycle elsewhere — please let us know.
* **Extremely similar submissions.** Some authors send us submissions that significantly overlap in content. ARR checks for that, and it is not very likely that two such papers get assigned to the same reviewer. Still, if you see such papers — please let us know.

# ✅ **TASK 3. Write a strong review**

Check whether the paper is a resubmission: if so, it should have a link in the “Previous URL" field in the metadata, and it should point to the previous submission. If that's the case, refer to the [section on resubmissions](#how-to-review-resubmissions).

## 1. Adjust your expectations <span class='reviewIssue'>I6</span> <span class='reviewIssue'>I7</span>

One reading strategy that seems to be often used, but not well suited for peer review is commenting/critiquing *during* the first (and only) read. The problem is that any criticism is done from a certain perspective. If you don't adjust it, you are relying on your default perspective, which is likely formed by a 'prototype' paper in your own subfield. If your prototype is a long paper with experimental results, and you get something else, you might be biased against it for just not being the type of work that you expected. Hence, **please read the paper at least twice: skimming and in-depth reading.**

**1. Skim-reading: adjusting your expectations.**

* *What is the research question and what was done to answer it? Will the answer advance the field?* Do NOT look at the results yet. Hindsight bias may make things seem obvious in retrospect, and [confirmation bias](https://www.acpjournals.org/doi/abs/10.7326/0003-4819-116-11-958_2) may make you dismiss evidence that contradicts your beliefs. Remember that the goal of research is to contribute new *knowledge*.
* *If the methodology and the type of contribution in scope of the CFP?* NLP is an interdisciplinary field, and we might learn from papers that don't do the same thing we do. E.g. there was a case when a *CL reviewer criticized a resource paper as follows: ['the paper is mostly a description of the corpus and its collection and contains little scientific contribution'](https://rbawden.wordpress.com/2019/07/19/one-paper-nine-reviews/). This is particularly unfortunate when the modeling work has far outpaced the development of theory and documentation. Furthermore, given the sad state of replicability of NLP experiments, even in published papers, reimplementations and systematic analyses of prior work should be encouraged.
* *Is the claim appropriately scoped?* This applies to all papers, but especially to the short ones. They may present a proof of concept, an interesting finding, a convincing point, a negative result, and they are very easy to criticize with "it would be nice/more complete to add X". Such a criticism can be made for most papers. It is only valid if the argument that is being made depends on X.

**In-depth reading.** This is where you evaluate the evidence that is presented for its technical soundness, proof validity, sound argumentation, novelty, etc. How to do this best depends on the type of paper and your workflow.

**Should I check for related work?** Please do that carefully, and only *after* you've drafted your review. Many papers have non-anonymous preprints, and you may accidentally discover the identity of authors, which would open you up to social biases. Do NOT deliberately search for the preprinted version of the paper you were assigned.

**Do I have to read the appendices?** The paper should be readable by itself, and any details important for understanding the key aspects of the work should be in the paper rather than in appendices. The authors may provide supplementary material with extra experiments, implementation details, examples, code, or data, but you are not required to consider such material. However, if you happen to have a question about supplementary experiments, methodological details etc., and the paper explicitly refers to the appendix for more information about that specific issue — looking it up would save everybody’s time. Often, we see author rebuttals that simply refer the reviewer to the appendix for exactly the thing they asked for.  At the same time, if something has been relegated to the appendix that you, as a reviewer, believe belongs in the main paper, this is a reasonable suggestion to make to the authors to improve the paper (but not a serious weakness as such modifications are usually simple).


## 2. Be specific <span class='reviewIssue'>I1</span>

If you would like to flag any issues, it should be specific and ideally understandable to the chairs without reading the full paper. Let us consider a few examples.


<table>
  <tr>
   <td>❎ Instead of:
   </td>
   <td>✅ Use:
   </td>
  </tr>
  <tr>
   <td>The paper is missing relevant references
   </td>
   <td>The paper is missing references XYZ
   </td>
  </tr>
  <tr>
   <td>X is not clear
   </td>
   <td>Y and Z are missing from the description of X.
   </td>
  </tr>
  <tr>
   <td>The formulation of X is wrong
   </td>
   <td>The formulation of X misses the factor Y
   </td>
  </tr>
  <tr>
   <td>The contribution is not novel
   </td>
   <td>Highly similar work X and Y has been published<a href="https://www.aclweb.org/adminwiki/index.php?title=ACL_Policies_for_Submission,_Review_and_Citation"> 3+ months prior to submission deadline</a>
   </td>
  </tr>
  <tr>
   <td>The paper is missing recent baselines
   </td>
   <td>The proposed method should be compared against recent methods X, Y and Z (see H14 below for requesting comparisons to 'closed' systems)
   </td>
  </tr>
  <tr>
   <td>X was done in the way Y
   </td>
   <td>X was done in the way Y which has the disadvantage Z
   </td>
  </tr>
  <tr>
   <td>The algorithm's interaction with dataset is problematic
   </td>
   <td>It's possible that when using the decoding (line 723) on the dataset 3 (line 512), there might not be enough training data to rely on the n-best list. 
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td><em>[If reasonably well-known entities are discussed] </em> \
It’s possible that when using the decoding from Smith and Eisner (2006) on the Hausa newswire dataset, there might not be enough training data to rely on the n-best list.
   </td>
  </tr>
</table>


The advantage of the last version is that it can be understood by an area chair (who has expertise in the subarea) without looking for line numbers.



## **3. Check for common review issues** <span class='reviewIssue'>I2</span> <span class='reviewIssue'>I10</span>

Judging whether a research paper is “good” is an objectively hard task, and over the past conferences, we collected a list of common problems, which is presented below. Such comments *may* point at legitimate problems with the paper, but they are not always "weaknesses". This can happen even to experienced reviewers, and it's worth checking your review for these problems before submitting.


<table>
  <tr>
   <td><strong>Heuristic</strong>
   </td>
   <td><strong>Why this is problematic</strong>
   </td>
  </tr>
  <tr>
   <td>H1. The results are not surprising
   </td>
   <td>Many findings seem obvious in retrospect, but this does not mean that the community is already aware of them and can use them as building blocks for future work.  Some findings may seem intuitive but haven’t previously been tested empirically.
   </td>
  </tr>
  <tr>
   <td>H2. The results contradict what I would expect
   </td>
   <td>You may be a victim of confirmation bias, and be unwilling to accept data contradicting your prior beliefs.
   </td>
  </tr>
  <tr>
   <td>H3. The results are not novel
   </td>
   <td>If the paper claims e.g. a novel method, and you think you've seen this before - you need to provide a reference (note the policy on <a href="https://www.aclweb.org/adminwiki/index.php/ACL_Policies_for_Review_and_Citation"> what counts as concurrent work</a>). If you don't think that the paper is novel due to its contribution type (e.g. reproduction, reimplementation, analysis) — please note that they are in scope of the CFP and deserve a fair hearing.
   </td>
  </tr>
  <tr>
   <td>H4. This has no precedent in the existing literature
   </td>
   <td>Believe it or not: papers that are more novel tend to be harder to publish. Reviewers may be unnecessarily conservative.
   </td>
  </tr>
  <tr>
   <td>H5. The results do not surpass the latest SOTA
   </td>
   <td>SOTA results are neither necessary nor sufficient for a <em>scientific</em> contribution. An engineering paper could also offer improvements on other dimensions (efficiency, generalizability, interpretability, fairness, etc.) If the authors do not claim that their contribution achieves SOTA status, the lack thereof is not an issue.
   </td>
  </tr>
  <tr>
   <td>H6. The results are negative
   </td>
   <td>The bias towards publishing only positive results is a known problem in many fields, and contributes to hype and overclaiming. If something systematically does not work where it could be expected to, the community does need to know about it.
   </td>
  </tr>
  <tr>
   <td>H7. This method is too simple
   </td>
   <td>The goal is to solve the problem, not to solve it in a complex way. Simpler solutions are in fact preferable, as they are less brittle and easier to deploy in real-world settings.
   </td>
  </tr>
  <tr>
   <td>H8. The paper doesn't use [my preferred methodology], e.g., deep learning
   </td>
   <td>NLP is an interdisciplinary field, relying on many kinds of contributions: models, resource, survey, data/linguistic/social analysis, position, and theory.
   </td>
  </tr>
  <tr>
   <td>H9. The topic is too niche
   </td>
   <td>A main track paper may well make a big contribution to a narrow subfield.
   </td>
  </tr>
  <tr>
   <td>H10. The approach is tested only on [not English], so unclear if it will generalize to other languages
   </td>
   <td>The same is true of NLP research that tests only on English. Monolingual work on any language is important both practically (methods and resources for that language) and theoretically (potentially contributing to a deeper understanding of language in general).
   </td>
  </tr>
  <tr>
   <td>H11. The paper has language errors
   </td>
   <td>As long as the writing is clear enough, better scientific content should be more valuable than better journalistic skills.
   </td>
  </tr>
  <tr>
   <td>H12. The paper is missing the [reference X]
   </td>
   <td>Per<a href="https://www.aclweb.org/adminwiki/index.php?title=ACL_Policies_for_Submission,_Review_and_Citation"> ACL policy</a>, missing references to prior highly relevant work is a problem if such work was published (which is not the same as 'put on arXiv') 3+ months before the submission deadline. Otherwise, missing references belong in the "suggestions" section, especially if they were only preprinted and not published. Note that for resubmissions, papers are only required to make comparisons to highly related relevant work published at least three months prior to the <strong>original</strong> submission deadline.
   </td>
  </tr>
  <tr>
   <td>H13. The authors could also do [extra experiment X]
   </td>
   <td><span class='reviewIssue'>I10</span> It is always possible to come up with extra experiments and follow-up work. But <em>a paper only needs to present sufficient evidence for the claim that the authors are making</em>. Any other extra experiments are in the “nice-to-have” category and belong in the “suggestions” section rather than “reasons to reject.” This heuristic is particularly damaging for short papers. If you strongly believe that some specific extra comparison is required for the validity of the claim, you need to justify this in your review. 
   </td>
  </tr>
  <tr>
   <td>H14. 🆕 The authors should compare to a 'closed' model X
   </td>
   <td><span class='reviewIssue'>I10</span> Requesting comparisons to closed-source models is only reasonable if it directly bears on the claim the authors are making. One can always say "it would be interesting to see how ChatGPT does this", but due to <a href="https://hackingsemantics.xyz/2023/closed-baselines/">methodological problems</a> such as test contamination and a general lack of information about 'closed' models, such comparisons may not be meaningful. Behind this kind of remark is often an implicit assumption that scientific questions can only be asked of the “best” models, but pursuing many important questions requires a greater degree of openness than is offered by many of today’s “best” models. 
   </td>
  </tr>
  <tr>
   <td>H15. The authors should have done [X] instead
   </td>
   <td>A.k.a. “I would have written this paper differently.” There are often several valid approaches to a given problem. This criticism applies only if the authors’ choices prevent them from answering <em>their</em> research question, their framing is misleading, or the question is not worth asking. If not, then [X] is a comment or a suggestion, but not a “weakness.”
   </td>
  </tr>
  <tr>
   <td>H16. Limitations != weaknesses
   </td>
   <td>No paper is perfect, and most *CL venues now require a Limitations section. A good review should not just take the limitations and list them as weaknesses or reasons to reject. If the reviewer wishes to argue that acknowledged limitations completely invalidate the work, this should be appropriately motivated.
   </td>
  </tr>
</table>


If you have something like the above listed as a “weakness” of the paper, do try to revisit the paper with an open mind. Both the authors and the ACs will be aware of these guidelines and can refer to them in discussion/meta-review.



## 🆕 4. Check for common problems in NLP papers

As a counter to common problems with reviews, there are also common problems with NLP papers. We do ask you to watch out for these and point them out when you see them. Above all else, published research should at least be technically sound and appropriately scoped. As with the above reviewer issues, it's a case-by-case evaluation: some things in the list below may be appropriate in a given context, given that they are sufficiently motivated. We provide codes for different types of issues (e.g. M1, G2...) that can be referenced in discussions.


<table>
   <td colspan="2" ><b>Issues with methodology (M)</b></td>
<tr>
   <td>M1. LLM-only evaluation without validation
   </td>
   <td>If LLMs are used as automated evaluators, is their reliability <em>in this context</em> sufficiently validated? 
   </td>
   </tr>
  <tr>
   <td>M2. Reproducibility issues

   </td>
   <td>Are there enough details to reproduce the experiments, including hyperparameter selection? Is it clear whether the code/data/etc will be publicly available? If not, is that sufficiently motivated? If so, are they at least provided for reviewer evaluation? If you can't find this in the paper, check the authors' answers for the Responsible NLP checklist. You are not obligated to run the code, especially if it's computationally expensive, but you are welcome to do this to substantiate your assessment of the paper.  <br/>
Note: reproducibility score refers to <em>reproducibility</em> (being able to run the same experiment with roughly the same results) rather than <em>replicability</em> (getting similar results after reimplementation or on different models/data). Since reviewers are not obligated to run anything, the scope of ARR reproducibility score is to at least assess whether enough details/code is provided for reproducibility. 

   </td>
  </tr>
  <tr>
   <td>M3. Undisclosed data quality issues

   </td>
   <td>The papers that provide resources may be accompanied by full datasets or samples. You are <em>not</em> obligated to check this data. But you are welcome to, and if you notice issues that are not disclosed/discussed in the paper — this is a serious problem to bring up.

   </td>
  </tr>
  <tr>
   <td>M4. Unmotivated selection

   </td>
   <td>Any paper will have a limited number of models and benchmarks. But it should be clear why this sample was selected, and that motivation should be directly linked to the scope of the claimed contributions. You <em>may</em> feel that you would have selected a different sample, but that's ok, as long as the sample that the authors selected is appropriate for their claims.

   </td>
  </tr>

  <tr>
   <td>M5. Incomplete sets of assumptions or proofs

   </td>
   <td>All assumptions should be clearly stated. If the paper contributes formal statements (theorems, propositions, lemmas, corollaries), they should be supported by complete and correct proofs. Proofs can be delegated to appendices, as long as they are properly referenced in the main text of the paper.

   </td>
  </tr>

   <tr><td colspan="2" ><b>Issues with terms of artifact sourcing or release (T)</b>

   </td></tr>
   <tr><td>T1. Ethics issues with data collection

   </td>
   <td>If the paper involves annotation or data collection from humans, the responsible NLP checklist has relevant questions about ethics approval, compensation etc. Issues related to that are considered not by the main conference reviewers, but by ethics reviewers. If you feel that these are satisfactorily addressed, you can <a href="https://aclrollingreview.org/ethics-flagging-guidelines/">flag the paper for ethics review</a>.

   </td></tr>
  <tr>
   <td>T2. Unclear license / release terms

   </td>
   <td>If the paper contributes some artifact (e.g. a dataset or a trained model), is it spelled out under what terms it would be released? Note that such decisions may vary by jurisdiction. Your role is not to make legal judgments (especially from the point of view of your own institution), but to make sure that the authors are clear about what they are doing.

   </td>
  </tr>
   <tr><td colspan="2" ><b>Issues with experimental results (R)</b>

   </td></tr>
   <tr><td>R1. Analysis issues

   </td>
   <td>Inappropriate/misleading statistics or data presentation, p-hacking, presenting the 'best' results out of an unknown number of trials (including prompt tuning or engineering), baselines that are not sufficiently well-tuned for a fair comparison (including prompt tuning or engineering). 

   </td></tr>
  <tr>
   <td>R2. Inappropriate scope of the claims

   </td>
   <td>The authors evaluate a sample that does not represent the population about which the claim is made. E.g., a few QA benchmarks !="reasoning" or "understanding", LLMs of a certain size != LLMs.

   </td>
  </tr>
  <tr>
   <td>R3. Hypotheses/speculations presented as conclusions

   </td>
   <td>Every claim that is made has to be based on evidence or arguments (the authors' or from other work), or clearly marked as conjecture/speculation. 

   </td>
  </tr>
  <tr>
   <td>R4. Misleading or inappropriate framing, overclaiming

   </td>
   <td>E.g., concluding from benchmark evaluation that LLMs generally 'understand' language, without validating that construct.

   </td>
  </tr>
  <tr>
   <td>R5. Inappropriate or missing statistical significance assessment

   </td>
   <td>Ideally, at least the main experimental results should be accompanied by appropriate information about their statistical significance (error bars, confidence intervals, statistical significance tests), details about how this was computed, and discussion of factors of variability and any assumptions. Effect size estimation is also very welcome.

   </td>
  </tr>  
   <tr><td colspan="2" ><b>General issues (G)</b>

   </td></tr>
   <tr><td>G1. Unclear research question or contribution

   </td>
   <td>Is it sufficiently clear what <em>knowledge gap</em> the authors are addressing and what they contribute to it? The paper's contributions should be clearly stated in the abstract and introduction, along with any important assumptions and limitations. Aspirational goals can be included as motivation, as long as it is clear that these goals are not attained by the paper.

   </td></tr>
  <tr>
   <td>G2. Reliance on a bad precedent

   </td>
   <td>Sometimes methodology choices or arguments are motivated by appeal to precedent in previously published papers, and sometimes you may feel that that precedent is by itself not sound, or was disproved, or does not reflect the current best practice recommendations. In such cases, you are welcome to explain your position and discuss it with the author and other reviewers. Afterwards please update your review and explain clearly (for the authors and AC) why you changed your position or not.

   </td>
  </tr>
  <tr>
   <td>G3. Missing/misrepresented related work

   </td>
   <td>The authors are not expected to be aware of all the preprints within the past 3 months, but they are expected to be aware of work prior to that (at least the work that was reviewed and officially published). It is important that they fairly represent the contributions from the other work, and the respective novelty of their work. Note that (non-)reproduction studies <em>are</em> proper contributions in scope of ARR CFP, as long as they are appropriately presented.

   </td>
  </tr>
  <tr>
   <td>G4. Key terms too vague and not defined

   </td>
   <td>It is unclear what the authors mean by X, and they do not specify or reference their definition.

   </td>
  </tr>
  <tr>
   <td>G5. Misleading/incorrect citations

   </td>
   <td>The cited papers do not clearly say — or even contradict — what is attributed to them. This is a particularly worrying trend as more and more authors turn to LLM-generated summaries instead of reading the papers in question.

   </td>
  </tr>

</table>


## 5. Check that your scores reflect the review <span class='reviewIssue'>I3</span>

Look at your review and the numeric scores and check that your list of weaknesses actually justifies that score. If you give a low *Soundness* score without finding any major faults, this means that your review is not a faithful explanation of your recommendation. One reason for that could be that you secretly rely on some unconscious bias or heuristics for your evaluation, like the ones listed in the previous section.

Another reason why reviewers sometimes give "meh" scores without indicating serious problems is that they just do not find the topic interesting/exciting, even if the work is sound. If that is your main issue with the submission, it should be reflected in the "overall recommendation" rather than the soundness score.

Even then, do try to step away from your own research agenda. Of course, we cannot be equally enthusiastic about everything, but before giving a “meh” score, ask yourself: are there other people who would be excited about it, or who would benefit from this perspective?



## 6. Check that the tone is professional and neutral <span class='reviewIssue'>I4</span>

Above all, a good review should be professional and neutral, if not kind. A key goal of peer review is to help the authors improve their papers. As an anonymous reviewer, you are in a position of power, and the written medium makes it easier to be more dismissive and sarcastic than if you were communicating with the authors face-to-face. Unfortunately such reviews are [not uncommon](https://www.science.org/content/article/rude-paper-reviews-are-pervasive-and-sometimes-harmful-study-finds).

Consider that you may well be addressing someone who is only starting on the research path. And/or someone struggling with stress and other mental health issues. And/or someone who has been less lucky with their school and advisors. Academic lives are already stressful enough, and we do not need to inflict extra damage on the mental health of our colleagues with sarcastic or insulting reviews. [Write the review you would like to get yourself.](https://www.nature.com/articles/d41586-020-03394-y)

The fact is, authors and reviewers *are* actually the same people: the conference crowd lining up for coffee, happily chatting with each other about the grand problems even if they do not always agree. Why can’t we do peer review in the same spirit of fun intellectual interaction with colleagues?

Just like the conference coffee break chats, reviewing is in fact, mutually beneficial: in exchange for feedback, the reviewers get to have the first look at cutting-edge research. Just like the coffee breaks, where you do not necessarily meet only the people working in your subsubfield, peer review may expose you to new techniques. Since there is careful written communication in the authors’ response, you may even find that you were wrong about something, which is a much faster way to learn than making the same mistake in your own research.

Not to mention, someone out there is reviewing your papers too. The more rude or dismissive reviews there are, the more of a norm they become, and the higher the chances you will get one yourself in the future.


# ✅ **TASK 4. Update your assessment after the authors’ response and discussion** <span class='reviewIssue'>I11</span>


## Discussion with the authors

A core feature of OpenReview that was welcomed by many in *CL community is the author discussion period with the reviewers. While the reviewers are volunteers and cannot be obligated to participate, we strongly hope that you would **at least acknowledge the authors’ response**. You are probably well aware that, as an author, it is rather depressing to spend a lot of time carefully preparing responses to the reviews, only to see in the notification that the reviews did not change at all.


* If you do read the response and do not find it convincing, please at least acknowledge it. Then the authors will at least know that their response was not convincing (rather than just not read), and that is still useful information for improving their work. <br/> 
E.g., *Update: the authors responded, but none of the issues was addressed sufficiently to change this assessment. [ideally, say briefly what you found unconvincing]*
* If you find that at least some of your concerns were sufficiently addressed, please update the scores/text of your review. To make it clear what the changes are, please do not just edit the old review but add in the end a short statement.  <br/>
E.g., *Update: the issues with X and Y were resolved in the discussion, and I updated my scores*.
* If you would like to discuss something with the authors, you are encouraged to discuss for as long as there's time, but please keep in mind that the AC is unlikely to read very long discussions (we ask them to read at least top 2 author responses per reviewer thread). We recommend asking for clarifications on the most important points first so that this information is more likely to be noticed by the AC.


## Discussion with other reviewers

In ARR reviewer discussion happens throughout the process, i.e., both before reviews are sent to authors and after the authors respond. Any reviewer or the AC can initiate a discussion. Please respond and engage, particularly after the authors’ response has been submitted. The goal here is to catch any mistakes, misunderstandings, or violations of the reviewer guidelines.

**Possible influence of other reviewers.** When you see the reviews by the other reviewers, be aware that they may affect your own judgment in several ways because of social psychology effects. If you pointed out a weakness and then saw it also pointed out by someone else, you may feel it is a more severe problem than you originally thought. You may “discard” your own opinion if you see the opinion of someone you believe to be more senior/experienced/famous. If your original opinion was very positive, in the face of a strongly negative review, you may be tempted to “converge to the mean” (or the other way round). Ask yourself if this is really warranted, and whether this may be reflecting some core dispute between approaches/methodologies etc. Strong disagreements may be an indication that the paper is doing something unusual and interesting.

If the paper is a resubmission, see [below](#how-to-review-resubmissions).


# How to review resubmissions

Papers that are resubmissions have a link in the “Previous URL" field in the metadata, and it should point to the previous submission. 

If the authors decide to resubmit their paper to another cycle of ARR, they will have the choice to request the same or different reviewers. However, sometimes the same reviewers are not available when requested.  This leads to the following three types of reviewers for resubmissions (to be discussed in turn below):


* **Repeat:** If the authors requested the same reviewers, and these reviewers are available in the cycle, then they are repeat reviewers.
* **Substitute:** If the authors requested the same reviewers, but one or more of these reviewers is not available in the cycle, then new reviewers will be substituted for the unavailable ones.
* **Fresh:** If the authors requested different reviewers, then new reviewers will be assigned who will have a fresh perspective on the paper.

Note that in all three cases, consistent with [ACL policy](https://www.aclweb.org/adminwiki/index.php?title=ACL_Policies_for_Submission,_Review_and_Citation), resubmitted papers are only required to make comparisons to highly related relevant work published at least three months prior to the **original** submission deadline, though they are encouraged to discuss contemporaneous work where feasible.

## Repeat reviewers

If you are a repeat reviewer, you will see the authors’ revision notes, typically listing and discussing the changes they made in the new version of the paper. Starting from December 2024, ARR will require that authors include such a summary of revisions for resubmissions. You will need to reread the paper and comment on to what extent the authors successfully responded to the previous reviews. **Please indicate that you read their revision notes and say whether you feel weaknesses were adequately addressed or not.**

In your review, you should **refrain from raising new issues** that were not discussed in the first round of reviews — otherwise, if resubmissions get a new round of weaknesses identified, then authors will never be able to move forward with commitment.  The exception is when the revisions resulted in **contradictory findings** or questionable results not present in the first round of reviews.  

Note that it is because of this stage that it is of utmost importance that in the first review, you are very clear about what kinds of improvements you want and how much of a difference they would make. If the authors are asked to perform a lot of extra experiments, but you fundamentally dislike the paper to the extent that nothing they could do would considerably change your opinion, this is not a good use of everybody’s time and resources.


## Substitute reviewers

If you are substituting for one of the original reviewers, then you will not initially see the previous  reviews or the authors’ revision notes, though this may change in future cycles. (The current setup is intended to help ensure that when authors request different reviewers, the newly assigned reviewers take a fresh look at the paper.)  Nevertheless, as with the repeat reviewers case above, the aim here should be to avoid an endless cycle of paper resubmissions.  You should therefore proceed as follows:


1. After reading the paper, you should submit a draft review (following the guidelines elsewhere in these instructions), at which point you will gain access to the previous reviews and author revision notes (click on the "Previous URL" link in the submission metadata).
2. After reading the revision notes, you should consider whether the weaknesses you identified in your draft review represent (i) previously identified weaknesses that were not adequately addressed; (ii) newly raised issues that represent critical issues of soundness; or (iii) other newly raised issues.
3. With these categories in mind, you should then edit your draft review, where (i) you explain the reasons why the revisions did not adequately address previously identified weaknesses; (ii) you explain the reasons why newly raised issues represent critical issues of soundness; and (iii) you reframe any other newly raised issues as suggestions for improvement.


## Fresh reviewers

As a fresh reviewer, you should form your own opinion of the paper.  Note that you will not initially see the previous reviews or the authors’ revision notes (new in August 2023), but after you submit your review, you will gain access to the old reviews and the revision notes (click on the "Previous URL" link in the submission metadata).  At this point, you should check the revision notes to see whether any weaknesses in your review were previously identified, and if so, edit your review to explain why the revisions were not fully adequate to address the weaknesses in question.  You may also consider whether the previous reviews identified weaknesses that you hadn’t thought of, and if so, whether you agree that they represent serious concerns meriting inclusion in your review.

---

# FAQ


## Q: How can I ask a question not answered in this FAQ?

* For questions on how to use OpenReview to complete your tasks, please contact our Support Team  ([support@aclrollingreview.org](mailto:support@aclrollingreview.org));

* For technical difficulties, errors, and generally in case of suspicious behavior of the OpenReview system, please contact the Tech team ([tech@aclrollingreview.org](mailto:tech@aclrollingreview.org));

* For content-based questions (e.g., about the submissions themselves, doubts about reviewer tasks, etc.), please contact editors-in-chief at [editors@aclrollingreview.org](mailto:editors@aclrollingreview.org)


## Q: What should I do if I cannot complete my assignment due to a personal emergency?

If your ability to complete your assignments on time has been compromised due to a personal emergency, please reach out to your ACs and SACs as soon as possible by filling out the Emergency Declaration form on the page for each paper you are assigned to.  The ACs and SACs will then try to find an emergency backup reviewer for each paper.  Note that this creates extra work for everyone involved and may be detrimental to review quality, so you should only use this option in real cases of emergency. 


## Q: Should I flag this for ethics review?

The general program committee members are not expected to be ethics experts. If you see something that you think could be problematic, you can flag the paper to be reviewed by a dedicated ethics review team. Generally, reviewers should look for issues with use of data sets and how they were collected, potential abuse, and disadvantages for minority groups. Please consider the [ethics flagging guidelines](https://aclrollingreview.org/ethics-flagging-guidelines/) as needed. Many commonly asked questions relevant to the ethics review are a part of the [Responsible NLP checklist](https://aclrollingreview.org/responsibleNLPresearch/), and so the authors have already answered them for you as part of their submission. 

How do you tell if the authors' answers are satisfactory? There is no single number for what counts as "fair pay", nor a simple rule that would account for "legal grounds for data collection/processing". The laws and practices at the authors' home country and institution probably differ from yours, and it would be unfair to expect that the authors would follow exactly your own practice. So fundamentally, the authors make their case for what they did, and try to convince you that this was appropriate — similarly to all other aspects of paper review. That being said, the broad principles of the [ACM Code of Ethics](https://www.acm.org/code-of-ethics) need to be upheld, even for the authors from the countries that did not ratify the human rights convention. If you believe there may be a serious ethical issue, but you lack the expertise to evaluate it, you may flag the paper for a separate review process by the ACL ethics committee. They will make a recommendation as to whether the paper should be accepted, revised, or rejected on ethical grounds.

## Q: Can I use generative AI?

The following recommendations come from the [ACL policy on publication ethics](https://www.aclweb.org/adminwiki/index.php/ACL_Policy_on_Publication_Ethics#Reviewing).

 - The reviewer has to read the paper fully and write the content and argument of the review by themselves, subject to the secondary reviewer policy described above, and it is not permitted to use generative assistance to create the first draft. This requirement extends to the meta-review, and the reviewer has to write any meaningful argumentation in the meta-review by themselves.
- Generative assistance should be used responsibly. For instance, it is reasonable to use writing assistance to paraphrase the review, e.g. to help reviewers who are not native speakers of English. It is also reasonable to use tools that help to check proofs.
- Neither reviewers nor editors should upload a submitted manuscript or any part of it into a non-privacy preserving generative tool as this may violate the authors’ confidentiality and intellectual property rights and, where the paper contains personally identifiable information, may breach data privacy rights.
- This confidentiality requirement extends to the peer review report, as it may contain confidential information about the manuscript and/or the authors. For this reason, neither reviewers nor editors may upload their peer review report into a non-privacy-preserving generative tool, even if it is just for the purpose of improving language and readability.

The ACL publication ethics committee is currently developing a full process for investigating and taking action on scientific malpractice, similar to the process for investigating professional misconduct.

To add to the above points, the reviews that look like they were written by ChatGPT overall decrease the faith in the peer review process. According to [this study](https://openreview.net/forum?id=bX3J7ho18S), there is more generated text in 'reviews which report lower confidence, were submitted close to the deadline, and from reviewers who are less likely to respond to author rebuttals'. All these factors generally correspond to the type of unmotivated reviewer that, as authors, we would prefer to avoid. The increased ratio of such reviews also attunes the community to reviews that *sound* like they were generated. Generally, reviews are valued for their content rather than language, so your thoughts are more likely to be appreciated if they come in your voice (even if with linguistic imperfections).

**What about the authors, can they use generative AI?** The [ACL policy on publication ethics](https://www.aclweb.org/adminwiki/index.php/ACL_Policy_on_Publication_Ethics#Reviewing) discusses various cases with different degrees of acceptability. Note that the authors are obligated to disclose their use of generative AI, and there is a question about that in the end of the Responsible NLP checklist (search for 'E1').

## Q: How do I contact the area chair?

You can contact your AC either directly or through OpenReview (see the OpenReview [tutorial](https://docs.google.com/presentation/d/1CkfR94WxEPEZEyCN--ydC7K3wY4g-5ZiFd2HM8LRSXg/edit#slide=id.gf84c08a109_0_55)):

* To communicate through OpenReview, you should see a button labeled “Official Comment” at the top of the paper forum. Click on it to open a message form. For messaging exclusively the ACs, please select only “area chairs” in the “Readers” field of the form.
* To communicate through email, you can find the name of the AC on the “Paper Assignments” page in OpenReview, and click on their name. Their email will be anonymized on the OpenReview page itself (for privacy reasons), but you can often find it by clicking on the “Homepage” link or otherwise searching for their contact information by following the links in the profile.


## Q: Can I use a secondary reviewer?

Starting with the April 2024 cycle, we have rolled out a secondary reviewing feature. We understand that especially for more senior reviewers, having the ability to collaborate in reviewing the papers is convenient and helps train new reviewers. This mechanism may also be useful for the cases when a submission does not have enough qualified authors to satisfy the [reviewing requirement](https://aclrollingreview.org/reviewing-workload-requirement/), but the senior author has postdocs or other colleagues who could help.

The main reviewer is still responsible for submitting the work, including the review itself, in a timely manner. They are still the point of contact for ARR, and will receive all of ARR communication. They are responsible for the quality and the sustained engagement of the secondary reviewer after author rebuttal. 

There is a special 'Secondary reviewer' field in the review form that can be used to acknowledge the reviewer. It will not be visible to tje authors. Secondary reviewers will be added to the list of reviewers for that cycle after completion of the assignments. Conferences publish lists of their reviewers in the proceedings, and secondary reviewers can request reviewer certificates.

## Q: Why is peer review so inconsistent?

You may have heard of the NeurIPS experiments ([2014](https://arxiv.org/abs/2109.09774), [2021](https://blog.neurips.cc/2021/12/08/the-neurips-2021-consistency-experiment/)), in which the same papers were assigned to two sets of reviewers. Their results suggested that peer review is fairly reliable in rejecting the low-quality submissions, but for the rest, the final decisions of the two committees are at random chance level. This is obviously a frustrating situation for the authors, going through rounds of seemingly arbitrary rejections. Besides the noise in this process, there are many factors that could contribute to this situation, including the following:

* *Variance in reviewer experience and training.* Some inexperienced reviewers do not receive appropriate training.
* *Variance in understanding the evaluation rubrics.* Reviewers may differ in what counts as a "weakness" - a fundamental flaw or a lack of clarification experiment? Similarly,  how exactly should  the "overall recommendation" balance a reviewer's own interest in the topic with  the thoroughness of the research?
* *Implicit biases* that we all have due to our social and academic backgrounds. The same approach may receive different evaluation if it is tested on a popular or a niche task, on English or any other language, with focus on engineering or linguistic aspects, and if it had been preprinted by a well-known lab and has received much attention. In case of submissions that get deanonymized due to preprints and social media, we may also be biased in favor of well-known authors and/or widely-discussed papers.

These guidelines are a part of an effort to improve the overall quality of reviews at *CL conferences, aiming to address the above issues. We discuss the overall structure and philosophy of the process for first-time reviewers, clarify the ARR principles and the review form, and address some of the cognitive and social biases that undermine peer review. 

Note that reviewer guidelines address only the variance in the *review* process, not the acceptance decisions. Top-tier conferences usually have more high-quality submissions that receive good reviews than they can accept, and then the decisions are also motivated by space and quota constraints, and editorial priorities of the chairs. 🆕 See [sec. 7 of ACL'23 report](https://aclanthology.org/2023.acl-long.911/) for analysis of the effect of reviews, meta-reviews, and SAC recommendations on the final decision.

## Q: I think I should have heard from ARR, but I haven’t seen any emails. What’s going on?

It’s possible that the emails have been marked as spam – check your spam folder! ARR does not use email tracking: we know if email bounces, but we don’t know if you have seen a message.

## Q: What is the review report license agreement about? 

At ARR you can donate your peer review reports to an open public dataset of peer reviews and paper drafts (see our [blogpost on the data collection](https://aclrollingreview.org/datacollection) for details). You can contribute your data to the corpus via signing the review report license transfer agreement, which you can find in your [task log on OpenReview](https://openreview.net/tasks). You have to make this decision for each cycle and you donate all review reports of a cycle in bulk.

## Q: How are paper assignments determined? In particular, how are areas used? 
We generate an assignment automatically based on areas, prior work, and languages involved. We also try to ensure at least one reviewer is a non-student, and that no two reviewers are from the same institution. This assignment is checked by the AC, who changes reviewers as needed. Regarding areas, reviewers choose multiple areas that they have expertise in while authors choose a single area at submission time. We strongly encourage the matching algorithm to assign reviewers that match the area.


## Q: I no longer wish to be a reviewer for ARR. How can I withdraw myself from the pool? 
Please [contact the EICs](https://aclrollingreview.org/organization) to have yourself removed.

Q: How to Request a Max Load (and Declare Unavailability) in OpenReview

See [these guidelines](https://docs.google.com/document/d/1_UEnoQVl27vg-IGyHZlt09nfShZxSofef2GDXo2pipI/edit).


# Extra resources

**General peer review process**

* EACL 2021 tutorial on peer review, pt. II - The Actual Review (Karën Fort): [slideslive](https://slideslive.com/38955744), [slides](https://github.com/reviewingNLP/EACL2021T5/blob/main/EACL_2021_pt2_theActualReview.pdf)
* [ACL'23 program chair report](https://aclanthology.org/2023.acl-long.911/) has extensive statistics and analysis for different aspects of the peer review process at that conference, including the impact of reviewer and AC scores and various aspects of paper-reviewer matching on the final outcome

**General advice and reviewing philosophy**


* Advice on peer review from Mirella Lapata, Marco Baroni, Yoav Artzi, Emily M.Bender, Joel Tetreault, Ani Nenkova, Tim Baldwin: [https://acl2017.wordpress.com/2017/02/23/last-minute-reviewing-advice/](https://acl2017.wordpress.com/2017/02/23/last-minute-reviewing-advice/)
* A podcast interview with Noah Smith: [https://soundcloud.com/nlp-highlights/77-on-writing-quality-peer-reviews-with-noah-a-smith](https://soundcloud.com/nlp-highlights/77-on-writing-quality-peer-reviews-with-noah-a-smith)
* Rebekah Baglini and Christine Parsons on how to avoid harsh language in peer review: [https://www.nature.com/articles/d41586-020-03394-y](https://www.nature.com/articles/d41586-020-03394-y)

**Examples of good reviews**

* Two examples of peer review from NAACL 2018: [https://naacl2018.wordpress.com/2018/01/20/a-review-form-faq/](https://naacl2018.wordpress.com/2018/01/20/a-review-form-faq/)

**Reviewing specific aspects of papers**

* Jesse Dodge and Noah Smith on the reproducibility checklist: [https://2020.emnlp.org/blog/2020-05-20-reproducibility/](https://2020.emnlp.org/blog/2020-05-20-reproducibility/)
* EACL 2021 tutorial on peer review, pt. III - Reviewing Results Section (Kevin Cohen): [slideslive](https://slideslive.com/38955745), [slides](https://github.com/reviewingNLP/EACL2021T5/blob/main/EACL_2021_pt3_resultsSection.pdf)
* EACL 2021 tutorial on peer review, pt. IV - Reviewing Conclusion Section (Kevin Cohen): [slideslive](https://slideslive.com/38955752/), [slides](https://github.com/reviewingNLP/EACL2021T5/blob/main/EACL_2021_pt4_conclusionSection.pdf)

**Reviewing different types of papers**

* COLING 2018 review form for different paper types has great questions to ask yourself when reviewing engineering, resource, reproduction, survey and computational linguistics papers: [http://coling2018.org/paper-types/](http://coling2018.org/paper-types/)
* Anna Rogers. Peer review in NLP: reject-if-not-SOTA [https://hackingsemantics.xyz/2020/reviewing-models/](https://hackingsemantics.xyz/2020/reviewing-models/)
* Anna Rogers. Peer review in NLP: resource papers [https://hackingsemantics.xyz/2020/reviewing-data/](https://hackingsemantics.xyz/2020/reviewing-data/)

**Cognitive and social biases in peer review**

* Anna Rogers, Isabelle Augenstein. What can we do to improve peer review in NLP? [https://aclanthology.org/2020.findings-emnlp.112/](https://aclanthology.org/2020.findings-emnlp.112/)
* EACL 2021 tutorial on peer review, pt. V: Reviewer Biases (Anna Rogers): [slideslive](https://slideslive.com/38955745), [slides](https://github.com/reviewingNLP/EACL2021T5/blob/main/EACL_2021_pt5_biases.pdf)
* EACL 2021 tutorial on peer review, pt. VI: Anonymity in Peer Review (Anna Rogers): [slideslive](https://slideslive.com/38955746), [slides](https://github.com/reviewingNLP/EACL2021T5/blob/main/EACL_2021_pt6_anonymity.pdf)

**Ethics**

* NAACL 2021 Ethics FAQ: [https://2021.naacl.org/ethics/faq/](https://2021.naacl.org/ethics/faq/)
* EACL 2021 tutorial on peer review, pt. VII - Ethics and Reviewing (Aurélie Névéol): [slideslive](https://slideslive.com/38955747), [slides](https://github.com/reviewingNLP/EACL2021T5/blob/main/EACL_2021_pt7_ethics.pdf)
* Just what do you think you're doing, Dave? A checklist for responsible data use in NLP. [https://arxiv.org/abs/2109.06598](https://arxiv.org/abs/2109.06598)

**NLP tool assistance in peer review**

* Kuznetsov et al. (2024) What Can Natural Language Processing Do for Peer Review? [https://arxiv.org/abs/2405.06563](https://arxiv.org/abs/2405.06563) 
