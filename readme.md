# (Dataset Exploration Title)
## by (your name here)


## Dataset

- the data is about zoonotic notifiable diseases outbreak that is recorded by FAO and could be found [here](http://empres-i.fao.org/eipws3g/)
- the data was downloaded in separate files that were apended to one file and columns were renamed
- all nulls were replaced by Zero

## Summary of Findings

- most of the records of human affected if existed is 1 which is a good thing but most of this column is null and I think null     mean Zero so I filled it with Zero there is also outliers where we have around 500 humans affected which raise a concern we need to see which diseases cause that
- the mode of humans_deaths if existed is 1, some times there is high number of deaths which raise concern we need to see which diseases cause that and most of the column is null which I think mean Zero so I filled it with Zero
- most of sum_cases of animal is less than 10 and the mode is 1 which is a good thing but there is cases where it is too large at 800K and I think those cases are in poultry, we need to see which diseases cause that
- sum_destroyed animals sometimes reach realy high numbers as 3.66 million which raise concerne and I think those cases are in poultry, we need to see which diseases cause that, and I think those nulls mean Zero so I filled them with Zero
- the highest count is for Avian_influenza flowed by African swine fever and viral diseases are the highest incidence
- the highest countries by records count by order are Poland, China and that is expected, Romania, France, Indonesia, Greece, and Egypt
- leptospirosis has the highest number of human cases followed by the same four viral diseases which have the highest number deaths which are japanese encephalitis, MERS-CoV, Avian-Influenza, and Rift Valley Fever
- most diseases have Zero human cases and deaths
- Brucellosis has one case in human which is so weird as I am sure that the number is higher than that by a lot
- there were two high spikes in 2013 in human cases
- Rabies has the highest case fatality for human followed by MERS-CoV
- the highest case fatality is for Schmallenberg followed by Anthrax for animals
- most of the countries have very litle cases and deaths, the highest in cases is Sri Lanka followed by India then Saudi Arabia, the last two metioned are the highest in human deaths with the same order, and I think MERS-CoV is to blame on the high cases and deaths in Saudi Arabia
- some countries have a case fatality of one which is shocking may be there data is not complete
- there are two spikes in the year 2006 and 2012 in sum_cases of animals spikes are caused by poultry diseases mostly
- some diseases have vey high cases and deaths as Avian Influenza and Newcastle disease while most have both of them low but MERS-CoV has zero deaths for animal desbite it's high fatality in humans
- leptospirosis has high humans' incedince and zero deathes desbite being a dangerous disease while japanese encephalitis, MERS-CoV, Avian-Influenza, and Rift Valley Fever have less incedince than it but higher mortality
- both spikes breviously opserved in 2013 are because of leptospirosis mostly
- desbite Sri Lanka having the heighest number of cases it has zero fatality
- countries with high case_fatality have 1 up to 4 cases each which confirm incomplete data even more

## Key Insights for Presentation

- there are two high spikes in 2013 in human cases
- both spikes breviously opserved in 2013 are because of leptospirosis mostly
- there are two spikes in the year 2006 and 2012 in sum_cases of animals spikes are caused by poultry diseases mostly
- leptospirosis has high humans' incedince and zero deathes desbite being a dangerous disease while japanese encephalitis, MERS-CoV, Avian-Influenza, and Rift Valley Fever have less incedince than it but higher mortality
- Rabies has the highest case fatality for human followed by MERS-CoV , Avian-Influenza, and japanese encephalitis

## Design choices

- I decided to use plotly.express for visualization in the slides after using it along with pandas_bokeh in exploration as it is better looking interactive and easy to polish