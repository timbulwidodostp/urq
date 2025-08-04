# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Unconditional Quantile Regression Use urq (uqr) With (In) R Software
install.packages("remotes")
remotes::install_github("cran/uqr")
library("uqr")
urq = read.csv("https://raw.githubusercontent.com/timbulwidodostp/urq/main/urq/urq.csv",sep = ";")
# Estimation Unconditional Quantile Regression Use uqr With (In) R Software
formula = urq ~ urq_
urq = urq(formula, data = urq)
urq$coefficients
urq$tau
# Unconditional Quantile Regression Use urq (uqr) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished
