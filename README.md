# Spinal Top

Spinal Top is a fork of [procps](https://gitlab.com/procps-ng/procps) with a patched `top(1)` that allows the server to be 10% busier.

This utility is very special, because if you can see, CPU percentages in this tool go up to 110%, right across the board. This is 10% busier, isn't it. Is not 100%.

You see, in many datacenters server CPUs go all the way up, all the way up to 100%. Where can you go from there? Nowhere! Exactly!

What this tool does is, when the server is computing a Fibonacci number and needs that extra push over the cliff, you know what you do? 110%, exactly, 10% busier.

