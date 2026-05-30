<p align="center">
  <img src="https://raw.githubusercontent.com/203x-io/.github/main/profile/banner.png" alt="203x — Performance engineering for the lowest layers of the stack" width="880">
</p>

Most software is written as if the machine were an abstraction. **We work where the abstraction ends** — in the kernel, on the wire, down to the instruction — where latency isn't a number you report but a budget you spend.

### Where we work

- **Kernel & runtime** — the path every request actually takes.
- **Packet & network** — throughput and tail latency on the wire.
- **Instruction & memory** — cache-aware data layout, SIMD, fewer syscalls.

### How we think

- **Measure, never guess.** A flamegraph beats an opinion.
- **Microseconds compound.** At a million requests a second, 5&nbsp;µs is real money.
- **The lowest layer has the most leverage.** Fix it once, and everything above gets faster.
