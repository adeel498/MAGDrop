# MAGDrop: Momentum-Adaptive Gradient Dropout

Official implementation of "Provable Generalization Bounds for Deep Neural Networks with Adaptive Regularization"

## Quick Start

### Installation

pip install -r requirements.txt

### Run Experiments

---> python pac_bayes_computation.py

This reproduces the PAC-Bayes bound computation showing 29.2% improvement over standard dropout.

---> train_cifar10.txt

Run comprehensive CIFAR-10 experiments comparing MAGDrop against baseline regularization methods



---> train_tiny_imagenet.py

It reproduces our Tiny ImageNet results for Table 3.


## Results

- 29.2% tighter generalization bounds
- MAGDrop bound: 0.901
- Standard dropout bound: 1.272

## Files

- pac_bayes_computation.py - MAGDrop implementation and Main experiments
- requirements.txt - Dependencies

## Citation

@article{safder2025magdrop,
  title={Provable Generalization Bounds for Deep Neural Networks with Adaptive Regularization},
  author={Safder, Adeel},
  journal={Journal of Machine Learning Research},
  year={2025}
}

## License

MIT License