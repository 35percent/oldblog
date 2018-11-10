---
layout: post
title: '11000 new council homes: figures show net loss rather than gain'
subtitle: >-
  Southwark demolishing and selling off council homes faster than it is building
  them
published: false
---
In 2014, as part of its manifesto pledge Southwark Council's administration [announced](http://www.southwarklabour.co.uk/latest-news/southwark/news.aspx?p=102262) an _"ambitious but realistic plan to build 11,000 new council homes"_ across the borough over the next 30 years. Concerns were [raised by us](http://35percent.org/the-southwark-clearances) and in the [local press](https://crappistmartin.github.io/images/SNHeygateOverage.pdf) that this would fail to make up for the thousands of council homes currently being lost to ongoing estate regeneration, void disposal polices and Right to Buy applications over the next 30 years.

![](https://crappistmartin.github.io/images/SN1100homes.png)
*Extract from an [Oct 2014 article in the local newspaper](https://crappistmartin.github.io/images/SNHeygateOverage.pdf)*

Council leader Peter John subsequently issued an [open letter](http://35percent.org/img/pj11000councilhomesletter.pdf) insisting that the 11,000 council homes would be over and above the existing stock count - i.e. a net increase:

![](http://35percent.org/img/pj11000councilhomesletter.png)
*Extract from Council leader Peter John's [open letter](http://35percent.org/img/pj11000councilhomesletter.pdf)*

Councillor John went one step further to pledge that the first 1500 net additional council homes would be finished by 2018:

![](http://35percent.org/img/1500councilhomes.png)
*Extract from [2014 Cabinet report](http://moderngov.southwark.gov.uk/documents/s47488/Report%20Long%20term%20plans%20for%20the%20delivery%20of%20new%20council%20homes.pdf)*

Four years on and we have taken a look at whether Councillor John has delivered on his manifesto pledge. [Official statistics](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/674346/LT_116.xlsx) from the government's [live tables](https://www.gov.uk/government/statistical-data-sets/live-tables-on-dwelling-stock-including-vacants) on local authority dwelling stock show that since the manifesto pledge in 2014 there has been a net reduction in Southwark's council housing stock of 476 council homes.

![](http://35percent.org/img/livetableextract.png)
*Extract from the government's [Live Table 116](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/674346/LT_116.xlsx)*

The figures aren't saying that Southwark hasn't built any new council homes, only that the rate at which is building has not kept up with the rate at which it is knocking them down and selling them off. The Council has or will demolish [over 7,500 council homes](http://35percent.org/the-southwark-clearances/) as part of regeneration schemes, including  1200 council homes in the [Heygate estate regeneration](http://35percent.org/heygate-regeneration-faq/) and circa 2400 on the  [Aylesbury estate](http://35percent.org/aylesbury-estate/).

In addition, it has [sold 1300 council homes under the Right to Buy since 2012](https://www.insidehousing.co.uk/comment/comment/how-we-will-attempt-to-restrict-high-rents-on-right-to-buy-re-lets-58865) and has an [ongoing policy](http://35percent.org/the-southwark-clearances/#void-disposal-policy) of selling every council home that becomes vacant which is valued at £300k or more.

Meanwhile, this [30th Oct 2018 Cabinet report](http://moderngov.southwark.gov.uk/documents/s78248/Report%20New%20Homes%20Programme%20Delivery%20Model%20Review%202018.pdf) confirms that the council has built just 262 council homes over 5 years (para 12).  

An additional 239 units of developer-built (S106) affordable housing has been bought by Southwark, to be council housing. A problem with this method of delivering new council housing, rather than building it yourself (and regardless of relative costs), is that it does not actually increase the net supply of social housing - the same units would otherwise be have been bought and let by a housing association anyway.  Further, and perversely, Southwark is denying itself the benefit of the S106 contribution, by paying for something a housing association would have paid for and further yet, denying itself funds for building units that would increase the net supply.

It is also not clear whether these have all been let at council rents. The [appendix](http://moderngov.southwark.gov.uk/documents/s78251/Appendix%202%20Map%20showing%20approved%20schemes.pdf) to the Cabinet report lists the council homes simply as 'rented units'. We have [blogged previously](http://35percent.org/2017-04-29-blackfriars-affordable-housing-circus/#10m-wasted-and-new-council-homes-not-even-social-rent) about new 'council homes' now being let at a percentage of market rent (40%) rather than social rent (which is currently approx 20% of market rent). 

In addition, 112 of these new 'council homes' are temporary accommodation units in hostels (_Willow Walk_ - 75 units, _Good Neighbours House_ - 37 units) and are [let](http://moderngov.southwark.gov.uk/documents/s65880/Temporary%20Accommodation%20Report.pdf) at [LHA rent levels](https://lha-direct.voa.gov.uk/SearchResults.aspx?LocalAuthorityId=28&LHACategory=999&Month=10&Year=2018&SearchPageParameters=true), which are more than twice current council rent levels.

![](http://35percent.org/img/lharates.png)

Even if we count all these new homes as council homes at council rents, the short and long term trend is clearly one of a ongoing decline in the number of council homes:

<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js">
</script>
<script src="http://code.highcharts.com/highcharts.js">
</script>
<script src="http://code.highcharts.com/modules/exporting.js">
</script>

<div id="container" style="min-width: 310px; height: 400px; margin: 0 auto">
</div>

<script type="text/javascript">

        $('#container').highcharts({
            title: {
                text: "Southwark's Council Homes",
                x: -20 //center
            },
            subtitle: {
                text: 'Source: https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/674346/LT_116.xlsx',
                x: -20
            },
            xAxis: {
                categories: ['1994', '1995', '1996', '1997', '1998', '1999',
                    '2000', '2001', '2002', '2003', '2004', '2005', '2006', '2007', '2008', '2009', '2010', '2011', '2012', '2013', '2014', '2015', '2016', '2017']
            },
            yAxis: {
                title: {
                    text: 'Council-owned stock'
                },
                plotLines: [{
                    value: 0,
                    width: 1,
                    color: '#808080'
                }]
            },
            tooltip: {
                valueSuffix: ' Council homes'
            },
            legend: {
                layout: 'vertical',
                align: 'right',
                verticalAlign: 'middle',
                borderWidth: 0
            },
            series: [{
                name: 'Southwark',
                data: [55803, 55162, 54439, 53363, 52448, 51706, 50903, 49875, 48052, 46887, 45346, 43885, 42275, 41873, 41287, 40618, 40120, 39845, 39781, 38578, 39029, 38687, 38522, 38553]
            }]
        });

</script>

Conscious of its manifesto commitment and failure to build the number of new homes promised, Southwark is now turning to a different strategy - buying section 106 homes from developers. These are the rented element of affordable homes in new developments that a developer is obliged to build in accordance with planning policy.

One such example is Blackfriars Circus, where the Council has [bought](http://35percent.org/2017-04-29-blackfriars-affordable-housing-circus/) 56 homes for £10m from developer Barratt.

![](http://35percent.org/img/tweetmwilliamsblackfriars.png)

A [recent Cabinet report](http://moderngov.southwark.gov.uk/documents/s78248/Report%20New%20Homes%20Programme%20Delivery%20Model%20Review%202018.pdf) confirms that the Council has bought 239 such properties from developers to date (paragraph 17), with 80 more purchases in the pipeline. 

We say that by buying up section 106 properties Southwark Council is not adding to the amount of social housing stock in the borough. It is simply buying homes that already exist and that housing associations would have otherwise bought and let as social housing. An added effect is that this increases the competition for S106 housing driving up the price - developers are rubbing their hands.. etc etc
