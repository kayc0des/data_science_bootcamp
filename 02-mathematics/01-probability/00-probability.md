# Probability

Probability is the likelihood of an event occuring. An event is a specific outcome or a combination of several outcomes - which could be pretty much anything. An example is when flipping a fair coin, we have two possible outcomes: head or tails thus we will assign two probabilities for both events.


Probabilities are often expressed as values between 0 and 1 where:

- A probability of `0` implies absolute certainty of the event `NOT` occuring
- A probability of `1` implies absolute certainty of the event occuring

## Definition

- `A` -> An event
- `P(A)` -> Probability of event A occuring is expressed as;

  - `P(A) = preferred outcomes / all outcomes`

This kind of probability is referred to as `theoretical (true)` probability

### Note

If two events are `independent` then:

`P(A and B) = P(A).P(B)`

An `independent` event is an event whose occurence is not dependent on any other. For example, if we flip a coin in the air and get the outcome as Head, then again if we flip the coin but this time we get the outcome as Tail. In both cases, the occurrence of both events is independent of each other.

## Expected Values

The average outcome we expect of we run an experiment many times.

- What is an `experiment`? Imagine we don't know what the probability of flipping a coin is. So we decide to estimate this probability ourselves.

    - `trial` -> flip and record outcome
    - `multiple trials` -> experiment

The probability we get after conducting experiments are called `experimental probabilities`

### Experimental Probability Definition

  - `P(A) = successful trials / all trials`

### Expected Values Definition

E(A) is the outcome we expect to occur when we run an experiment.

#### Categorical outcomes

  - `E(A) = P(A) x n`

where:
  - P(A) is the theoretical probability
  - n is the number of trials
  - E(A) is the expected value

**Example:** Drawing a spade from a deck of cards in 20 trials. If we evalue this probability we have 

  - `E(A) = 0.25 x 20 = 5`

In this case we expect a spade at least five times if we run this experiment. That is the expected value which might differ from reality as we could get a spade more, less number of times or not at all.

#### Numerical Outcomes

  - Sample Space = A, B and C
  - Expected Value = A.P(A) + B.P(B) + C.P(C)

**Example:** Hitting a target with a bow and arrow, the target has three zones. Zone A (outermost) is worth 10 points, Zone B is worth 20 Points and Zone C (target) is worth 100 points. The probability of hitting each Zone is as follows. 

  - `A` -> 0.5
  - `B` -> 0.4
  - `C` -> 0.1

Thus:
  - `E(X) = (0.5 x 10) + (0.4 x 20) + (0.1 x 100) = 23`

We can use expected values to make predictions about the future based on past data.