# Charts with SwiftUI

For this app Xcode 11 Beta 4 and MacOS Catalina Beta 4 are required.
 
- Note: I cannot upgrade the code to Xcode Beta 5 and MacOS Catalina Beta 5, 
   because there is a major bug in the Path struct, that will crash any application that uses it. 
   Apple has disclosed the problem in their Release Notes, so I am hopeful they will fix it by the time the next beta arrives.

## One chart is ChartView,
![ChartView](https://bestkora.com/IosDeveloper/wp-content/uploads/2019/07/Screenshot-2019-07-15-at-11.54.23-1.png)

## which consists of:

-  GraphsForChart,
-  YTickerView, 
-  IndicatorView,
-  TickerView, 
-  RangeView, 
-  CheckMarksView.


## Combines several charts in three ways 

- List
- HStack with rotation3DEffect
- ZStack of CardViews

![List](https://bestkora.com/IosDeveloper/wp-content/uploads/2019/07/Screenshot-2019-08-02-at-10.58.34.png)
![HStack with rotation3DEffect](https://bestkora.com/IosDeveloper/wp-content/uploads/2019/07/Screenshot-2019-08-02-at-15.05.42.png)
![ZStack of CardViews](https://bestkora.com/IosDeveloper/wp-content/uploads/2019/07/Screenshot-2019-08-02-at-15.01.38.png)




More to come!


