Hui, J., 2021. GAN — Wasserstein GAN & WGAN-GP [WWW Document]. Medium. URL https://jonathan-hui.medium.com/gan-wasserstein-gan-wgan-gp-6a1a2aa1b490 (accessed 1.31.23).
# What is WGAN_GP

# What is Wasserstein loss


However, the Kullback-Leibler divergence (KL divergence) hit 0 at around 900 epochs 
 
The purple dots is the generated distribution of data points which is q(x) in the KL divergence formula. While the Green dots are the actual real data points which is p(x). The KL formula how much the actual distribution matches the generated distribution.
Meanwhile the JS divergence was going down fast and would soon stagnant at 0.23.
JS(P || Q) = 1/2 * KL(P || M) + 1/2 * KL(Q || M)
•	M = 1/2 * (P + Q)

JS divergence uses the KL diverge to calculate a more normalized score which gives a value between 0 to 1 . On top of that the measure of the difference between the real and fake distribution is symmetric. People also call the JS divergence the average KL divergence since it multiplies by half of pretty much the KL divergence formula.


# FID Score

# Visual Evaluation

## Conclusion of WGAN
