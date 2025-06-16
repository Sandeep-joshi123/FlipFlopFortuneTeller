# 🎰 FlipFlopFortuneTeller

**FlipFlopFortuneTeller** is an innovative, fully hardware-based digital lottery system designed using discrete digital electronics components, without any microcontrollers or software programming. This project showcases the design and implementation of a pseudo-random number generator built with D Flip-Flops configured as a synchronous 4-bit up-counter, driven by a high-frequency clock generated from a 555 timer IC.

The generated number is then compared with a manually preset 4-bit lottery number using a 7485 magnitude comparator IC. Upon a match, the system signals the winner through a green LED, or indicates a loss with a red LED. The clock and result checking operations are controlled via manual switches, making the entire system interactive and purely hardware-dependent.

This project emphasizes core digital logic concepts including Boolean algebra simplification with Karnaugh Maps, truth table analysis, and sequential circuit design. It also includes simulation of the circuit in Proteus IDE before physical implementation on breadboard and custom PCB, ensuring robust performance.

Explore the detailed design methodology, component explanations, wiring diagrams, simulation results, and troubleshooting tips in the project [Wiki](https://github.com/Sandeep-joshi123/FlipFlopFortuneTeller/wiki).

---

*Discover how basic logic elements combine to create a practical and educational lottery system—perfect for learning digital electronics hands-on!*
