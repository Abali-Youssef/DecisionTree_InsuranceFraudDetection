# Decision Tree: Insurance Fraud Detection

<br>

> **Problematic :**
>Insurance fraud detection is a set of practices implemented by insurers to identify and prevent fraud from policyholders or third parties. nowaday,digitalization is
>increasing insurance fraud risks and they became more and more sophisticated, in the other hand, the insurance fraud detection should be in growth to face this risk.

<br>

> **Objectif** :
> basing on a insurance data of a reported frauds, my objectif is to train decision tree modele which can predict if a given case will be reported as fraud or not.
<br>

> **Algorithm :**
>1. go through all the given features and find the best one that keeps the most information by calculating the information gain for each one.
>2. find the best threshold of the values ​​of this feature (two intervals) by calculating the information gain for each one.
>3. devise values ​​based on this threshold on both subnodes.
>4. remove the current feature from the set of features.
>5. repeat from 1 to 4 for each subnode and add the element to the tree.
