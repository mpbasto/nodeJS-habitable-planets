# Habitable Exoplanets 🌍

Verifying which exoplanets found by Kepler's telescope are habitable, using NodeJS and the csv-parse module.

## Getting Started
### Dependencies

* [NodeJS](https://nodejs.org/en/): 16.14.2
* [csv-parse](https://csv.js.org/parse/): ^5.3.5

### Installation

Use the package manager **npm** to install project dependencies.

```bash
npm install
```

### Get the data
For this project, I used the *KOI Table (Cumulative list)* from the [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=cumulative). 
Download this table in CSV format.

### Criteria
The criteria implemented in this program to consider whether an exoplanet has good habitability conditions reflect those written in the essay [A Review of the Best Habitable Planet Candidates](https://www.centauri-dreams.org/2015/01/30/a-review-of-the-best-habitable-planet-candidates/).

### Output
The output should be present in the [Optimistic Sample of Potentially Habitable Exoplanets](https://phl.upr.edu/projects/habitable-exoplanets-catalog#h.z62ef7783e5) list, with some discrepancies.
