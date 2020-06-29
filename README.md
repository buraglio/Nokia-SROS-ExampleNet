# Nokia-SROS-ExampleNet

### Nokia PCE Segment Routing testing
Included here are the Test configurations for PCE testing with Nokia SROS as well as the Topology and Eve-NG Lab XML File. This repo consists of a 4 Router Lab utilizing Nokia SROS 14 for testingo. 

### Files and such

1. flatten.sh - A script that takes the SROS configuration and converts it to a paste-able, flattened format. Requires https://github.com/door7302/transcode-sros
2. files named .flat.txt - flattened filed produced by the above script
3. vsr* Nokia SROS configurations as stored in the flash. Usable in the "startup configuration" for Eve-NG
5. Nokia PCE Lab.unl - the Eve-NG XML file that is the lab -- TO BE ADDED

### Diagrams and physical layout

The Physical layout of this test environment is detailed in this diagram. This was built on EVE-NG bare metal server with significant horsepower. 
![Physical lab Topology](https://github.com/buraglio/Nokia-SROS-ExampleNet/blob/master/Network%20Diagram.png?raw=true "Physical Lab Topology")
