## This is a markdown file

x.data <- rbind(x.test, x.train)

features <- read.table("features.txt")
colnames(x.data) <- features[[2]]
