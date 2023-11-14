# Flambegate
Failsafe Highside shutoff FET for 3d printers 
![HighSideFet](https://github.com/Ccecil/Flambegate/assets/1588588/c1255bb0-c71a-46f3-be1e-3e0bb6d962e2)

Flambegate is an attempt at adding hardware failsafes to 3d printers to add a layer of protection above and beyond what the standard hardware does.  This adds a "highside fet control" to the hotend so that it can be shutdown in case of fault.
Can be controlled by "dumb" devices such as my ThermistorComparator board.

-Standalone option via optional 5v Recom regulator
-Safely switches up to ~8a @28v DC
-Inline fuseholder added
-Can use Amass XT30 Horizontal or vertical connectors or bare wires (strain relief holes in board)

Available at: https://www.robosprout.com/product/flambegate-v0-1/
