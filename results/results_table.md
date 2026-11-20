| Model | Params | Train time/epoch (s) | Latency (ms/batch 64) | Test MSE | Test PSNR (dB) | Test SSIM | FID |
|---|---|---|---|---|---|---|---|
| Vanilla Autoencoder | 435,536 | 7.2 | 0.17 | 0.00651 | 22.99 | 0.7889 | N/A |
| Sparse Autoencoder | 1,067,024 | 7.9 | 0.25 | 0.00444 | 24.68 | 0.8449 | N/A |
| Variational Autoencoder (VAE) | 451,984 | 7.2 | 0.12 | 0.01322 | 19.64 | 0.6479 | 85.84 |
| GAN | 1,477,136 | 9.1 | 0.30 | N/A | N/A | N/A | 103.01 |
| DCGAN | 759,681 | 9.0 | 0.95 | N/A | N/A | N/A | 22.48 |
| DDPM | 2,326,529 | 41.8 | 16047.42 | N/A | N/A | N/A | 42.30 |
