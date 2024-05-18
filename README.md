# Swarm Simulation in a Maritime Environment 🌊

This project simulates swarm behavior in a maritime environment using ARGoS and Buzz.

## Dependencies 📦

Ensure you have the following installed:

- [ARGoS](https://www.argos-sim.info/) (Autonomous Robots Go Swarming)
- [Buzz](https://the.swarming.buzz/) (Programming Language for Robot Swarms)

## Installation ⚙️

### Installing ARGoS 🤖

Follow the [official ARGoS installation guide](https://www.argos-sim.info/user_manual.php) to install ARGoS on your system.

### Installing Buzz 🐝

Follow the [Buzz installation guide](https://the.swarming.buzz/ICRA2017/how-to/) to install Buzz.

## Running the Simulation Cases 💻

### Compile the Buzz Controller

First, compile the Buzz controller with the following command:

```bash
bzzc -I [path_to_buzz_includes] [simulation_case].bzz
```

Replace [path_to_buzz_includes] with the path to your Buzz includes and [simulation_case].bzz with the specific simulation case file.

### Run the Simulation

To run the Simulation use the command:

```bash
argos3 -c main.argos
```

Ensure that main.argos is configured correctly for your simulation setup.
