NO DATA AUGMENTATION

HYPERPARAM 

- BATCH SZ = 64 
- LR = 0.001 
- EARLY STOPPING = NO 
- EPOCHE = 100 
- OPT = SGD (momentum 0.8 e decay 1e^-5) 

Interpretazione = La curva relativa alla validation in questo caso sale nelle prime 20/30 epoche e poi sembra nuovamente oscillare attorno ad un valore di 0.5/0.6, la matrice di confusione risulta invece per nulla soddisfacente, ed appuràbile come il dataset sia sbilanciato sulla classe 4. Va anche in questo caso riprovato per vedere se viene simile. Ed anche qua, va notato come dopo 50 epoche, non vi siano particolari modifiche o migliore dal punto di vista delle metriche 