mass <- 47.5
age <- 122
mass <- mass * 2.3
age <- age - 20
mass > age

quiz_vector_1 <- c(2,6, '3')
quiz_vector_2 <- c('a', TRUE)
quiz_vector_3 <- c(0, TRUE)
typeof(quiz_vector_1)
typeof(quiz_vector_2)
typeof(quiz_vector_3)
quiz_vector_4 <- c('yes', 2, 2.5, TRUE)
quiz_vector_4
quiz_vector_5 <- c( 2, 2.5, TRUE)
quiz_vector_5
typeof(quiz_vector_5)
quiz_vector_6 <- c( 1L, TRUE)
quiz_vector_6
typeof(quiz_vector_6)

#to extract observations collected in 1957
gapminder[gapminder$year = 1957, ] # must use ==
gapminder[gapminder$year == 1957, ]

#to extract all columns except 1 through 4
gapminder[,-1:4] #negative column numbers don't exist
gapminder[,-c(1:4)]

#extract the rows where life expectancy is longer than 80 yrs
gapminder[gapminder$lifeExp > 80] # need a comma for column indices!
gapminder$lifeExp > 80
gapminder[gapminder$lifeExp > 80, ]

# extract the first row and fourth and fifth columns (continent and lifeExp)
gapminder[1, 4, 5] #Just returns [1,4] and ignores 5
gapminder[1, 4]
gapminder[1,c(4,5)]
