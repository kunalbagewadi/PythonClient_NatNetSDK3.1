# PythonClient
NatNet SDK 3.1 Samples' PythonClient example with Motive 2.1
It has some modification from original SDK here: https://optitrack.com/products/natnet-sdk/

Edit trace() def in NatNetClient.py to use print()
Use NAT_REQUEST_MODELDEF in NatNetClient.py-> self.sendCommand() call to see names of rigid bodies, skeletons.
Use NAT_PING in NatNetClient.py-> self.sendCommand() call to receive mo-cap data. Tested with rigid bodies and skeleton (upper body markerset with 25 markers)

Run command:
python3.6 PythonSample.py 
