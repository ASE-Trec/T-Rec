# T-Rec
## Commands to run T-Rec
### Run T-Rec
```
java -jar t-rec.jar \
    --test-script <path to the test script> \
    --input-file <path to the file to be reduced> \
    --on-demand-reducer-classes "org.perses.reduction.reducer.AtnFineTuningTokenReducer"
```

### Run T-Red_dd
```
java -jar t-rec.jar \
    --test-script <path to the test script> \
    --input-file <path to the file to be reduced> \
    --on-demand-reducer-classes "org.perses.reduction.reducer.DeltaDebuggingFineTuningTokenReducer"
```
### Check all the available command line arguments
```
java -jar t-rec.jar --help
```
## Benchmarks
### C and Rust Benchmarks
The C and Rust benchmarks are collected from the Github repository of Perses:
https://github.com/uw-pluverse/perses/tree/master/benchmark
### SMTLIBv2 Benchmarks
The SMTLIBv2 benchmarks are from the ddsmt paper:
https://zenodo.org/record/4721925#.ZF2UoeyZNUc