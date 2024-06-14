22.05.2024 11:06:39
Repository not in the required format. Should be a clone of my repository

28.05.2024 18:48:03 
Repozytorium dalej nie w takim formacie jak trzeba. Ale poprawię:) 

# Banknotes NB

## Problem 1

28.05.2024 18:48:52 OK

## Problem 2

28.05.2024 18:49:28
Wygląda OK, ale brakuje porównania krzywych ROC,dla jednej i dwu cech. 

14.06.2024 13:08:48 OK
Ale za dużo krzywych na wykresie. Można usunąć krzywe z train set,

## Problem 3

28.05.2024 18:49:28
Wygląda OK, ale brakuje porównania krzywych ROC dla rónej ilości cech. 

14.06.2024 13:09:34 OK
Ale jak wyżej.

# Banknotes GMDA 

## Problem 1

4.06.2024 13:17:20 OK

## Problem 2

4.06.2024 13:18:53
You have bundled together B and C. This makes it hard to me to check. Please correct this. Also you have not taken into acount that the numbers of counterfeit and non-counterfeit banknotes are not the same.  

14.06.2024 16:17:17 OK
But different number of counterfeit and real banknotes is still not acounted for. The weights that you initialize when fitting the GMMs have nating to do with it. 

## Problem 3

4.06.2024 13:23:00 OK
But see previous assignment. 

## Problem 4

4.06.2024 13:25:00
The cost does not take into acount the probability of the counterfeit banknote. 


14.06.2024 16:19:02 
You were supposed to compare the classfiers obtained in problems A-C.
Anyway the answer is wrong. You are choosing the optimal threshold by maximazing TPR – FPR instead of minimizing loss. 

# Banknote NN

4.06.2024 15:34:49
You should at least try some more complicated network.
Try also to better train the model. You can get better accuracy.

14.06.2024 16:22:59 OK
But it would be nice to have also a confusion matrix and AUC score. 
