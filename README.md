# Pandora: Principled Symbolic Validation of Intel SGX Enclave Runtimes

Pandora is a symbolic execution tool designed for truthful validation of Intel SGX enclave shielding runtimes. Pandora is based on the fabulous angr and extends it with enclave semantics such as Intel SGX instruction support, a realistic enclave memory view, attacker taint tracking, and report generation for a set of powerful vulnerability plugins.

Pandora is the result of our research publication at the 45th IEEE Symposium on Security and Privacy (IEEE S&P 2024) and should be cited as:

> Alder, F., Daniel, L. A., Oswald, D., Piessens, F., & Van Bulck, J. (2024, May). Pandora: P>

Bibtex:

```
@inproceedings{alder2024pandora,
  title={Pandora: Principled Symbolic Validation of Intel SGX Enclave Runtimes},
  author={Alder, Fritz and Daniel, Lesly-Ann and Oswald, David and Piessens, Frank and Van Bu>
  booktitle={45th IEEE Symposium on Security and Privacy-IEEE S\&P 2024},
  year={2024},
  organization={IEEE}
}
```
This organization has four repositories:

1. **pandora**: The symbolic execution tool for Intel SGX enclave runtimes, written in Python.
2. **sgx-tracer**: A C program to dump enclave memory during its initialization.
3. **examples**: Example enclaves written in C to check common enclave runtimes or test Pandora.
4. **reports**: Artifacts of our research results as reported in our paper.
