﻿# Stochastics & Statistics
Notes in probability, statistics, and their applications from the introductory to the advanced level. Always going to be a work in progress.

## Contents
-   [Fundamentals](#fundamentals)
    -   [Introductory Probability](#introductory-probability)
        -   [Probability Laws](#probability-laws)
        -   [Introductory Combinatorics](#introductory-combinatorics)
        -   [Probability Distributions](#probability-distributions)
        -   [Expectation](#expectation)
        -   [Variance](#variance)
        -   [Independence](#independence)
    -   [Introductory Statistics](#introductory-statistics)
        -   [Data Generating Processes](#data-generating-processes)
        -   [Descriptive Statistics](#descriptive-statistics)
        -   [Inferential Statistics](#inferential-statistics)
        -   [Simple Linear Regression](#simple-linear-regression)
        -   [Analysis of Variance](#analysis-of-variance)
        -   [Method of Moments](#method-of-moments)
    -   [Intermediate Probability](#intermediate-probability)
        -   [Families of Continuous Univariate Probability
            Distributions](#families-of-continuous-univariate-probability-distributions)
        -   [Families of Discrete Univariate Probability
            Distributions](#families-of-discrete-univariate-probability-distributions)
        -   [Random Vectors](#random-vectors)
        -   [Multivariate Probability
            Distributions](#multivariate-probability-distributions)
        -   [Transformations of Random
            Variables](#transformations-of-random-variables)
        -   [Inequalities in Probability](#inequalities-in-probability)
        -   [Notions of Convergence](#notions-of-convergence)
    -   [Intermediate Statistics](#intermediate-statistics)
        -   [Least Squares](#least-squares)
        -   [Statistical Decision Theory](#statistical-decision-theory)
        -   [Maximum Likelihood
            Estimation](#maximum-likelihood-estimation)
        -   [Fisher Information](#fisher-information)
        -   [Maximum a Posteriori
            Estimation](#maximum-a-posteriori-estimation)
        -   [James-Stein Estimators](#james-stein-estimators)
        -   [Generalised Linear Models](#generalised-linear-models)
        -   [Gauss-Markov Theorem](#gauss-markov-theorem)
    -   [Advanced Probability](#advanced-probability)
        -   [Moments](#moments)
        -   [Probability Generating
            Functions](#probability-generating-functions)
        -   [Characteristic Functions](#characteristic-functions)
        -   [Cumulants](#cumulants)
        -   [Central Limit Theorem](#central-limit-theorem)
        -   [Multivariate Gaussian
            Identities](#multivariate-gaussian-identities)
        -   [Exponential Families](#exponential-families)
        -   [Random Matrices](#random-matrices)
        -   [Stochastic Processes](#stochastic-processes)
    -   [Bayesian Probability &
        Statistics](#bayesian-probability-statistics)
        -   [Cox's Theorem](#coxs-theorem)
        -   [Extensions to Bayes' Theorem](#extensions-to-bayes-theorem)
        -   [Bayesian Priors](#bayesian-priors)
        -   [Bayesian Updating](#bayesian-updating)
        -   [Bayesian Networks](#bayesian-networks)
        -   [Bayesian Inference](#bayesian-inference)
        -   [Bayesian Classifiers](#bayesian-classifiers)
    -   [Markov Processes](#markov-processes)
        -   [Markov Chains](#markov-chains)
        -   [Hidden Markov Models](#hidden-markov-models)
        -   [Markov Decision Processes](#markov-decision-processes)
        -   [Markov Chain Monte Carlo](#markov-chain-monte-carlo)
    -   [Measure Theoretic Probability](#measure-theoretic-probability)
        -   [Probability Spaces](#probability-spaces)
        -   [Borel-Cantelli Lemma](#borel-cantelli-lemma)
        -   [Dominated Convergence
            Theorem](#dominated-convergence-theorem-1)
        -   [Radon-Nikodym Theorem](#radon-nikodym-theorem)
        -   [Karhunen-Loève Theorem](#karhunen-loève-theorem)
    -   [Advanced Statistics](#advanced-statistics)
        -   [Copulas](#copulas)
        -   [Empirical Measures](#empirical-measures)
        -   [Order Statistics](#order-statistics)
        -   [Asymptotic Theory](#asymptotic-theory)
        -   [Resampling Methods](#resampling-methods)
        -   [Principal Component
            Analysis](#principal-component-analysis)
        -   [Survival Analysis](#survival-analysis)
        -   [Linear Discriminant
            Analysis](#linear-discriminant-analysis)
        -   [Rao-Blackwell Estimators](#rao-blackwell-estimators)
    -   [Stochastic Calculus](#stochastic-calculus)
        -   [Martingales](#martingales)
        -   [Itô Calculus](#itô-calculus)
        -   [Stratonovich Integral](#stratonovich-integral)
        -   [Kolmogorov-Chentsov Continuity
            Theorem](#kolmogorov-chentsov-continuity-theorem)
        -   [Stochastic Differential
            Equations](#stochastic-differential-equations)
    -   [Combinatorial Probability](#combinatorial-probability)
        -   [Inclusion-Exclusion
            Principle](#inclusion-exclusion-principle)
        -   [Pigeonhole Principle](#pigeonhole-principle)
        -   [Partitions](#partitions)
        -   [Catalan Numbers [@Lange2010]](#catalan-numbers)
        -   [Derangements](#derangements)
-   [Applications](#applications)
    -   [Information Theory](#information-theory)
        -   [Entropy](#entropy)
        -   [Kullback-Leibler Divergence](#kullback-leibler-divergence)
        -   [Maximum Entropy
            Distributions](#maximum-entropy-distributions)
        -   [Coding Theory [@Cover2006]](#coding-theory)
        -   [Information Criteria](#information-criteria)
        -   [Sanov's Theorem](#sanovs-theorem)
        -   [Minimum Description Length](#minimum-description-length)
        -   [$f$-Divergence](#f-divergence)
    -   [Econometrics](#econometrics)
        -   [Model Specification](#model-specification)
        -   [Instrumental Variables](#instrumental-variables)
        -   [Panel Data Regression](#panel-data-regression)
        -   [Time-Series Models](#time-series-models)
        -   [Time-Series Regression](#time-series-regression)
    -   [Machine Learning](#machine-learning)
        -   [Classification Problems](#classification-problems)
        -   [$k$-Nearest Neighbours](#k-nearest-neighbours)
        -   [Radermacher Complexity](#radermacher-complexity)
        -   [Neural Networks](#neural-networks)
        -   [Ensemble Methods](#ensemble-methods)
        -   [Decision Trees](#decision-trees)
    -   [Statistical Signal Processing](#statistical-signal-processing)
        -   [Random Signals and Systems](#random-signals-and-systems)
        -   [Power Spectral Density](#power-spectral-density)
        -   [Linear Filtering](#linear-filtering)
        -   [Wiener-Kolgomorov Filtering](#wiener-kolgomorov-filtering)
        -   [Kalman Filtering](#kalman-filtering)
        -   [Kalman Smoother](#kalman-smoother)
        -   [Viterbi Algorithm](#viterbi-algorithm)
        -   [Particle Filtering](#particle-filtering)
        -   [Subspace Identification](#subspace-identification)
        -   [Wavelets](#wavelets)
    -   [Stochastic Control](#stochastic-control)
        -   [Linear Quadratic Gaussian](#linear-quadratic-gaussian)
        -   [Stochastic Model Predictive
            Control](#stochastic-model-predictive-control)
        -   [Stochastic Stability](#stochastic-stability)
        -   [Reinforcement Learning](#reinforcement-learning)
    -   [Quantitative Finance](#quantitative-finance)
        -   [Portfolio Optimisation](#portfolio-optimisation)
        -   [Black-Scholes Model](#black-scholes-model)
        -   [Optimal Stopping](#optimal-stopping)
        -   [Ruin Theory](#ruin-theory)
    -   [Statistical Physics](#statistical-physics)
        -   [Mean Sojourn Time](#mean-sojourn-time)
        -   [Mean Field Theory](#mean-field-theory)