#read  cat data
cats <- read.csv("data/feline-data.csv")
cats

# one data column
cats$coat
cats$weight + 2
cats$weight
cats$likes_string

cats$coat + cats$weight

typeof(cats$coat)
typeof(cats$weight)
typeof(cats$likes_string)

typeof(1L) #integer
typeof(1) #double
typeof(1 +1i) #complex
typeof(FALSE) #logical
typeof("banana") #character

# factors
cats$coat
str(cats$coat)
levels(cats$coat)
cats$coat <- factor(cats$coat, levels = c("tabby", "calico", "black"))

# lists
list_example <- list(1,"a",TRUE)
list_example

# matrix
matrix_example <- matrix(1:12)
str(matrix_example)
matrix(1:12, ncol=2, byrow = TRUE)
matrix(1:12, ncol=4, byrow = TRUE)

# dataframes
gapminder <- read.csv("data/gapminder-FiveYearData.csv")
str(gapminder)
head(gapminder)
colnames(gapminder)

#subsetting
x <- c(5.4,6.2,7.1,4.8,7.5)
names(x) <- c('a','b','c','d','e')
x
x[1]
x[1:4]
x[c(1,2,1)]
x[-2]
names(x)
names(x) != c('a','b')
names(x) != c('b','a')

names(x) %in% c('b','a')
!names(x) %in% c('b','a')
x[!names(x) %in% c('a','b')]

head(gapminder[3])
head(gapminder[["pop"]])
gapminder[1:3, ]