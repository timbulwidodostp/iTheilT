# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Individual decomposition of Theil's T Index Use iTheilT With (In) R Software
install.packages("iIneq")
library("iIneq")
iTheilT = read.csv("https://raw.githubusercontent.com/timbulwidodostp/iTheilT/main/iTheilT/iTheilT.csv",sep = ";")
# Estimation Individual decomposition of Theil's T Index Use iTheilT With (In) R Software
weight <- iTheilT$weight
Diet <- iTheilT$Diet
iTheilT <- iTheilT(weight, Diet)
head(iTheilT, 36)
# Individual decomposition of Theil's T Index Use iTheilT With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished