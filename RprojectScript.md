```{r}
# Remove  all objects from R memory 
rm(list=ls())  

# Set a path to the library containing packages
.libPaths("C:/Computerteknologi/10_semester/Rcourse")
.libPaths()


# Load selected packages# 
pack<-c("car","sandwich","lmtest","RColorBrewer","mgcv","foreign","xtable"
        ,"AER","stargazer", "MASS")

lapply(pack, require, character.only=T)

# Check the working path
getwd()

# Specify  paths
getwd()

# Set working path
data_path<-"C:/Computerteknologi/10_semester/Rcourse/project/data"
data_graph <-"C:/Computerteknologi/10_semester/Rcourse/project/graph"
data_results <-"C:/Computerteknologi/10_semester/Rcourse/project/result"
data_scripts <-"C:/Computerteknologi/10_semester/Rcourse/project/script"
setwd(data_path)

#Check the directory
dir()
```
