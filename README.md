# Informe_taller_intermedio_Marina_Figueiredo

Informe para el taller intermedio 2025

Test de informe Más un test

plot(2,3)

setwd("C:/Users/icaro/OneDrive/PC Marina/UEMA/cursos/Ocean Hack Week") 

getwd 

scolias.dat <- read.csv("colias.csv", header = TRUE,dec = ".", sep = ";") 

summary(scolias.dat) names(scolias.dat)

# transformacion de variables categóricas

# as.character cuando son valores textuales

# as.factor cuando son valores únicos y quiero realizar algún análisis categórico

scolias.dat$fishID <- as.character(scolias.dat$fishID) scolias.dat$year <- as.factor(scolias.dat$year) scolias.dat$month <- as.factor(scolias.dat$month) scolias.dat$survey <- as.character(scolias.dat$survey) scolias.dat$sex <- as.character(scolias.dat$sex) scolias.dat$age <- as.factor(scolias.dat$age) scolias.dat$MatMacro <- as.factor(scolias.dat$MatMacro) scolias.dat$MATogMacro <- as.factor(scolias.dat$MATogMacro) scolias.dat$histoID <- as.character(scolias.dat$histoID) scolias.dat$MatMicro <- as.factor(scolias.dat$MatMicro) scolias.dat$MATogMicro <- as.factor(scolias.dat$MATogMicro) scolias.dat$date <- as.Date.character(scolias.dat$date)
