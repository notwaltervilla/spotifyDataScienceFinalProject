Final Report - Spotify and Billboard Rankings
================
Alison and Walter Villa
2020-12-15

  - [Purpose:](#purpose)
  - [Background:](#background)
  - [Data:](#data)
  - [Including Plots](#including-plots)

## Purpose:

What song attributes lead towards success on the Billboard charts?

## Background:

Each year, new songs emerge and become some of the year’s top hits.
Whether it’s because of a viral video or a certain time of year, new
songs seem to become popular overnight. The Billboard charts are a place
in which songs and albums are ranked based on their weekly popularity in
the United States. The charts can be ranked in categories such as sales,
streams, or airplay. All three of these categories are used to compile
the Hot 100 song chart, including data that come from YouTube and other
video streaming sites.

In 2005, Billboard made the change to include paid digital downloads
from digital music retail stores like AmazonMP3 and iTunes. This meant
that a song was able to make it onto the charts based solely on digital
downloads. In 2007, it incorporated digital streams into the Top 100.
Over the years, Billboard’s methodology changed in ways that would allow
different types of genres to gain a position on the charts through
digital downloads and streaming plays. It’s most recent change has had
major impact in how songs were ranked on the billboard charts. This
change had to do with YouTube video streaming data, which enhanced a
formula that incorporates on-demand audio streaming and online radio
streaming. Billboard made this change in order to reflect the diverse
music consumption platforms of today’s day and age.

Spotify is a Swedish audio streaming and media services provider. Having
come out in the early 2000’s, it offers millions of digital copyright
music and podcasts. While free service allows you to listen to songs
alongside advertisements, paid subscriptions offer easier accessibility
and more features for users. People from all around the world are able
to listen to the latest trending songs on the platform. Interestingly
enough, Spotify stores certain features for different songs, which is
useful information for noticing certain trends in the type of songs that
perform a certain way. On January 3, 2020, Billboard made the decision
to count the popularity of official music videos on YouTube, as well as
on streaming platforms like Apple Music, Spotify, Tidal, and Vevo into
the Billboard 200, according to the New York Times. As a group, we
wanted to investigate any potential patterns or trends in songs landing
on the Billboard charts in correlation to Spotify’s top tracks.

## Data:

Our data is composed of Spotify’s top songs by year in the world and top
songs ranked on the Billboard charts. The Spotify dataset contains
several variables corresponding to each song’s features (i.e genre, bpm
\[beats per minute\], energy, liveness, etc) defined by Spotify itself.
The Billboard dataset contains values from each track pulled from the
Spotify Web API to be able to have information on each track listed on
the Billboard charts.

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](finalprojectdoc_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.