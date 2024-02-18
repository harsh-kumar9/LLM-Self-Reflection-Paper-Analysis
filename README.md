Instruction for running ReflectionQuickTA.Rmd:

1.	Put the datasets
 	“study1_qta_winter_343.csv”
“study2_merged_homework_final_confidence.csv”
 in the same folder with ReflectionQuickTA.Rmd.

2.	Click Run all, it will give you all the plots.

Remark: We use set.seed at the beginning of ReflectionQuickTA.Rmd. This is because we are using the plotting method geom_jitter() which involves randomness for the positions of the dots in the plots. The set.seed in ReflectionQuickTA.Rmd we upload here ensures that it could produce the exact same plots included in the paper. Changing the value of set.seed may give you a different appearance of the plots.

