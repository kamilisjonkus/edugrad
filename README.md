# To understand the [tinygrad](https://github.com/tinygrad/tinygrad)

* tinygrad/codegen/linerize.py:linearize_uop. Computation graph of UOps -> Ordered list of UOps.
  * Think of it like untangling a messy ball of yarn into a single, straight thread.
  * Respect the interdependencies, but perform actions in sequence, one action a time. 
