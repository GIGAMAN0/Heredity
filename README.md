# Heredity

## Objective
Write an AI to assess the likelihood that a person will have a particular genetic trait.

## Python Version
Use Python 3.11 as newer versions might not be fully compatible with some Python modules used in the course.

## Features
- Calculate probabilities of people having certain genetic traits based on Bayesian Network.
- Compute joint probabilities for multiple events considering gene inheritance and mutation.
- Update probability distributions based on new evidence.
- Normalize probability distributions to ensure sum equals 1.

## Background
The project deals with assessing genetic traits based on Bayesian Network modeling. It considers gene inheritance, mutation probabilities, and observable traits to make inferences about a population's genetic makeup.

## Getting Started
1. Download the distribution code from the provided link.
2. Familiarize yourself with the data format and the definitions in heredity.py.
3. Implement the joint_probability, update, and normalize functions as per the specification.

## Usage
- Execute `heredity.py` with the path to the CSV file containing family data.
- The program will output probabilities of individuals having specific genetic traits.
