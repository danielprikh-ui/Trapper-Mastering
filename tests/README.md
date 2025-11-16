# Tests Directory

This folder contains all unit tests for the Trapper-Mastering game.

## Running Tests

To run all tests:
```bash
python -m pytest tests/
```

Or using unittest:
```bash
python -m unittest discover tests/
```

To run a specific test file:
```bash
python -m pytest tests/test_game.py
```

## Test Files

- **test_game.py**: Main test suite covering creature, player, and battle functionality

## Test Structure

Tests are organized by game components:

### TestCreature
- Creature creation
- Fainting mechanics
- Healing
- Damage calculation
- Wild creature generation

### TestPlayer
- Player creation
- Party management
- Item management
- PC storage system

### TestBattle
- Battle initialization
- Attack mechanics
- Catching mechanics
- Running from battle
- Battle results

## Adding New Tests

When adding new features to the game, create corresponding tests in this directory following the naming convention:
- Test files: `test_*.py`
- Test classes: `Test<ComponentName>`
- Test methods: `test_<functionality>`

## Requirements

Tests require the following modules:
- unittest (built-in)
- pytest (optional, but recommended)

Install test dependencies:
```bash
pip install pytest pytest-cov
```

## Coverage

To run tests with coverage:
```bash
python -m pytest --cov=. --cov-report=html tests/
```

This will generate a coverage report in `htmlcov/index.html`
