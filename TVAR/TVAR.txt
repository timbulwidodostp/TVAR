# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Threshold Vector Autoregressive (TVAR) model Use TVAR With (In) R Software
install.packages("tsDyn")
library("tsDyn")
TVAR = read.csv("https://raw.githubusercontent.com/timbulwidodostp/TVAR/main/TVAR/TVAR.csv",sep = ";")
# Estimation Threshold Vector Autoregressive (TVAR) model Use TVAR With (In) R Software
TVAR <- TVAR(TVAR, lag=2, nthresh=2, thDelay=1, trim=0.1, mTh=1, plot=FALSE)
print(TVAR)
summary(TVAR)
# Threshold Vector Autoregressive (TVAR) model Use TVAR With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished