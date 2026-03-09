# Configuration files for TB OGRE environments

## Artic RAMPART environment

Derived from instructions foud on the artic-network [website](https://artic-network.github.io/rampart/docs/installation).

1. Install the basic requirements (after installing MinKNOW)

```bash
conda create -f artic-rampart.yaml -n artic-rampart
```

2. Install the non-conda things

```bash
python -m pip install git+https://github.com/artic-network/Porechop.git@v0.3.2pre
python -m pip install binlorry==1.3.0_alpha1
```

3. Test that it works

```bash
rampart --help
```
