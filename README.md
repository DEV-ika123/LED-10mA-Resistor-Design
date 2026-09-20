# LED 10mA Current Target Design

## Objective

To design and simulate an LED circuit that achieves a target current of approximately 10 mA using a calculated resistor value.

## Circuit

**9V Power Supply → Resistor → Red LED → Power Supply −**

## Design Calculation

Supply voltage:

**Vₛ = 9 V**

Approximate LED forward voltage:

**VLED ≈ 2 V**

Target current:

**I = 10 mA = 0.01 A**

Required resistor:

**R = (Vₛ − VLED) / I**

**R = (9 − 2) / 0.01**

**R = 700 Ω**

Therefore, the calculated resistor value is:

**R = 700 Ω**

## Simulation

A **700 Ω resistor** was used in Tinkercad.

The measured current was:

**I = 10.0 mA**

The measured value matched the target current very closely.

## Resistor Power

Using the measured current:

**P = I²R**

**P = (0.010)² × 700**

**P = 0.07 W**

Therefore, the resistor dissipates approximately **70 mW** of power.

## Comparison with 680 Ω

A second test was performed using a **680 Ω resistor**.

| Resistor | Target Current | Measured Current | Power |
|---|---:|---:|---:|
| 680 Ω | 10 mA | 10.3 mA | 0.0721 W |
| 700 Ω | 10 mA | 10.0 mA | 0.0700 W |

## What I Learned

* A resistor value can be calculated from a desired LED current.
* The calculated resistor value can be tested using simulation.
* A small change in resistance changes the circuit current.
* Measured results can be compared with the design target.
* Resistor power should also be checked during circuit design.

## Engineering Lesson

Circuit design is not only about building a circuit. An engineer first determines the required values, calculates the components, builds the circuit, measures the result, and checks whether the design meets the target.

## Tools Used

* **Tinkercad Circuits** — circuit simulation
* **Red LED** — circuit load
* **Resistors** — current limiting
* **9V Power Supply** — circuit source
* **Ohm's Law** — resistor calculation
* **GitHub** — project documentation and version control
