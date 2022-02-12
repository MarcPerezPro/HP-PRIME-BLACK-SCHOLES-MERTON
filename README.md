# HP PRIME Black-Scholes-Merton

A library of Black-Scholes-Merton functions for HP Prime calculators 🧮

![results part 1](docs/results1.png)
![results part 2](docs/results2.png)
![results part 3](docs/results3.png)

## Installation

Using the [HP Connectivity Kit](https://www.hpcalc.org/details/8938), drag and drop the [BSM.hpprgm](Calculators/Prime/BSM.hpprgm) file into the HP Prime calculator.

![HP Connectivity Kit usage](docs/hp_connectivity_kit.png)

## Interactive Usage

Press <kbd>Shift</kbd>+<kbd>1</kbd> to open the `Program` menu on the HP Prime.

![Program menu key presses](docs/program_key_presses.png)

From there you can interactively run the `BSM` function that will display the results of the Black-Scholes-Merton formulas.

![Running from program catalog](docs/run_from_program_catalog.png)

![Setting parameters](docs/setting_parameters.png)

## Library Usage

If you want to run the formulas independently, press the <kbd>Toolbox</kbd> key.

![Toolbox key](docs/toolbox_key.png)

Then, on the touchscreen, go to the `User` tab, click on `BSM`, and select the function of your choice from the dropdown menu.

![BSM function selection](docs/toolbox.png)

![Running as library](docs/running_as_library.png)

This library contains:

- `BSM_D1(price, strike, rate, time, volatility, dividend)`
- `BSM_D2(price, strike, rate, time, volatility, dividend)`
- `BSM_ND1(price, strike, rate, time, volatility, dividend)`
- `BSM_ND2(price, strike, rate, time, volatility, dividend)`
- `BSM_N_MINUS_D1(price, strike, rate, time, volatility, dividend)`
- `BSM_N_MINUS_D2(price, strike, rate, time, volatility, dividend)`
- `BSM_N_PRIME_D1(price, strike, rate, time, volatility, dividend)`
- `BSM_CALL(price, strike, rate, time, volatility, dividend)`
- `BSM_PUT(price, strike, rate, time, volatility, dividend)`
- `BSM_CALL_DELTA(price, strike, rate, time, volatility, dividend)`
- `BSM_PUT_DELTA(price, strike, rate, time, volatility, dividend)`
- `BSM_GAMMA(price, strike, rate, time, volatility, dividend)`
- `BSM_CALL_THETA(price, strike, rate, time, volatility, dividend)`
- `BSM_PUT_THETA(price, strike, rate, time, volatility, dividend)`
- `BSM_VEGA(price, strike, rate, time, volatility, dividend)`
- `BSM_CALL_RHO(price, strike, rate, time, volatility, dividend)`
- `BSM_PUT_RHO(price, strike, rate, time, volatility, dividend)`

## Development

Contributions are welcome, just make sure it still passes the [Unit Tests](Calculators/Prime/BSM_UNIT_TEST.hpprgm).
