# Flatiron Cars Flask Application

## Description

This Flask application simulates a simple car company catalog. It provides routes that allow users to view a welcome message and check whether a specific car model exists in the company's fleet.

## Features

* Default route (`/`) displays a welcome message.
* Dynamic route (`/<model>`) checks if a car model exists in the catalog.
* Returns a confirmation message when a model is available.
* Returns an unavailable message when a model is not found.

## Available Models

* Beedle
* Crossroads
* M2
* Panique

## Routes

### Home Route

```text
/
```

Returns:

```text
Welcome to Flatiron Cars
```

### Model Route

```text
/<model>
```

Example:

```text
/Beedle
```

Returns:

```text
Flatiron Beedle is in our fleet!
```

Example:

```text
/Toyota
```

Returns:

```text
No models called Toyota exists in our catalog
```

## Installation

1. Clone the repository.
2. Navigate to the project directory.
3. Install dependencies:

```bash
pipenv install
```

4. Activate the virtual environment:

```bash
pipenv shell
```

5. Run the application:

```bash
python app.py
```

## Author

Caren Chemjor
