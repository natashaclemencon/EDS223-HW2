# Repository for the first homework assignment in EDS 223 

This repository houses data from:
- US Environmental Protection Agency’s Environmental Justice Screening and Mapping Tool (ejscreen). This tool no longer exists with the EPA, but an unofficial version of it can be accessed from https://pedp-ejscreen.azurewebsites.net/ .

- Mapping Equality/redlining data from the Digital Scholarship Lab at the University of Richmond(mapping-inequality), accessed from https://dsl.richmond.edu/panorama/redlining/data

- The Statewide Integrated Traffice Records System (SWITRS) database, from the Transportation Information Mapping System (TIMS) developed by UC Berkley SafeTREC, accessed from https://tims.berkeley.edu/.

Author(s): Natasha Clemencon-Charles

This repo has the following structure:
```{r}
EDS223-HW2
├── data
│   ├── ejscreen
│   ├── mapping-inequality
│   └── SWITRS_LA
├── HW2_files
├── HW2.html
├── HW2.qmd
└── README.md
```

The visualizations and html created for this assignment were completed in the HW2.qmd.

The qmd uses the ejscreen, mapping_inequality, and SWITRS datasets to look at conditions across different redlining groups. The first figure in this document shows redlined tracts across Los Angeles County. The next three figures show low income percent, percentile PM 2.5, and percentile low life expectancy across the four grades, and demonstrates that as you move from A towards D HOLC grades, those three metrics become more extreme. The final plot utilizes the bike crash data to find that A and B grades appear to see a lower percent of bike and pedestrian crashes compared to the C and D grades. All of these visualizations demonstrate that worse HOLC grades are correllated with worse socioeconomic and environmental outcomes, demonstrating an issue of environmental inequity. 
