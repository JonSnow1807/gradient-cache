# Gradient Cache v1.0.0 Release Notes

## 🎉 First Public Release

### Features
- 90%+ GPU memory savings during neural network training
- 100x gradient compression with minimal accuracy impact
- Simple 3-line integration with any PyTorch model
- Support for Metaflow and PyTorch Lightning
- Tested on NVIDIA A100 and T4 GPUs

### Performance
- Compression ratio: 100x (keeps top 1% of gradients)
- Memory savings: 90-95% of gradient memory
- Training overhead: ~10-15%
- Enables 2-3x larger batch sizes

### Files Included
- `gradient_cache-1.0.0-py3-none-any.whl` - Pip installable wheel
- `gradient_cache-1.0.0.tar.gz` - Source distribution
- Full documentation and examples

### Installation
```bash
pip install gradient_cache-1.0.0-py3-none-any.whl
```

### Acknowledgments
Built with PyTorch 2.7.1 and tested extensively on Lightning AI platform.