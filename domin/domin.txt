# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Dominance analysis (DA) Use domin And dominanceanalysis And dominance_analysis With (In) R Software
install.packages("domir")
install.packages("dominanceanalysis")
install.packages("parameters")
install.packages("performance")
library("domir")
library("dominanceanalysis")
library("parameters")
domin = read.csv("https://raw.githubusercontent.com/timbulwidodostp/domin_r/main/domin/domin.csv",sep = ";")
# Estimation Dominance analysis (DA) Use domin And dominanceanalysis And dominance_analysis With (In) R Software
domin(mpg ~ cyl + carb, lm, list("summary", "r.squared"), data = domin)
dominanceanalysis<-lm(mpg ~ cyl + carb,domin)
dominanceanalysis<-dominanceAnalysis(dominanceanalysis)
print(dominanceanalysis)
summary(dominanceanalysis)
dominance_analysis <- lm(mpg ~ cyl + carb, data = domin)
dominance_analysis(dominance_analysis)
# Dominance analysis (DA) Use domin And dominanceanalysis And dominance_analysis With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished