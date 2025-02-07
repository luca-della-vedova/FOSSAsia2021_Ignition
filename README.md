# Next gen robotics simulation with Ignition Gazebo @ FOSSAsia Summit 2021

Presentation about a simulator, from inside the simulator.

## Dependencies

Install dependencies as instructed on their pages

* [Ignition Dome](https://ignitionrobotics.org/docs/dome)
* [SimSlides](https://github.com/chapulina/simslides/tree/dome)
    * use `dome` branch

## Run presentation

```
git clone https://github.com/luca-della-vedova/FOSSAsia2021_Ignition
cd FOSSAsia2021_Ignition
simslides_ignition -r FOSSAsia.sdf
```

To run with TPE:

```

simslides_ignition -r FOSSAsia.sdf --physics-engine ignition-physics-tpe-plugin
```
