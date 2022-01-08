# Qiskit Starter Repository

## Description

My attempt to learn Qiskit Quantum Computing.

## Usage

Build python virtual environment and install necessary packages

```
    # Make
    python -m venv qiskit-env
    
    # Activate
    .\qiskit-env\Scripts\Activate.ps1
    
    # Install
    pip install -r requirements.txt
```

To use real quantum computer from IBM, we need to get API token to access them. Register to [IBM Quantum](https://quantum-computing.ibm.com/) to get API Token. Save our API Token in new `.env` file located in root. Your `.env` file should look like this.

```
    # file location : /.env
    IBM_TOKEN='paste-your-IBM-token'
```

## References

[1] [Qiskit Website](https://qiskit.org/)

[2] [Qiskit Youtube Channel](https://www.youtube.com/channel/UClBNq7mCMf5xm8baE_VMl3A)