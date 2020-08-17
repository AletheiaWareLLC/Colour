Colour
======

Inspired by Reddit's r/place and Posner & Weyl's Radical Markets, this is an exploration of Colour and Economics through Collaborative, Blockchain-Backed, Digital Canvases.

This project defines the data structures of Colour as protocol buffers (https://developers.google.com/protocol-buffers/), allowing implementations in C, C++, C#, Dart, Go, Java, and/or Python.

## Rules

A Domain hosts a Digital Canvas and each Pixel has a Location, Colour, and Value.

Visit the Domain to see the rendered Canvas.

An Alias can register with a Domain and subscribe to a Canvas to become a Painter.

## Modes

### Anarchy

A Painter may change the Colour of any Pixel at any time.

### Democracy

A Painter may cast a single Vote on the Colour of any Pixel, the Colour with the most Votes is rendered.

### Market

A Painter can pay the Pixel Value to the Pixel Owner to become the Pixel Owner and set the Pixel Colour and Value.

Initially the Digital Canvas Creator owns every Pixel.

### Radical Democracy

Like Democracy, but a Painter may cast multiple Votes on the Colour of any Pixel where each Vote costs double the previous. The Colour with the most Votes is rendered.

### Radical Market

Like Market, but the Pixel Owner pays a Daily Tax on the Pixel Value;
- 2% to Canvas Creator
- 3% to all Pixel Owners
- 4% to all Painters

// TODO How to prove Painter paid? If an Painter doesn't pay, their participation is not considered in rendering.

Build
=====

    ./build.sh --c_out=<c-output>

    ./build.sh --cpp_out=<cpp-output>

    ./build.sh --csharp_out=<csharp-output>

    ./build.sh --dart_out=<dart-output>

    ./build.sh --go_out=<go-output>

    ./build.sh --java_out=lite:<java-output>

    ./build.sh --python_out=<python-output>
