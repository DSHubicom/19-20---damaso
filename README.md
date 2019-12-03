# Pylosophorum
Python Orchestrator for the Dámaso project (DSH)

This project contains a Python program that orchestrates different events of the Damaso Ubicom project for the subject Hardware System Description (DSH) using the MQTT protocol.

## Requirements

- Python 3.7+
- Pip for Python 3
- Mosquitto message broker

## Installing Pylosophorum

1. Clone this Git repository.
2. Install packages in `requirements.txt` using Pip.

You can do it easily with these commands (under GNU/Linux):
```bash
git clone https://github.com/StickBrush/Pylosophorum.git
cd Pylosophorum
pip3 install -r requirements.txt
```

## Executing Pylosophorum

1. Run Mosquitto in the background.
2. Run `launch.py`

If you have Mosquitto running in the background already, you can simply do this:

```bash
python3 launch.py
```
