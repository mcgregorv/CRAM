Chatham Rise Atlantis Model 1900-2016 with a 35 year burnin (starts 1865) with or without historical fishing forced
Included are all the inputs required to run the model, but not the Atlantis source code - you would need to get that from CSITO
#
#Atlantis2 Updated to Version 6262M
#Atlantis path https://svnserv.csiro.au/svn/ext/atlantis/Atlantis/trunk/atlantis
#Atlantis SVN Last Change Date 2017-11-29 18:28:29 +1300 (Wed, 29 Nov 2017)
#
Included are the outputs from the model runs, including those from the species group interaction simulations, and the bootstrap ROMS simulations (in the outputs folder)
#
The input files for the ROMS bootstrap simulation and the species interaction simulations are in InputAndRun\________________ and and inputAndRun\InteractionSims 
#
Initial conditions for the model, they are in InputAndRun\CRAM_input_short.nc
#
The forced catch histories are in the .ts files catch_history\catchts_Burnin1865
#
The biological parameters are in CRAM_BH_hybrid_biol.prm
#
The ROMS oceanographic variables are in inputs\ROMS
#
There is an additional diet summary .csv file in outputs\Historic_withFishing_outputDietSummary.csv
#
All R scripts are included and should be fairly self explanatory by the script names
