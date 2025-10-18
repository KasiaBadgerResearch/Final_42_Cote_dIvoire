# How has the share of agricultural land evolved relative to the share of arable land in Côte d’Ivoire between 1962 and 2022?

## Abstract

Using World Bank World Development Indicators (WDI), this study examines the evolution of land use in Côte d’Ivoire between 1962 and 2022. The analysis compares two key indicators: agricultural land (% of total land area) and arable land (% of total land area). Over this sixty-year period, agricultural land expanded significantly, reflecting the country’s growing commitment to cultivating and managing land for agricultural production. In contrast, arable land remained a small fraction of total agricultural land and increased only slightly, showing limited expansion despite the overall growth in agricultural land. These patterns highlight the uneven dynamics within land use: while overall agricultural development surged, the portion suitable for crop cultivation expanded at a much slower pace, pointing to structural constraints, land management practices, and the balance between different types of agricultural activities.

## 1. Question

How has the share of agricultural land evolved relative to the share of arable land in Côte d’Ivoire between 1962 and 2022?

- **Agricultural land proxy**: Agricultural land (% of total land area)
- **Arable land proxy**: Arable land (% of total land area)

## 2. Data

- **Source**: World Bank World Development Indicators (WDI)
- **Indicators**:
  - Agricultural land (% of total land area)
  - Arable land (% of total land area)
- **Coverage**: Côte d’Ivoire, 1962–2022
- **Notes**: National-level data only

## 3. Method

1. Filtered dataset for Côte d’Ivoire and selected the two land use indicators.
2. **Extracted relevant columns**: Year, Indicator Name, and Value.
3. Pivoted the dataset to create a side-by-side chronological comparison of agricultural and arable land shares.
4. Produced a dual-line time series plot to visualize the divergence, volatility, and long-term trends of land use in Côte d’Ivoire.

(Analysis is descriptive; no causal inference applied.)

## 4. Results

- **Agricultural land (% of total land area)**: Expanded significantly over the period, showing consistent growth and reflecting an increase in land dedicated to agriculture overall.
- **Arable land (% of total land area)**: Remained a small portion of total agricultural land and increased only slightly, indicating limited expansion of land suitable for crop cultivation.
- **Comparison**: The two indicators reveal divergent patterns: while agricultural land grew strongly, arable land increased marginally. This highlights the structural distinction between total agricultural expansion and the fraction of land actively used for arable purposes.

(Figure 1. Côte d’Ivoire: Agricultural vs. Arable Land, 1962–2022)

(Table 1. Pivoted dataset summary)

## 5. Interpretation

- The rapid growth of agricultural land suggests a broad expansion of farming activities, including permanent crops, pastures, and other non-arable uses.
- The slow increase in arable land indicates limitations in converting land to crop cultivation, possibly due to soil quality, land tenure systems, or environmental constraints.
- The divergence underscores the need for sustainable land management policies that optimize both total agricultural capacity and crop production potential.
- These trends provide insight into Côte d’Ivoire’s agricultural development trajectory, revealing how structural and ecological factors shape the balance between overall agricultural expansion and arable land availability.

## 6. Limitations

- National-level aggregates may mask regional differences in land use, soil quality, or crop suitability.
- WDI estimates rely on national reporting and modeling, introducing potential uncertainty, especially for early years.
- The descriptive approach does not identify causal factors, such as government policy, technology adoption, or investment in irrigation, that may influence land allocation patterns.

## 7. Next Steps / Extensions

- Disaggregate land use data by crop type, pasture, and permanent plantations to better understand internal agricultural composition.
- Explore correlations between land expansion and socio-economic variables such as population growth, agricultural productivity, and market access.
- Compare Côte d’Ivoire’s land use trends with neighboring West African countries to identify regional development patterns.
- Conduct a time-series decomposition to distinguish long-term structural changes from short-term fluctuations in land use.
