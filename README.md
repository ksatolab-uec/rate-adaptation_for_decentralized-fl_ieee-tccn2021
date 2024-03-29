# Implementation Example of Rate Adaptation Algorithm for Decentralized Federated Learning
* This code demonstrates the rate-adaptation algorithm proposed in the following paper:
  * Koya Sato and Daisuke Sugimura, "Rate-Adapted Decentralized Learning Over Wireless Networks," IEEE Trans. Cogn. Commun. Netw., vol.7, no.4, pp.1412-1429, Dec. 2021.
  * https://ieeexplore.ieee.org/document/9410554
* You can evaluate the effect of $\lambda_\mathrm{target}$ on the average transmission rate (related to Fig.11 in the above paper)
 * Please adjust simulation parameters based on the desired condition (e.g., this code sets n=4; however, Fig.11 assumes n=6)
* This code can work with the following command:
```
$python main.py
```

# Note
This code does not contain the learning part.
Please implement it with your favorite ML framework (e.g., PyTorch) if necessary.

# License

The MIT License (MIT)

Copyright (c) 2022 Koya SATO.
