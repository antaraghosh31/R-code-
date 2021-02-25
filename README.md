# R-code-
print("hello,world")
[1] "hello,world"
> 2+3
[1] 5
> 50000*84567
[1] 4228350000
> (4000+300)/(90*3)
[1] 15.92593
> x<-3
> x<-2+3
> (x<-2)
[1] 2
> (x<-2+3)
[1] 5
> y=x**4
> (y=x**4)
[1] 625
> x->4+2
Error in 4 + 2 <- x : target of assignment expands to non-language object
> x<-4+2
> nummy <- c(2,3,4)
> nummy_int <- c(1L,2L,3L)
> typeof(nummy)
[1] "double"
> typeof(nummy_int)
[1] "integer"
> is.numeric(nummy)
[1] TRUE
> is.numeric(nummy_int)
[1] TRUE
> is.double(nummy)
[1] TRUE
> types <- c("int","double","character")
> types
[1] "int"       "double"    "character"
> typeof(types)
[1] "character"
> length(types)
[1] 3
> is.character(types)
[1] TRUE
> logicals <- c(TRUE,F,TRUE,T, FALSE)
> logicals
[1]  TRUE FALSE  TRUE  TRUE FALSE
> money_in_chars <- c("15","20","25")
> typeof(money_in_chars)
[1] "character"
> money_money <- as.numeric(money_in_chars)
> money_money
[1] 15 20 25
> typeof(money_money)
[1] "double"
> logicals <- c(money_money)
> logicals
[1] 15 20 25
> as.logical(c(15,20.25))
[1] TRUE TRUE
> month.name
 [1] "January"   "February"  "March"    
 [4] "April"     "May"       "June"     
 [7] "July"      "August"    "September"
[10] "October"   "November"  "December" 
> 1:110
  [1]   1   2   3   4   5   6   7   8   9  10
 [11]  11  12  13  14  15  16  17  18  19  20
 [21]  21  22  23  24  25  26  27  28  29  30
 [31]  31  32  33  34  35  36  37  38  39  40
 [41]  41  42  43  44  45  46  47  48  49  50
 [51]  51  52  53  54  55  56  57  58  59  60
 [61]  61  62  63  64  65  66  67  68  69  70
 [71]  71  72  73  74  75  76  77  78  79  80
 [81]  81  82  83  84  85  86  87  88  89  90
 [91]  91  92  93  94  95  96  97  98  99 100
[101] 101 102 103 104 105 106 107 108 109 110
> month.abb
 [1] "Jan" "Feb" "Mar" "Apr" "May" "Jun" "Jul" "Aug" "Sep" "Oct" "Nov" "Dec"
> month.abb[4:7]
[1] "Apr" "May" "Jun" "Jul"
> month.abb[7,8,12]
Error in month.abb[7, 8, 12] : incorrect number of dimensions
> month.abb[(7,8,12)]
Error: unexpected ',' in "month.abb[(7,"
>  month.abb[c(7,8,12)]
[1] "Jul" "Aug" "Dec"
> days <- c("Mon","Tue","Wed")
> 
> days
[1] "Mon" "Tue" "Wed"
> week_end <- c(days,"Thurs,"Fri,week_end)
Error: unexpected symbol in "week_end <- c(days,"Thurs,"Fri"
> more_days
Error: object 'more_days' not found
