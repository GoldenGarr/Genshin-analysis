## Parsing data from multiple sources into single Pandas dataframe for future data analysis and predictions

**Featured columns**:

#### Numeric columns:
1. `Character` - Shortened character name (**numpy.object**)
2. `Paired ` - Whether the character was featured in a *paired* banner (**int64**)
3. `Appearances ` - Number of overall reruns (**int64**)
4. `Popularity ` - Character popularity among community (**float64  0...100**)


#### Categorical columns:
1. `Element ` - Character element (Anemo/Pyro/Hydro/Geo/Cryo/Electro)
2. `Weapon ` - Character weapon (Bow/Catalyst/Polearm/Sword/Claymore)
3. `Region ` - The originating region (Mondstadt/Snezhnaya/Liyue/Inazuma)


#### Datetime columns:
1. `Date ` -  Latest rerun date (**datetime64 in nanoseconds**) 
2. `CurrentRerunDelta ` - Days from latest rerun (**timedelta64 in nanoseconds**)
3. `MaxRerunDelta` - Maximal number of days since latest rerun (**timedelta64 in nanoseconds**)