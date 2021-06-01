# League_api_test
An exploritory analysis of data from the LOL APi 




## methodology

for this analysis I use the LOL API available at https://developer.riotgames.com/, since this is just exploratory this will not cover predictive analysis.  But just looking at the LOL api to learn about API's to sort and work with pandas array.

hopefully to provide a usefull analytics that can be considered for a current site to add to their service, and benifit the players


## results 

so there are definitly sites that already take a look at players statistics, But I wanted to see if there were any charts that would be relevant for players to see and what information that could be gained. and what future analysis could compound on top of.  some data is repetative as found on different sites.

I am using my own personal acount for this analysis, I am a terrible player as much as I think I am good at the game :).  Mostly using simple charts, data manipulation and descriptive statistics.

# the Charts

First I decided to take a simple look at the list of champions that I played this season and the grabbed only the one that I had more than a 50% win rate. That is the first chart; I felt that this is left out of most sites. even tho they post your best champs it does not filter out as simply the number of games played with the specified champs.

So as we can see in the second chart, a cut down version of the data that are just with champions that were played more than Five times.  and this was quiet lucky because it has done a good job of filtering my most used champs.  I would think that this level of analysis would be for optimization.



Champions with above a 50% win rate

	championName	win	assists
0	Ahri	win	100.000000
3	Caitlyn	win	84.210526
5	Draven	win	100.000000
7	Garen	win	94.117647
11	Hecarim	win	100.000000
17	Karthus	win	100.000000
23	Lucian	win	57.647059
27	Malzahar	win	52.422907
29	MasterYi	win	65.217391
33	Nasus	win	52.631579
34	Olaf	win	100.000000
36	Quinn	win	52.631579
40	Samira	win	66.331658
42	Senna	win	60.586797
44	Seraphine	win	67.029973
46	Shyvana	win	100.000000
47	Sona	win	100.000000
49	Soraka	win	85.185185
52	Taric	win	100.000000
53	Tristana	win	100.000000
54	Twitch	win	100.000000
56	Varus	win	84.615385
57	Vayne	win	100.000000
62	Xayah	win	71.428571
64	Yasuo	win	93.548387
66	Yone	win	72.058824


Champions with above a 50% win rate and played more than 5 times

	championName	win	assists
1	Lucian	win	57.647059
3	Malzahar	win	52.422907
5	Nasus	win	52.631579
7	Samira	win	66.331658
9	Senna	win	60.586797
11	Seraphine	win	67.029973
13	Varus	win	84.615385
15	Yone	win	72.058824

