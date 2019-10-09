# AggrePlay
AggrePlay is a pintool created using Intel PIN version 3.0-76991.
Extract the AggreRec folder into the pin/source/tools folder under the Pin directory.

to compile AggrePlay type:

    make AggreRec.wrap

to run AggrePlay:

    Path_to_pin/pin -t Path_to_Pintool/AggreRec.so -o5 output_directory -- Path_to_benchmark
