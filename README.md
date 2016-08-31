# vhdl-testbench-generator
Langage : Python2
Author : Proux Alexandre
Date : 2016
Aim : Develop a generic script able to parse a given vhdl file and to generate a testbench skeleton.
Use : $python2.7 tb_gen.py file.vhd
      # This will create a file_tb.vhd
      # You just have to a write testbench scenario (stimulus process) and you should be good to go


Features :
*Recognize Entity
*Recognize Signals
*Instantiate Signals
*Recognize Clock signals
*Recognize Reset signals

Not implemented yet :
*Recognize and instantiate generic
*Regenaration, rewrite all the file but the main stimulus OR rewrite the stimulus with new signals ?



