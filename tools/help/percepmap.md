Brand maps based on attribute data can be analyzed using Factor analysis.

<!-- #### Example 1

The city data (city) contains information on distances in miles between 10 major cities in the US. In total 45 distances (10 x 9 / 2) from-to cities are provided. These data are used to illustrate that MDS can take simple data on distances (or on brand similarities as we will see) and use them to create a 2-dimensional map that quite accurately identifies their relative position. 

Click the 'examples' radio button on the Data > Manage page and click 'Load examples' then choose the city data from the Datasets dropdown. The original distances are shown in (lower triangular) matrix form in the figure below. If the analysis is successful we would expect that cities that are close (e.g., Washington DC and New York) should be located close together on the map and cities that are far apart (e.g., Seattle and Miami) should also be positioned far apart in the map.

The basic measure of (lack of) fit for an MDS analysis is call Stress. Stress values of .1 are generally considered fair, .05 is good, and .01 or lower is excellent. High stress values may indicate that a dimensionality of three (or higher) is needed to accurately depict that available data. For the city data the stress value is equal to .006 which is outstanding. 

![mds city - summary](figures/mds_city_summary.png)

The relative locations of Los Angeles, Boston, etc. look wrong. This is due to the fact the MDS program has no information on North, South, East and West. We can ‘flip’ the plot in Radyant to see if the plot becomes easier to recognize and interpret.

![mds city - plots org](figures/mds_city_plots_org.png)

After ‘flipping’ the plot we see that the relative locations look quite good. Note that this map is ‘flat’, i.e., there is no correction for the curvature of the earth.

![mds city - plots flip](figures/mds_city_plots_flip.png)

#### Example 2

The following plot is based on similarity data for a set of toothpaste brands (tpbrands). Respondents were asked the following question: "Please rate the following pairs of toothpaste brands on the basis of their similarity (1 = very similar, 7 = very dissimilar)." for all pairwise combinations of 10 brands, i.e., 45 comparisons. MDS will try to create a made that reproduces as accurately as possible the original dissimilarities (or perceptual distances) provided by the respondent. The original dissimilarity ratings are shown in (lower triangular) matrix form in the figure below. From these data we can already see that the respondents percieves some brands to be very similar (e.g., Crest and Colgate) and others to be very dissimilar (e.g., Dentagard and Aqua Fresh). The stress value for a two-dimensional solution is very good (.092). 

![mds toothpaste - summary](figures/mds_tpbrands_summary.png)

The coordinates shown in the Summary tab are used to plot the brands in two-dimensions in the Plots tab. In the plot we see that Crest and Colgate as well as Ultra Brite and Pepsodent are located very close together. This is consistent with the original data (both pairs were rated '1'). Dentagard and Aqua Fresh, however, are positioned at opposite ends of the plot. Again, this is consistent with the original data providing visual confirmations that MDS was able to create a plot that fits the data well.

From the plot a manager might conclude that the brands that are closest together in the map are percieved are close substitutes and, hence, close competitors on the mind of this consumer. A manager for Aqua Fresh or Macleans, in constrast, might focus less on Dentagrad when developing a competitive positioning plan for her brand. The main limitation of the brand maps based on (dis)similarity data is that the axes are hard to intrepret. Why are Close-up and Aim located at opposite ends of the horizontal axes for example? Research may ask respondents to explain the meaning of the axis or else obtain additional attribute information for the brands and correlate/overlay these on to the plot to vacilitate interpretation.

![mds toothpaste - plots org](figures/mds_tpbrands_plots.png)

-->