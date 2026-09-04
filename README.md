# Development wheels for stormpy

Wheels for [stormpy](https://github.com/stormchecker/stormpy) are created nightly and published at [stormchecker.github.io/stormpy-wheels/simple](https://stormchecker.github.io/stormpy-wheels/simple/stormpy/).

The stormpy wheel can be installed by first manually installing the dependencies and then installing the stormpy wheel:
```
pip install Deprecated
pip install --index-url https://stormchecker.github.io/stormpy-wheels/simple stormpy
```

Alternatively, stormpy can be installed in one go by explicitly allowing pre-releases (`--pre`):
```
pip install stormpy --pre --index-url https://stormchecker.github.io/stormpy-wheels/simple --extra-index-url https://pypi.org/simple
```
