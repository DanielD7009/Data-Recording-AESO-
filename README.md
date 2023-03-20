# Data-Recording-AESO-
# This file keeps recording the data of electricity generation of each type (solar, gas, hydro, etc.) in Alberta from AESO (Alberta Electric System Operator).
# The data recording starts immediately when running and repeats every hour (3600s).
# The website only allows a limited amount of requests at one time, so if the the gateway is too crowded the program may get an error and stop. To counter this,
# a recurson is added to keep the program trying when the gateway is too crowded.
