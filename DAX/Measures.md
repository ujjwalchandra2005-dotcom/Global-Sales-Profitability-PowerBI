# DAX Measures

## Total Sales
```DAX
Total Sales = SUM(Sales_Data[Sales])
```

## Total Profit
```DAX
Total Profit = SUM(Sales_Data[Profit])
```

## Total COGS
```DAX
Total COGS = SUM(Sales_Data[COGS])
```

## Total Units Sold
```DAX
Total Units Sold = SUM(Sales_Data[Units_Sold])
```

## Profit Margin %
```DAX
Profit Margin % =
DIVIDE(
    [Total Profit],
    [Total Sales],
    0
)
```

## Average Sale Price
```DAX
Average Sale Price =
AVERAGE(Sales_Data[Sale_Price])
```

## Total Discount
```DAX
Total Discount =
SUM(Sales_Data[Discounts])
```

## Total Gross Sales
```DAX
Total Gross Sales =
SUM(Sales_Data[Gross_Sales])
```

## Sales LY
```DAX
Sales LY =
CALCULATE(
    [Total Sales],
    SAMEPERIODLASTYEAR(Date_Table[Date])
)
```

## Sales Growth %
```DAX
Sales Growth % =
DIVIDE(
    [Total Sales] - [Sales LY],
    [Sales LY],
    0
)
```

## Profit LY
```DAX
Profit LY =
CALCULATE(
    [Total Profit],
    SAMEPERIODLASTYEAR(Date_Table[Date])
)
```

## Profit Growth %
```DAX
Profit Growth % =
DIVIDE(
    [Total Profit] - [Profit LY],
    [Profit LY],
    0
)
```

## YTD Sales
```DAX
YTD Sales =
TOTALYTD(
    [Total Sales],
    Date_Table[Date]
)
```

## YTD Profit
```DAX
YTD Profit =
TOTALYTD(
    [Total Profit],
    Date_Table[Date]
)
```
