---
content_type: page
learning_resource_types:
- Readings
ocw_type: CourseSection
parent_title: Readings
parent_type: CourseSection
parent_uid: 579c055a-ccb4-eb7e-bb6b-f294146b45a5
title: Reading Questions 3
uid: d5b22a13-5c6c-59b0-d2d8-2ac7256c5565
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Reading Questions Answer Checker
--------------------------------

To check your answers put them in the appropriate box and click the 'Check' button. Every checker box can do arithmetic and calculate standard functions (see {{% resource_link 758ceee0-d290-5d7c-5072-7d458581a3b3 "calculator help" %}}). If you give decimal answers, give them to at least 3 decimal places.

As you work you should have pencil and paper handy for calculations and thinking!

Note: some questions ask for a formula. For the checker we ask you to plug a value into the formula. For your pset you still need to give the whole formula.

//DEBUG PARAMETERS //Because we don't show solutions for pset checkers we use //this to give a showanswer button during the debugging phase var debugans = undefined; //release //var debugans = kDebugAnswer; //debug problemNumber = 0; wl("\<h3>Calculator\</h3>"); writecalculator("psetcheckcalcid", "Calculate"); whr(kdivcol,kdivwid);

//Problem 1 problemNumber++; wl(problemheader(problemNumber)); wl(kp); var s; var partName, problemName, buttonLabel, answerArray, correct; s = \["You roll two dice. Consider the following events.", kbr, "$A$ = 'first die is 3'", kbr, "$B$ = 'sum is 7'", kbr, "$C$ = 'sum is greater than or equal to 7'"\]; wl(s.join(' ')); wl(kp); s = \["(a) Compute $P(B)$."\]; wl(s.join(' ')); wl(kp); partName = problemNumber + " (a)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", .16667, buttonLabel, 0.001, "1/6 &#x2248; 0.16667"); wl(kp); s = \["(b) Compute $P(B|A)$."\]; wl(s.join(' ')); wl(kp); partName = problemNumber + " (b)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", .16667, buttonLabel, 0.001, "1/6 &#x2248; 0.16667"); wl(kp); s = \["(c) Compute $P(B|C)$."\]; wl(s.join(" ")); wl(kp); partName = problemNumber + " (c)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", .28571, buttonLabel, 0.001, "6/21 &#x2248; 0.2857"); wl(kp); s = \["(d) Are $A$ and $B$ indepenendent"\]; wl(s.join(" ")); wl(kbr); partName = problemNumber + " (d)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; correct = "Yes" var answerArray = \[correct,"No"\]; writeMultipleChoiceRadioGroup(answerArray, problemName, correct, buttonLabel); wl(kp); s = \["(e) Are $B$ and $C$ indepenendent"\]; wl(s.join(" ")); wl(kbr); partName = problemNumber + " (e)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; correct = "No" var answerArray = \['Yes',correct\]; writeMultipleChoiceRadioGroup(answerArray, problemName, correct, buttonLabel); whr(kdivcol,kdivwid);

//Problem 2 problemNumber++; wl(problemheader(problemNumber)); wl(kp); var s; var partName, problemName, buttonLabel, answerArray, correct; s = \["Draw two cards from a deck.", kbr, "Let $S\_1$ = &grave;first card is a spade'.", kbr, "Let $S\_2$ = &grave;second card is a spade'.", kp, "What is $P(S\_2 | S\_1^c)$?"\]; wl(s.join(" ")); wl(kp); partName = problemNumber; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", .25490, buttonLabel, 0.001, "13/51 &#x2248; 0.2549"); whr(kdivcol,kdivwid);

//Problem 3 problemNumber++; wl(problemheader(problemNumber)); var s; var partName, problemName, buttonLabel, answerArray, correct; s = \["Start with an urn with 5 red and 3 blue balls in it. Draw one ball. Put that ball back in the urn along with another ball of the same color.", kbr, "Now draw another ball from the urn"\]; wl(s.join(' ')); wl(kp); s = \["(a) What is the probability the second ball is red?"\]; wl(s.join(' ')); wl(kp); partName = problemNumber + " (a)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", .625, buttonLabel, 0.001, kuseCorrectVal); wl(kp); s = \["(b) Suppose the second ball is red. What is the probability the first ball was blue."\]; wl(s.join(' ')); wl(kp); partName = problemNumber + " (b)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", 1/3, buttonLabel, 0.001, "1/3 &#x2248; .3333"); wl(kbr); whr(kdivcol,kdivwid);