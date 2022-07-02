DATA AUGMENTATION : BRIGHTNESS & FLIP

HYPERPARAM 

- BATCH SZ = 64 
- LR = 0.001 
- EARLY STOPPING = NO 
- EPOCHE = 100 
- OPT = SGD (momentum 0.8 e decay 1e^-5) 

Interpretazione = La curva relativa alla validation sembra oscillare attorno ad un valore di 0.3, la matrice di confusione risulta abbastanza soddisfacente, naturalmente non è perfetta. Va riprovato per vedere se viene simile. Va notato come dopo 50 epoche, non vi siano particolari modifiche o migliore dal punto di vista delle metriche. 