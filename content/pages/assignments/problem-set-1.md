---
content_type: page
learning_resource_types:
- Assignments
ocw_type: CourseSection
parent_title: Assignments
parent_type: CourseSection
parent_uid: fed85a98-064c-2e2a-4378-f3f7549df9b8
title: Problem Set 1
uid: 1f279e32-1ff1-0437-6886-46f84e9ef313
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Problem Set 1 Answer Checker
----------------------------

Work on the assigned problems in the associated Problem Set PDF file, then use the problem set checker to find out if the answer was correct or incorrect. To check your answers put them in the appropriate box and click the 'Check' button. Every checker box can do arithmetic and calculate standard functions (see {{% resource_link 758ceee0-d290-5d7c-5072-7d458581a3b3 "calculator help" %}}). If you give decimal answers, give them to at least 3 decimal places.

As you work you should have pencil and paper handy for calculations and thinking!

Note: some questions ask for a formula. For the checker we ask you to plug a value into the formula. For your pset you still need to give the whole formula.

//DEBUG PARAMETERS //Because we don't show solutions for pset checkers we use //this to give a showanswer button during the debugging phase var debugans = undefined; //release //var debugans = kDebugAnswer; //debug problemNumber = 0; wl("\<h3>Calculator\</h3>"); writecalculator("psetcheckcalcid", "Calculate"); whr(kdivcol,kdivwid);

//Problem 1 problemNumber++; wl(problemheader(problemNumber)); wl(''); var s; var partName, problemName, buttonLabel, answerArray, correct; s = \["(i) Probability of two-pair:"\]; wl(s.join(' ')); wl(kp); partName = problemNumber + " (i)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", .047539, buttonLabel, 0.001, debugans); wl(kp); s = \["(ii) Probability of three-of-a-kind:"\]; wl(s.join(' ')); wl(kp); partName = problemNumber + " (ii)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", .021128, buttonLabel, 0.001, debugans); wl(kp); s = \["(iii) Which is more likely?"\]; wl(s.join(" ")); partName = problemNumber + " (iii)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; correct = "Two-pairs"; var answerArray = \[correct,"Three-of-a-kind"\]; writeMultipleChoiceRadioGroup(answerArray, problemName, correct, buttonLabel); wl(kp); whr(kdivcol,kdivwid);

//Problem 2 problemNumber++; wl(problemheader(problemNumber)); wl(kp); var s; var partName, problemName, buttonLabel, answerArray, correct; s = "(a.1) $P$(white beats green):" wl(s); wl(kp); partName = problemNumber + " (a.1)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", 0.58333, buttonLabel, 0.01, debugans); wl(kp); s = "(a.2) $P$(green beats red):" wl(s); wl(kp); partName = problemNumber + " (a.2)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", 0.69444, buttonLabel, 0.01, debugans); wl(kp) s = "(b) P(sum of white &nbsp; > &nbsp; sum of red):" wl(s); wl(kp); partName = problemNumber + " (b)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", 0.59028, buttonLabel, 0.001, debugans); wl(kp); whr(kdivcol,kdivwid);

//Problem 3 problemNumber++; wl(problemheader(problemNumber)); wl(kp); var s; var partName, problemName, buttonLabel, answerArray, correct; s = \["(a) Probability function. Using your answer for $n=5$, what is the probability the sequence of birthdays is 1, 2, 1, 2, 1?", kbr, "This is a very small number, so either give your answer in scientific notation, e.g. 6.28 \* 10^(-26), or as an exact formula, e.g. 8 + (1/5)^(24)"\]; wl(s.join(' ')); wl(kp); partName = problemNumber + " (a)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", Math.pow(1/365,5), buttonLabel, Math.pow(10,-15), debugans); wl(kp); s = "(b) " + knoonlinecheck; wl(s); wl(kp); wl(kbr); s = "(c.1) Exact formula for $P(A)$? Give your answer when $n=30$"; wl(s); wl(kp); partName = problemNumber + " (c.1)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", 0.079009, buttonLabel, .001,debugans); wl(kp); s = "(c.2) Smallest $n$ such that $P(A) > 0.5)$?" wl(s); wl(kp); partName = problemNumber + " (c.2)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", 253, buttonLabel, .01, debugans); wl(kp); s = "(d) " + knoonlinecheck; wl(s); wl(kp); wl(kbr); s = "(e) Smallest $n$ where $P(B) > 0.9$?" wl(s); wl(kp); partName = problemNumber + " (e)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", 41, buttonLabel, 0.01, debugans); wl(kp); s = "(f) Exact formula for $P(B)$. Give the value when $n=5$." wl(s); wl(kp); partName = problemNumber + " (f)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", 0.027136, buttonLabel, 0.001, debugans); wl(kp); s = "(g) Smallest $n$ for which $P(C) > 0.5)$?"; wl(s); wl(kp); partName = problemNumber + " (g)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; //answer is designed to accept 87 or 88 writeNumericBox(partName+"id", 87.5, buttonLabel, 0.8, debugans); wl(kp); s = "(h) " + knoonlinecheck; wl(s); wl(kp); wl(kbr); whr(kdivcol,kdivwid);