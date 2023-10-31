
Hi there 👋

Here's an overview of a few of my open source projects. I think those listed here add value  unique at least in some ways (eg. not just apply existing techinque X for random problem Y).

### pytest-visual - visual testing for ML

This library takes a novel approach at testing ML code - in addition to writing traditional tests with assert statements, you can also add visualizations to your tests. These visualizations are cached, and when running tests, only those changed will be displayed. This will greatly expand the amount of functionality that can be meaningfully tested, such as data augmentation, neural network architectures and output processing.

### PhaseTransition (60k Youtube views, >99% like/dislike ratio) - a 2d particle physics simulator with good visualization and high performance integrator

See this demo [video](https://www.youtube.com/watch?v=SFf3pcE08NM), a lot of people find it pretty cool.

An interesting achievement that I haven't so clearly seen in other simulations is the emergent solid-like, liquid-like, and gas-like states. Each can be identified just as you would in real life:
* solid-like state = particles form a clear structure, and it resists external forces
* liquid-like state = particles don't form a structure, but they have a roughly fixed density.
* gaseous-like state = particles move randomly, at a completely non-fixed, but low density

The states depend on the temperature of the matter.

### fire-hpp (400+ github stars) - using clever tricks in C++ to achieve super low-code command line argument parsing

Here's the whole program for adding two numbers from command line with this library:

```c++
#include <iostream>
#include <fire-hpp/fire.hpp>

int fired_main(int x = fire::arg("-x"), int y = fire::arg("-y")) {
    std::cout << x + y << std::endl;
    return 0;
}

FIRE(fired_main)
```

Usage:
```bash
$ ./add -x=1 -y=2
3
```

This program has all the bells and whistles that you need for a CLI, such as automatic `--help` messages with type information, and proper error handling.

## Contact

For business/contract/employment queries, please message on [Linkedin](https://www.linkedin.com/in/kristjan-kongas-8030b2254/). You can also contact me using the method described [here](https://stackoverflow.com/a/44229207).

I'll 100% try to answer :).
