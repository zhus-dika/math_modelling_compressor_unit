# Modelling of the operation of a gas compressor station

Source wolfram code for the paper *"Modeling gas compressor station operation to minimize fuel costs for surge zone protection"*

### To run calculations follow the instructions below:

1. ---> run code in the file _calculateFunctionsForCSRegime.nb_

2. ---> run code in the file _calculateProceduresForCSRegime.nb_

3. ---> run code in the file _globalVariablesHours.nb_

4. ---> run code in the file _SGERG-88.nb_

5. ---> run code in the file _totalHoursComputations.nb_

6. ---> open file _data/output/dataset.xlsx_

The calculation results will be shown as plots in the file _totalHoursComputations.nb_, and the calculation results will be written to _data/dataset.xlsx_.

### Example output plots:

![plot](https://github.com/zhus-dika/math_modelling_compressor_unit/blob/main/data/output/example_figs/01.02_02.png)

and corresponding output parameters:


| Name                    |      Value      |  Unit    |
|----------               |:-------------:  |------:   |
|calculated rotations     | $5035$          |$rot/min$ |
| real rotations          | $5000$          |$rot/min$ |
| $\tilde{n}_{red}$       | $0.9401$        |    -     |
| $\eta_{pol}$            | $0.6676$        |    -     |
| $T_{out}$ calculated    | $13.3783$       |$C^\circ$ |
| $T_{out}$ real          | $15$            |$C^\circ$ |
| $N_{red}$               | $124.671$       |    -     |
| $N_{available}$         | $4887.5$        |  $kW$    |
| $N_{inner}$             | $2495.96$       |  $kW$    |
| $K_{charge}$            | $0.5629$        |    -     |
| $K_{dist}$              | $1.8642$        |    -     |
| $N$                     | $2751.13$       |   $kW$   |
| $Q_{fuel-gas}$          | $1557.31$       |$m^3/hour$|
|compressor work point $X$| $249.677$       |    -     |
|compressor work point $Y$| $1.1265$        |    -     |

A description of all computational procedures is presented in the file _description.nb_.

NOTE. The input data for the calculations was not included in this repository due to the privacy policy, but examples of filling out the data are in the _data_ folder.
