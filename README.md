# tkseek
A distributed computing platform that runs DeepSeek machine learning models across multiple computers across the TKS network using SLURM, SingularityCE, and PyTorch.

[Docs](https://the-knowledge-seeker.gitbook.io/the-knowledge-seeker)

## Tasks

### MVP
- [ ] Set up Kubernetes configuration across 3 machines  
- [ ] Create Docker container with DeepSeek dependencies  
- [ ] Implement PyTorch distributed data parallel for model distribution  
- [ ] Configure network resilience for home internet connections  
- [ ] Test minimal deployment with 1-2 machines  
- [ ] Create monitoring dashboard with Prometheus/Grafana  
- [ ] Implement checkpoint-based synchronization  
- [ ] API endpoint for TKSites  
- [ ] Create simple CLI for job submission  

### SPRINKLES  
- [ ] Implement dynamic resource allocation based on node capabilities  
- [ ] Create web UI for job management  
- [ ] Add auto-scaling capabilities using Kubernetes Horizontal Pod Autoscaler (HPA)  
- [ ] Implement peer-to-peer data transfer for model weights  
- [ ] Create visualization tools for distributed processing  
- [ ] Add support for GPU acceleration using Kubernetes GPU plugins  
- [ ] Implement fine-tuning capabilities  
- [ ] Create automated deployment scripts using Helm charts
