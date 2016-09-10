# vhdl-testbench-generator

##Project Overview

Language : Python2
Author : Proux Alexandre, Digital Designer
Date : 2016
Status : Ongoing development

##Overview
The aim of this project is to develop a generic script able to parse a given vhdl file and  generate a testbench preloaded with entity / signals.

##Use
$python2.7 tb_gen.py file.vhd
* This will create a file_tb.vhd
* You just have to a write testbench scenario (stimulus process) and you should be good to go


##Features :
*Recognize Entity
*Recognize Generics
*Recognize Signals
*Instantiate Signals
*Recognize Clock signals
*Recognize Reset signals

##Not implemented/ Ongoing :
*Testbench Regenaration-> rewrite all the file but the main stimulus OR rewrite the stimulus with new signals.
*Generate basic Modelsim waveform file "wave.do"



