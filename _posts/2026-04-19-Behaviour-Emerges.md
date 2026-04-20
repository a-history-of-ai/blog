---
title:  "Behaviour Emerges"
layout: post
---

<figure>
    <img src="https://upload.wikimedia.org/wikipedia/commons/7/77/Roomba_time-lapse.jpg"
         alt="Roomba time-lapse showing path traced across a living room floor" 
         height="300">
    <figcaption style="font-size: 10px;">Image: Chris Bartle, <a href="https://creativecommons.org/licenses/by/2.0">CC BY 2.0</a>, via Wikimedia Commons</figcaption>
</figure>

*"The world is its own best model. It is always exactly up to date. It always contains every detail there is to be known."* — Rodney Brooks

---

In 1988, NASA held a workshop on how to explore other planets. The expected answer was one large rover, carefully engineered, remotely controlled from Earth. Rodney Brooks proposed the opposite: swarms of cheap autonomous robots, mass-produced, expendable, no human in the loop. To prove the idea could work, he built a walking robot in twelve weeks with two people and model airplane servos for legs. It now lives in the Smithsonian.

The robot was called Genghis. It weighed under a kilogram and had no central brain. Each leg had its own chip responding directly to the environment through sensors rather than to any central plan. Walking emerged from their interaction even though Brooks had never programmed it. He had designed conditions and the behaviour arose on its own.

Brooks went further and built Herbert, a robot that navigated office corridors, searched for and collected empty cans, with no internal messaging between modules. Each one just acted on what its sensors read directly from the environment. The roots of the idea went back to a trip to Thailand years earlier. Watching insects navigate complex terrain with almost no brain at all, Brooks realised the world was their model.

Brooks called the architecture subsumption. Simple behaviours stacked in layers, each running in parallel, each coupled directly to sensors and actuators. The lowest layer handles obstacle avoidance. A layer above handles wandering. Add wall-following, add room exploration. Each layer is trivial on its own, and none of them knows what the others are doing. Stack them and the robot navigates buildings, finds objects, responds to the unexpected. The intelligence is nowhere in the design and everywhere in the result.

Brooks built the rest of his career on proving the point at scale. Students he trained went on to lead robotics research across academia and industry, and the subsumption architecture found its way into military systems, collaborative manufacturing and consumer products. The Roomba, a robotic vacuum cleaner launched in 2002, is the most tangible proof. It works by layering simple behaviours, not by having a map of the room. That stacking of simple behaviours is at work in over twenty-five million homes.

Before Brooks, the conventional wisdom in AI was that you had to understand intelligence before you could build it. Brooks thought the order was wrong and is still working to prove it. The best way to understand intelligence is to build something and see if it acts intelligently. That pragmatic test is still the most useful one we have when applying AI to real problems. If it behaves intelligently, that's enough. The rest is philosophy.

---

## Further Reading

- Brooks, R. A. (1986). ["A Robust Layered Control System for a Mobile Robot." IEEE Journal of Robotics and Automation, 2(1), 14–23.](https://people.csail.mit.edu/brooks/papers/AIM-864.pdf)

- Brooks, R. A., & Flynn, A. M. (1989). ["Fast, Cheap and Out of Control: A Robot Invasion of the Solar System." Journal of the British Interplanetary Society, 42, 478–485.](https://people.csail.mit.edu/brooks/papers/fast-cheap.pdf)

- Brooks, R. A. (1991). ["Intelligence Without Representation." Artificial Intelligence, 47(1-3), 139–159.](https://people.csail.mit.edu/brooks/papers/representation.pdf)
