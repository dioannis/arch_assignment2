# arch_assignment2

### Αρχιτεκτονική Υπολογιστών 2021 Εργαστήριο 2

Παρτσάνης Παναγιώτης - 8037

Διακονικολής Ιωάννης - 8802

**Ερώτημα 1**

a. Βρίσκουμε στο αρχείο του προηγούμενου εργαστηρίου, το _stats.txt_ και βλέπω ότι στο MemRead οι commited εντολές είναι 1085, 18.61% των total instructions της προσομοίωσης.

b. Για τη L1 data cache βρήκα 2152 συνολικό αριθμό των block.

c. Ο συνολικός αριθμός των acceses (read+write) στην L2 Cache είναι 474.

**Ερώτημα 2**

**specbzip**

| Χρόνος Εκτέλεσης | CPI | L1-D miss.rate | L1-I miss.rate | L2 miss.rate |
| ---------------- | ----------- | ----------- | ---------- | ----------- |
| 0.083982s | 1.679650 | 770644 | 747 | 200.996 |

**spechmmer**

| Χρόνος Εκτέλεσης | CPI | L1-D miss.rate | L1-I miss.rate | L2 miss.rate |
| ---------------- | ----------- | ----------- | ---------- | ----------- |
| 0.059396s | 1.187917 | 71886 | 3821 | 5487 |

**speclibm**

| Χρόνος Εκτέλεσης | CPI | L1-D miss.rate | L1-I miss.rate | L2 miss.rate |
| ---------------- | ----------- | ----------- | ---------- | ----------- |
| 0.174771s | 3.493414 | 2975817 | 558 | 1488454 |

**specmcf**

| Χρόνος Εκτέλεσης | CPI | L1-D miss.rate | L1-I miss.rate | L2 miss.rate |
| ---------------- | ----------- | ----------- | ---------- | ----------- |
| 0.064955s | 1.299095 | 75340 | 668914 | 39875 |

**specsjeng**

| Χρόνος Εκτέλεσης | CPI | L1-D miss.rate | L1-I miss.rate | L2 miss.rate |
| ---------------- | ----------- | ----------- | ---------- | ----------- |
| 0.513528s | 10.270554 | 10.523.861 | 649 | 5.263.903 |

**Ερώτημα 3**

**specbzip**

| CPU Clock | Χρόνος εκτέλεσης |  System Clock | CPU Clock |
| ---------------- | ----------- | ----------- | ---------- |
| 1 GHz | 0.083982s | 1000 | 1000 |
| 1.5 GHz | 0.109754s | 1000 | 667 |


**specsjeng**

| CPU Clock | Χρόνος εκτέλεσης |  System Clock | CPU Clock |
| ---------------- | ----------- | ----------- | ---------- |
| 1 GHz | 0.513528s | 1000 | 1000 |
| 1.5 GHz | 0.581937s | 1000 | 667 |































