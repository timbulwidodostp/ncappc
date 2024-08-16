# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# NCA Calculations and Population Model Diagnosis Use ncappc With (In) R Software
install.packages("ncappc")
library("ncappc")
ncappc = read.csv("https://raw.githubusercontent.com/timbulwidodostp/ncappc/main/ncappc/ncappc.csv",sep = ";")
# Estimation NCA Calculations and Population Model Diagnosis Use ncappc With (In) R Software
ncappc <- ncappc(obsFile=ncappc, onlyNCA = T, extrapolate = T, printOut = F, evid = FALSE, noPlot = T)
# AUClast
ncappc$ncaOutput$AUClast
# AUCINF_pred
ncappc$ncaOutput$AUCINF_pred
# Cmax
ncappc$ncaOutput$Cmax
# Tmax
ncappc$ncaOutput$Tmax
# NCA Calculations and Population Model Diagnosis Use ncappc With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished