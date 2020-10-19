# Highly Customizable Robot Simulation @ All Things Open 2020

Presentation about a simulator, from inside the simulator.

## Dependencies

Install dependencies as instructed on their pages

* [Ignition Dome](https://ignitionrobotics.org/docs/citadel)
* [SimSlides](https://github.com/chapulina/simslides/) (use `dome` branch)

## Run presentation

```
git clone https://github.com/chapulina/ATO2020_Ignition
cd ATO2020_Ignition
IGN_GAZEBO_RESOURCE_PATH=`pwd`/models simslides_ignition -r ATO2020.sdf
```

To run with TPE:

```

simslides_ignition -r ATO2020.sdf --physics-engine ignition-physics-tpe-plugin
```
