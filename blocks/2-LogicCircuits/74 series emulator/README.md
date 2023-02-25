# IceChips TTL Standard Parts Collection

[![Icestudio](https://img.shields.io/badge/collection-icestudio-blue.svg)](https://github.com/FPGAwars/icestudio)
![Version](https://img.shields.io/badge/version-v0.9.2-orange.svg)

All common discrete logic devices for use in Icestudio

## Install

* Download the collection: [Latest Release](https://github.com/TimRudy/ice-chips-verilog/releases/latest)
* Install the collection: *Tools > Collections > Add*
* Load the collection: *Select > Collection*

## Blocks

* ***Combinational***

  * ***Buffers, Inverters***
    * 7404 Hex inverter
    * 7407 Hex buffer/driver (OC)

  * ***Gates***
    * 7400 Quad 2-input NAND gate
    * 7402 Quad 2-input NOR gate
    * 7408 Quad 2-input AND gate
    * 7432 Quad 2-input OR gate
    * 7486 Quad 2-input XOR gate
    * 74266 Quad 2-input XNOR gate (OC)

  * ***Gates 3+***
    * 7410 Triple 3-input NAND gate
    * 7411 Triple 3-input AND gate
    * 7420 Dual 4-input NAND gate
    * 7421 Dual 4-input AND gate
    * 7427 Triple 3-input NOR gate
    * 7430 8-input NAND gate
    * 74260 Dual 5-input NOR gate

  * ***Decoders***
    * 7442 BCD to decimal one-of-ten decoder

  * ***Encoders***
    * 74147 10-line to 4-line priority encoder
    * 74148 8-line to 3-line priority encoder

  * ***Demultiplexers***
    * 74138 3-line to 8-line decoder/demultiplexer (inverted outputs)
    * 74139 Dual 2-line to 4-line decoder/demultiplexer (inverted outputs)
    * 74154 4-line to 16-line decoder/demultiplexer (inverted outputs)
    * 74155 Dual 2-line to 4-line decoder/demultiplexer (inverted outputs)
    * 74238 3-line to 8-line decoder/demultiplexer (active high outputs)

  * ***Multiplexers***
    * 74150 16-input multiplexer
    * 74151 8-input multiplexer
    * 74153 Dual 4-input multiplexer
    * 74157 Quad 2-input multiplexer
    * 74158 Quad 2-input multiplexer (inverted outputs)
    * 74352 Dual 4-input multiplexer (inverted outputs)

  * ***Comparators, Adders, ALUs***
    * 7485 4-bit magnitude comparator
    * 74181 4-bit arithmetic logic unit
    * 74283 4-bit binary full adder with fast carry

* ***Sequential***

  * ***Flip-Flops***
    * 7473 Dual J-K flip-flop with clear; negative-edge-triggered
    * 7474 Dual D flip-flop with set and clear; positive-edge-triggered
    * 74112 Dual J-K flip-flop with set and clear; negative-edge-triggered

  * ***Registers***
    * 74273 Octal D flip-flop with clear
    * 74377 Octal D flip-flop with enable

  * ***Counters***
    * 74160 4-bit BCD decade counter with parallel load, asynchronous clear
    * 74161 4-bit modulo 16 binary counter with parallel load, asynchronous clear
    * 74162 4-bit BCD decade counter with parallel load, synchronous clear
    * 74163 4-bit modulo 16 binary counter with parallel load, synchronous clear

## Authors

* [Tim Rudy](https://github.com/TimRudy)

## License

Licensed under [GPL-3.0](https://www.gnu.org/licenses/gpl)
