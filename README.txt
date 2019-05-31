This is a model of a multistage network with stages representing
regions and synaptic contacts from the olfactory cortex to region CA1
of the hippocampus in Brian2 spiking neural network simulator. It is
primarily designed to assess how syanptic facilitation at multiple
stages in response to theta firing changes the output of the
network. Further developments will be posted at:
github.com/cdcox/multistage_network

It is published in the paper "Pronounced differences in signal
processing and synaptic plasticity between piriform-hippocampal
network stages: A prominent role for adenosine". Brian H. Trieu, Eniko
A. Kramar, Conor D. Cox, Yousheng Jia, Weisheng Wang, Christine
M. Gall, and Gary Lynch Journal of Physiology 2015.

This model was prepared by Conor D Cox University of California,
Irvine For questions please contact Conor at cdcox1@gmail.com

What it contains:

1. The model from the paper in a .py file

2. A csv containing the facilitaiton at each point in response to
theta pulsing.

How to use:

1. Unpack the model file and the csv.

2. Run the model, it should generate a figure similar (but not
identical as connections randomize each run) to figure 9 in the above
mentioned paper.

3. synapse_monitor can be used to probe state of individual synapses
throughout firing train.

4. cell_monitor can be used to monitor region specific spiking.
