# Diamonds
There is a positive correlation between carat and the price of diamonds
ggplot(diamonds,mapping=aes(x=carat,y=price,color=cut))+geom_point()+geom_smooth(method="lm")
