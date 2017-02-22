---
title: Distribution-Independent Evolvability of Linear Threshold Functions
abstract: Valiant's model of evolvability models the evolutionary process of acquiring
  useful functionality as a restricted form of learning from random examples \citep{Valiant:09}.Linear
  threshold functions and their various subclasses, such as conjunctions and decision
  lists, play a fundamental role in learning theory and hence their evolvabilityhas
  been the primary focus of research on Valiant's framework. One of the main open
  problems regarding the model is whether conjunctions are evolvable distribution-independently\citep{FeldmanValiant:08colt}.
  We show that the answer is negative. Our proof is based on a new combinatorial parameter
  of a concept class that lower-bounds the complexity of learning fromcorrelations.We
  contrast the lower bound with a proof that linear threshold functions having a non-negligible
  margin on the data points are evolvable distribution-independently via a simple
  mutationalgorithm. Our algorithm relies on a non-linear loss function being used
  to select the hypotheses instead of 0-1 loss in Valiant's original definition. The
  proof of evolvabilityrequires that the loss function satisfies several mild conditions
  that are, for example, satisfied by the quadratic loss function studied in several
  other works \citep{Michael:07,Feldman:09sqd,Valiantp:11manu}. An important property
  of our evolution algorithm is monotonicity, that is the algorithm guaranteesevolvability
  without any decreases in performance. Previously, monotone evolvability was only
  shown for conjunctions with quadratic loss \citep{Feldman:09sqd} or when the distribution
  on the domain is severely restricted \citep{Michael:07,Feldman:09sqd,KanadeVV:10}.
pdf: "./feldman11b/feldman11b.pdf"
layout: inproceedings
key: feldman11b
month: 0
firstpage: 253
lastpage: 272
origpdf: http://jmlr.org/proceedings/papers/v19/feldman11b/feldman11b.pdf
sections: 
authors:
- given: Vitaly
  family: Feldman
---
