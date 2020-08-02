# MPPs
An implementation for discovering non-terminating inputs (NTI) for multi-path polynomial programs (MPPs)

Current version: v1.1
Validated on platform: `Maple` 2020, macOS Catalina
Latest modification: on Aug 2nd, 2020, by _Mingshuai Chen_, RWTH Aachen

Corresponding e-mail: chenms@cs.rwth-aachen.de
Comments and bug-reports are highly appreciated.

## Usage

1. The procedure takes a specific MPP as input, and gives the NTI as well as the minimum integer *N* such that *D<sub>N</sub>* is a fixed-point of the descending chain of algebraic sets. In particular, essential computations of Gröbner bases and membership of radical ideals attribute to the package `Groebner` and `PolynomialIdeals`, respectively.

2. The script `mpp1.mw` contains the implementation of Algorithm 1 for computing the fixed-point of the descending chain of algebraic sets and a bunch of examples as well.

3. The script `mpp2.mw` provides another more efficient implementation (Algorithm 2) which computes the NTI using Gröbner bases. Also, the same bunch of examples are enclosed in this script.

4. With `Maple` pre-installed, using this procedure is quite straightforward: one can evaluate the entire worksheet by clicking `Evaluate` -> `Evaluate Worksheet`. Please refer to the embedded examples in case you encountered any issue when working on it.

5. Again, any comments and bug-reports are highly appreciated. Enjoy.
