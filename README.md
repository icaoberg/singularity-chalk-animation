# chalk-animation

Singularity recipe for [chalk-animation-cli](https://github.com/bokub/chalk-animation).

## Building the image using the recipe

### To build the image locally
Run the script `build.sh` to build image locally.

```
bash ./build.sh
```

### Example
```
singularity exec singularity-chalk-animation-1.6.0.sif chalk-animation rainbow Hello world!
```

![Screenshot](/images/screenshot.png)

## Alternative
```
spack install npm
spack load npm
npm install -g chalk-animation
```

---
[![PSC](http://www.andrew.cmu.edu/user/icaoberg/images/logos/psc.png)](http://www.psc.edu)

[icaoberg](http://www.andrew.cmu.edu/~icaoberg) at the [Pittsburgh Supercomputing Center](http://www.psc.edu) in the [Mellon College of Science](https://www.cmu.edu/mcs/) at [Carnegie Mellon University](http://www.cmu.edu).
