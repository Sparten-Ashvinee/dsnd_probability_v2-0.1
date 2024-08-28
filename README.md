# Python library for statistics

Both Binomial and Gaussian (Normal) distributions are fundamental concepts in statistics and probability theory. They serve different purposes and are used to model different types of data.

### Binomial Distribution
The Binomial Distribution is a discrete probability distribution that models the number of successes in a fixed number of independent trials, each with the same probability of success.
It means that it deals with distinct or separate values (e.g., 0, 1, 2, ...). Used for discrete events with fixed trials and success/failure outcomes.

![Binomial_graph](https://miro.medium.com/v2/resize:fit:640/format:webp/0*yErIFuYufYXy2DS1.png)

### Gaussian Distribution
The Gaussian Distribution, commonly known as the Normal Distribution, is a continuous probability distribution characterized by its bell-shaped curve. It is widely used due to the Central Limit Theorem, which states that the sum of a large number of independent random variables tends to be normally distributed, regardless of their original distribution. meaning it deals with a continuum of values (e.g., all real numbers). It is used for continuous data where the distribution tends to cluster around a mean.

![gaussian_graph](https://miro.medium.com/v2/resize:fit:640/format:webp/0*RM4ZJOC0xAN5Fug5.png)

### Project Structure
```
dsnd_probability_v2-0.1/
├── dsnd_probability_v2               # Main package directory
│   ├── __init__.py                   # Initialize the package
│   ├── Binomialdistribution.py       # Binomial distribution
│   ├── Gaussiandistribution.py       # Gaussian distribution
│   └── Generaldistribution.py        # General distribution
├── dsnd_probability_v2.egg-info/     # Directory for pkg info
│   ├── PKG-INFO                      # Package information
│   ├── SOURCES.txt                   # source directory path
│   ├── dependency_links.txt          
│   ├── not-zip-safe                  
│   └── top_level.txt 
├── LICENSE                           # License file
├── README.md                         # README file
├── setup.py                          # Setup script for packaging
├── setup.cfg                         # Config file for packaging
└── PKG-INFO                          # Package information
```

### Release on PyPI
- Creeate account on PyPI
- Upload the Package Using Twine


### Resources
- https://packaging.python.org/en/latest/tutorials/packaging-projects/
- https://simonwillison.net/2021/Nov/4/publish-open-source-python-library/
- https://www.youtube.com/watch?v=Kz6IlDCyOUY
- https://www.turing.com/kb/how-to-create-pypi-packages
