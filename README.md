# Factorio Train Scheduler

Until Factorio 2.0, there is no way to redirect trains to refueling station when fuel is running out, so ideally you would need to loop load-unload cycles manually.
This tool is designed to help automate the creation of train schedules with multiple delivery cycles in mind.

## Features

- **Train Station Input**: specify names for loader, unloader, and refueling stations
- **Delivery Count**: set the number of times a train should go through the specified schedule before refueling
- **Blueprint Generation**: generates a Factorio blueprint string based on the provided inputs

## To-Do:

- **Fuel Type Selection**: Choose the type of fuel for the train (train will be loaded by robots)
- **Custom Wait Conditions**: Instead of waiting for full cargo, wait for e.g. 2000 space science packs

## Usage

To use the Factorio Train Scheduler, follow these steps:

1. Open the `index.html` file in a web browser
2. Enter the names of the loader, unloader, and refueling stations (Factorio icons supported, just copy&paste from ingame)
3. Specify the number of deliveries before refueling is needed
4. Click on the "Generate" button to create the blueprint string
5. Blueprint string is already in clipboard

## Installation

No installation is necessary. Just clone this repository and open `index.html` in your web browser.

```bash
git clone https://github.com/yourusername/factorio-train-scheduler.git
```

Or download this repo directly instead.