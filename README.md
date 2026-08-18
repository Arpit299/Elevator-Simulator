# Elevator Simulator

A simple, object-oriented Python simulation of a building elevator system.

## Features
- Customizable number of floors.
- Door opening and closing logic.
- Sequential floor movement with real-time logging.
- Safety checks for invalid floor requests.

## Installation
No external dependencies are required other than the Python standard library (`time` module).

## Usage
Initialize the `Elevator` class and use the `move_to_floor` method to navigate.

```python
my_elevator = Elevator(name="Main Elevator", floors=10)
my_elevator.move_to_floor(5)
```
