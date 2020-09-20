# CSP-PR-ResNet50
--------------------------------------------------------------------------------
CSP is used to detect the center points and scales of a shared salient region. 
Generate  multiple-instance target candidate regions based on redundancy strategy.
 Then used for cyclist and cyclist detection

### Demo and Test
The center point and scale information predicted by the CSP are used as the "RPN" for the candidate region obtained by Monte Carlo sampling into the neural network.

Result image frames:

<img src="./data/output/output_1.png" width = "420" height = "250" align=center />