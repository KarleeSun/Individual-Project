# Meeting Minutes

## Date: 2025/04/29
### Current Progress
#### Experiments:
- Trained VQ-VAE SOKE on CSL-Daily
- Trained DETO SOKE on CSL-Daily
#### Report:
- Completed the report on the experiments conducted and background sections

### Next Steps:
-[ ] Train RVQ SOKE on CSL-Daily
   - RVQ: https://arxiv.org/pdf/2107.03312
   - Sample Config: https://github.com/2000ZRL/SOKE_backup/blob/main/configs/vq/hand2048_res5.yaml
   - [ ] Try different num_res and compare effectiveness
   - [ ] Add results to the report 
- [ ] Experiment Rot6D
  - Rot6d: https://arxiv.org/pdf/1812.07035
  - [ ] Add description in 3D Representation section in the report
  - [ ] Experiment and compare performance
  - [ ] Add results to the report
- [ ] Experiment with encoder-decoder architecture
  - [ ] Change CNN to transformer
  - [ ] Add results to the report 
### Further reading
  - Introducing semantics into quantization: https://arxiv.org/pdf/2409.04429, https://arxiv.org/pdf/2504.08736
  - Qwen3-series: https://huggingface.co/collections/Qwen/qwen3-67dd247413f0e2e4f653967f
  - Contrastive learning in sign language translation: https://arxiv.org/pdf/2405.04164, https://arxiv.org/pdf/2307.14768
### Idea about final project:
  - Try multi-modal approach with text embedding, freeze VQ-VAE part and train with contrastive loss.