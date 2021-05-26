#Working notebook is this:  I am working on discharge dataset, trying to reduce val_loss, and it did worked for now, reduced to:
# 0.0230 from 0.45 something, so reduced of a order of magnitude, just by scaling from (0,1) instead of (-1,1). 
#DL_dischargeIncreasedFeatures.ipynb


# DL_ChrDisAsOneDataSet, take sine dataset, added features - entropy, availability, flow for charge and discharge both.Very low val_loss



# DL_tryingWholeDataChargeDisCharWithAvailaEntropAndZeroInputToNN does seperatly for charge and sischage, takes entropy and flow but seperatly-
#charging is very clean, discharging is 0.04 something val_loss
#

#maybe I should get a data which take is multiple charge and discharge to run DL for figures
