# LaplaceMechanism
C++ code example for computing the secure multi-party Laplace mechanism. This implementation is inspired by the paper:
> Secure multiparty computation of the Laplace mechanism

**Execution Instructions**:
1. Download the benchmark intended for evaluating the performance of differentially private MPC protocols using floating-point arithmetic. The link is provided in the paper:
> "Differentially private data aggregation with optimal utility" by Eigner, F., Kate, A., Maffei, M., Pampaloni, F., and Pryvalov, I. (ACSAC 2014).
2. Copy the code from the file `MPCDP` and paste it into `Node.cpp` (located at `...\src_20140608\floatingMPC\MPC-Shared\src\`).
3. Use the command `make` to compile `Node.cpp` and produce the final executable.
4. Run the program with the command `python3 start.py`.

**Benchmark Installation**:
To install the benchmark, download and integrate the following libraries:
1. GMP library
2. Boost library
3. Pugixml library
4. Relic library, available at [https://projects.cispa.saarland/pryvalov/relicwrapper](https://projects.cispa.saarland/pryvalov/relicwrapper)

