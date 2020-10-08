# The Eudoxus Real Numbers
The Eudoxus real number is a construction of reals directly from integers. Every number is a set of functions ```ℤ → ℤ``` growing "almost linearly" 
(called almost homomorphisms) in which
the difference between each two functions is bounded. <br />
We defined addition, multiplication, inverse, less than, etc between the numbers, proving they form an additive group, a ring, a total order, etc.
Finally, we verified that the construction is a complete ordered (called ```conditionally_complete_linear_order``` in lean) field 
-- every such field is isomorphic to ℝ. <br />
The formalizing idea is from the paper by R. D. Arthan which can be found at https://arxiv.org/abs/math/0405454.
