# LaplaceMecanism
C++ code example for computing the secure multi-party Laplace mechanism. This implementation is based on the paper 
> Secure multiparty computation of the Laplace mechanism

**Execution Instructions**:
1. Download the benchmark designed to evaluate the performance of differentially private MPC protocols operating with floating-point arithmetic from the paper
> Differentially private data aggregation with optimal utility" by Eigner, F., Kate, A., Maffei, M., Pampaloni, F., and Pryvalov, I. (ACSAC 2014).
3. Copy the code from the file `MPCDP` and paste it into `Node.cpp` (located in `...\src_20140608\floatingMPC\MPC-Shared\src\`).
4. Use the command `make` to compile `Node.cpp` and build the final executable.
5. Execute the program with the command `python3 start.py`.

**Benchmark Installation**:
To set up the benchmark, download and install the following libraries:
1. GMP library
2. Boost library
3. Pugixml library
4. Relic library available at `https://projects.cispa.saarland/pryvalov/relicwrapper`
