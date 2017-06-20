# R-Prog
Try this this will show the variable names
# store the variable names into headers
headers = read.csv("IMDB_data.csv", skip = 0, header = F, nrows = 1, as.is = T)  
# read the data file by skipping second row
df = read.csv("IMDB_data.csv",skip = 3, header = F)
# add headers to data
colnames(df)=headers 
