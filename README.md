# Poker Sliders

A simple planning poker tool to help determine the "right" story point value.

Try it online at [poker-sliders](https://rangzen.github.io/poker-sliders).

- [Poker Sliders](#poker-sliders)
  - [Maximum Value vs Mean Value: Which to Choose?](#maximum-value-vs-mean-value-which-to-choose)
    - [Maximum Value](#maximum-value)
      - [Advantages for maximum value](#advantages-for-maximum-value)
      - [Disadvantages for maximum value](#disadvantages-for-maximum-value)
    - [Mean Value](#mean-value)
      - [Advantages for mean value](#advantages-for-mean-value)
      - [Disadvantages for mean value](#disadvantages-for-mean-value)
    - [Understanding Standard Deviation](#understanding-standard-deviation)

## Maximum Value vs Mean Value: Which to Choose?

### Maximum Value

#### Advantages for maximum value

- Aligns with the principle that a story's complexity is driven by its most challenging aspect
- Better reflects real-world scenarios where a single difficult component often determines the overall complexity
- Helps identify potential bottlenecks early

#### Disadvantages for maximum value

- May obscure the overall scope of the story
- Requires three separate discussions, potentially extending estimation time
- Risk of over-focusing on edge cases during estimation

### Mean Value

#### Advantages for mean value

- Mitigates the impact of outliers across dimensions
- Generally leads to faster consensus
- Provides a balanced view of the story's complexity

#### Disadvantages for mean value

- May underestimate the impact of meaningful combinations of medium values
- Can lead to inflated estimates when one dimension significantly differs from others
- Risk of overlooking critical complexity factors

### Understanding Standard Deviation

The standard deviation indicates how spread out the values are from their mean:

- A low value (close to 0) suggests consistency across all dimensions
- A high value indicates significant variation between dimensions
- A standard deviation of 0 means all values are identical

For example:

- Values [1, 1, 1] → SD = 0 (perfect agreement)
- Values [1, 2, 3] → SD = 0.8 (moderate variation)
- Values [1, 1, 8] → SD = 3.3 (significant disagreement)