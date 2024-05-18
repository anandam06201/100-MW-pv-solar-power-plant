# this files are 100MW solar pwer plant data analysis
#brief description about solar power plant
1.  Each solar module have capacity of 315w 35v and 8.5amps of capacity
2.  One string equlls to 20 modules connected in seris and 2 series coonected modules connected in parallell is given 700v and 
    17amps
3.  Twelve strings are connected to one SMB box
4.  Eight SMB boxes are connected to one Inverter capacity of 1.2 MW dc to 1 MW ac power converting
5.   Four inverters we called one block
6.   Twenty Five  blocks are total plant capacity in the 600 acres of land
     
#data analysis


1. We are taking the data of all strings,smbs,inverters data from scada system(communication system)
2. Daily we did string break downs and low perform smbs,inverters using data analysis
   1.python file:inverter_smb_performance
   2.data:SMB REPORT BLOCK wise
3  We find out the divition in the blocks respected to with their inverters performance using data analysis
   1.python file:KWH_devition,DCtoACdevition
   2.data:INVERTER_15MIN data
4. Daily we find the break down irradition of strings and inverters and it will add in DGR(daily ganeration report) report using data analysis
   1.python file:find_irradition_csvfile,find_irradition_xlsbfile
   2.WMS_REPORT(csv,xlsb files)
