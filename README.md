# Satellite Orbit Prediction Processor (S.O.P.P.)

## Overview

S.O.P.P. (Satellite Orbit Prediction Processor) is an open-source tool designed to help radio astronomers mitigate interference from satellites during observations. It calculates satellite positions relative to an observation facility and identifies potential interference with the main beam of the telescope.

## Features

Computes satellite positions based on TLE data

Identifies satellites crossing the telescope's main beam

Lists satellites above the horizon during an observation

Supports filtering satellites by name, frequency, and orbit type

Configurable through JSON or Python API

## Installation

To install S.O.P.P., first ensure you have Python 3.8+ installed. Then, clone the repository and install dependencies:

### Clone the repository
```
git clone https://github.com/example/sopp.git
cd sopp
```

### Install dependencies
```
pip install -r requirements.txt
```
