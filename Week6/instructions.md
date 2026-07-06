## Experimentation Methodology

To evaluate the robustness of the proposed autoencoder architectures under different noise conditions, experiments were conducted across all combinations of three noise models and three noise intensities.

### Noise Models
- Gaussian Noise
- Salt-and-Pepper Noise
- Speckle Noise

### Noise Intensities
- 0.1
- 0.5
- 0.9

The global configuration variables

```python
CURRENT_NOISE_TYPE
CURRENT_NOISE_FACTOR
```

were updated for each configuration, and the notebook was executed independently for every combination, resulting in **9 total experimental runs (3 × 3)**.

For each experiment, the following artifacts were generated and recorded:

- Training and validation loss curves
- Model checkpoints
- Image reconstruction outputs
- Quantitative evaluation metrics (e.g., MSE, PSNR, SSIM)
- Architecture-wise performance comparisons

The benchmark tables, reconstruction visualizations, and comparative analyses presented in the following sections summarize the results obtained from these nine experimental configurations.
