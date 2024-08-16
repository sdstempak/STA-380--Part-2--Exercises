Wrangling the Billboard Top 100
================

### Part A

**Top 10 Most Popular Songs since 1958 by Total Numbers of Weeks spent
on Billboard Top 100**

    ## # A tibble: 10 × 3
    ## # Groups:   performer [10]
    ##    performer                                 song                          count
    ##    <chr>                                     <chr>                         <int>
    ##  1 Imagine Dragons                           Radioactive                      87
    ##  2 AWOLNATION                                Sail                             79
    ##  3 Jason Mraz                                I'm Yours                        76
    ##  4 The Weeknd                                Blinding Lights                  76
    ##  5 LeAnn Rimes                               How Do I Live                    69
    ##  6 LMFAO Featuring Lauren Bennett & GoonRock Party Rock Anthem                68
    ##  7 OneRepublic                               Counting Stars                   68
    ##  8 Adele                                     Rolling In The Deep              65
    ##  9 Jewel                                     Foolish Games/You Were Meant…    65
    ## 10 Carrie Underwood                          Before He Cheats                 64

The table above displays the top ten most popular songs since 1958
measured by the total numbers of weeks spent on Billboard Top 100 chart.
Based on the table produced and our metric for popularity, we can see
that “Radioactive,” by Imagine Dragons, is the most popular song since
1958 with 87 total weeks spent on the Billboard Top 100 chart with the
remaining top 9 songs in the top 10 list ranging from 64 to 79 weeks
spend on the Billboard Top 100 chart since 1958 up until week 22 of 2021
when our data set ends.

### Part B

Below is a times series plot that displays the musical diversity of the
Billboard Top 100 over time. The plot has the number of unique songs in
a year’s Billboard Top 100 songs (y-axis) for every year (x-axis) from
1959 up until 2020.

![](Wrangling_Billboard_files/figure-gfm/billboard%20part%20b%20musical%20diversity%20over%20time%20plot-1.png)<!-- -->

Based on this plot, there are some interesting trends for the number of
unique songs in the Billboard Top 100 songs. In the earlier years of the
data set (1960s), the number of unique songs appear to peak. As our data
set goes past the late 1960s, there is a steady decline in the number of
unique songs by year until the early 2000s. After 2000, the musical
diversity starts to increase with the number of unique songs in the
Billboard Top 100 reaching levels similar to the beginning of our data
set from the 1960s. These trends can be a result of very popular songs
coming out in the 1980s through the early 2000s that stay in the charts
for longer periods of time, making it harder for more unique songs to
make the Billboard Top 100 songs chart.

### Part C

![](Wrangling_Billboard_files/figure-gfm/billboard%20part%20c%20ten-week%20hit%20plot-1.png)<!-- -->

The “Artists with at Least 30 songs that are ‘Ten-Week Hits’” figure
above displays all the artists who have had at least 30 songs that were
“ten-week hits,” which is defined as a single song that appeared on the
Billboard Top 100 for at least ten weeks. The artists’ names are given
on the y-axis and the amount of “ten-week hits” are displayed on the
x-axis.

Based on the results, we can see that Elton John is the artist with the
most ‘Ten-Week Hits’ followed by Madonna and Kenny Chesney.
