# AutoModeler3D

AutoModeler3D is an advanced 3D modeling system designed to automate and enhance the 3D modeling process using Blender's Python API. It provides a comprehensive set of tools for model generation, scripting, UI, asset management, and more.

## Prerequisites

- Blender 2.93 LTS or newer
- Python 3.9 or newer

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/VishwamAI/AutoModeler3D.git
   ```
2. Navigate to the project directory:
   ```
   cd AutoModeler3D
   ```
3. Install the required Python packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

To generate a batch of primitive shapes:
```
python batch_shape_generator.py
```

For more advanced usage, refer to the [API documentation](Documentation/API_Documentation.md) and [tutorial scripts](Documentation/Tutorial_Scripts.md).

## Running Tests

To verify the installation and functionality:
```
python -m unittest discover tests
```

## Contributing

Contributions are welcome! Please read our [contribution guidelines](CONTRIBUTING.md) for details on how to submit pull requests.

This project adheres to a code of conduct. By participating, you are expected to uphold this code.

## License

AutoModeler3D is open-source software licensed under the MIT license.