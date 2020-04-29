# This Map Challenge is made to Update the List of "Stolpersteinen" in Openstreet Maps

The Template is preconfigured with the default values used in most of the already present "Stolpersteinen" in Würzburg.

## Data Quality Review

Overpass API Query:
[Overpass API](https://overpass-turbo.eu/#)

```OverpassQL
area[name="Würzburg"];

node
  ["memorial:type"=stolperstein]
  (area);
out;
```

## Sources

* [Würzburger Stolpersteine](https://stolpersteine-wuerzburg.de/)
* [Wikipedia](https://de.wikipedia.org/wiki/Liste_der_Stolpersteine_in_W%C3%BCrzburg)
