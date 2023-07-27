# The-Mysterious-dice
Problem :You have two dice, but each die has only four sides instead of the usual six. The sides of the first die are numbered 1, 2, 2, and 3. The sides of the second die are numbered 1, 2, 3, and 3. You randomly pick one die and roll it. If the result is a 1, what is the probability that you rolled the first die?
Let's define the events:
A: Rolling the first die
B: Rolling a 1

We want to find P(A | B), which is the probability of rolling the first die given that the result is a 1.

Using Bayes' theorem:
P(A | B) = (P(B | A) * P(A)) / P(B)

P(B | A) is the probability of rolling a 1 given that you picked the first die. Since the first die has two sides with 1, the probability is 2/4 = 1/2.

P(A) is the probability of picking the first die initially. Since you randomly pick one die, the probability of picking the first die is 1/2.

P(B) is the probability of rolling a 1, regardless of which die you picked. There are three sides with 1 between both dice, so the probability is 3/8.

Now, we can calculate P(A | B):
P(A | B) = (1/2 * 1/2) / (3/8)
P(A | B) = 1/3

So, the probability of having rolled the first die, given that the result is a 1, is 1/3.
