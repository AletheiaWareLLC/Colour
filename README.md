Colour
======

Colaborative Colouring

Inspired by Reddit's r/place and Posner & Weyl's Radical Markets, this project explores alternative economic, governance and social structures using colour on a digital canvas.

#Purchasing
 - Free-For-All - All Colours and Locations are free, the most recent Purchase determines the Colour of that Location.
 - Colour Market - An Alias can Purchase a Colour and determine its Location. The Alias pays a 7% Tax on the Purchase price.
 - Radical Colour Market - An Alias can Purchase a Colour and determine its Location and Price. The Alias pays a 7% Tax on the Purchase price. The owner must sell the Colour to any Alias prepared to pay the Price. The owner pays a daily tax (eg. 7%, adjusted +/- 0.1% yearly) proportional to the Colour's Price which is distributed between the Developers and the Aliases.
 - Location Market - An Alias can Purchase a Location and determine its Colour. The Alias pays a 7% Tax on the Purchase price.
 - Radical Location Market - An Alias can Purchase a Location and determine its Colour and Price. The Alias pays a 7% Tax on the Purchase price. The owner must sell the Location to any Alias prepared to pay the Price. The owner pays a daily tax (eg. 7%, adjusted +/- 0.1% yearly) proportional to the Location's Price which is distributed between the Developers and the Aliases.

#Voting
 - One-Alias-One-Vote - An Alias has a single Vote per Location per Day, the Colour with the most Votes determine Colour at that Location.
 - Quadratic Vote - An Alias can Purchase multiple Votes, but the marginal cost grows proportionally to the number of votes cast (ie 1 vote = £1, 2 votes = £4, 3 votes = £9, N votes = £NxN). The Colour with the most Votes determine Colour at that Location.

This project defines the data structures of Colour as protocol buffers (https://developers.google.com/protocol-buffers/), allowing implementations in C, C++, C#, Dart, Go, Java, and/or Python.

Build
=====

    ./build.sh --c_out=<c-output>

    ./build.sh --cpp_out=<cpp-output>

    ./build.sh --csharp_out=<csharp-output>

    ./build.sh --dart_out=<dart-output>

    ./build.sh --go_out=<go-output>

    ./build.sh --java_out=lite:<java-output>

    ./build.sh --python_out=<python-output>
