## OLS Linear Regression: Hyperplane of zero net force and torque

### Introduction

Linear regression is a commonly used technique. It was first used by Sir Francis Galton. Despite it’s dull nature, the term ‘regression’ has a significant implication as per Sir Galton’s study. Nowadays it is used in several applications to study the effect of change of one or more (independent) variables on a response variable.

In this article, I will attempt to look at linear regression through a different lens — physics. For simplicity, we will assume that all the assumptions of linear regression are satisfied.

---

### The Mathematics

Linear regression has the form @[y = \beta_0 + \beta_1*x_1 + \beta_2*x_2 + ... + \beta_n*x_n@]

The conditional mean is estimated as

$$\hat{y} = b_0 + b_1*x_1 + b_2*x_2 + ... + b_n*x_n$$

The ordinary least square solution is obtained by minimizing

$$\sum_{\forall i}(\hat{y[i]}-y[i])^2$$

