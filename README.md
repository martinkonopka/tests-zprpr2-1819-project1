# Test scenarios for ZPrPr2-1819 project 1

Each directory in the `tests` directory contains test scenario for the Project 1 from the ZPrPr2 course in SS 2018/2019.

Scenario name template:
```
<number>_<TestedFunction>_<Scenario>_<ExpectedResult>
```

* `number` - optional, for maintaining order of the test scenarios,
* `TestedFunction` - name of the tested function of the project,
* `Scenario` - describes test scenario,
* `ExpectedResult` - optional, use for describing expected program behavior.

Each test scenario contains:
* `input.txt` - with tested program input,
* `expected.txt` - expected output which actual output of the program is compared with,
* `DNAsekvencia.txt` - file with DNA sequence.


To run test scenarios with [Simple Tester](https://github.com/martinkonopka/simple-tester), copy test scenarios to the `tests` directory in the tester.