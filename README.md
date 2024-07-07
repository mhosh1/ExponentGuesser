# Exponent Guesser

This project consists of two parts: ExponentGuesser1 and ExponentGuesser2. Both programs aim to approximate a given positive real number (μ) using a formula with exponents. The programs repeatedly ask the user for positive real numbers and perform calculations to find the best approximation for a given set of exponents.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Example Output](#example-output)

## Overview

The project uses a combination of user-provided values and predefined exponents to find the best approximation of a given constant. The exponents are applied to the user-provided values, and the program iterates through all possible combinations to minimize the difference between the calculated approximation and the target value (μ).

## Features

- Prompt the user for a positive real number (μ) to approximate.
- Prompt the user for four positive real numbers (w, x, y, z) not equal to 1.0.
- Use nested loops to iterate through different combinations of exponents.
- Calculate the best approximation and its relative error.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher.

### Example Output
what constant μ should be approximated that is a positive real number: 2.718

Enter a positive real number not equal to 1.0: 1.5

Enter a positive real number not equal to 1.0: 2.5

Enter a positive real number not equal to 1.0: 3.5

Enter a positive real number not equal to 1.0: 4.5

Exponents: a = -0.5, b = 1.0, c = -1.0, d = 2.0

Approximation: 2.718

Relative Error: 0.00%

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mhosh1/ExponentGuesser.git
