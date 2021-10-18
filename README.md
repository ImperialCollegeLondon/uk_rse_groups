# UK RSE Group Sizes

RSE groups at UK institutions with comparable research intensity to Imperial
were approached with the below request for information regarding their team:

> - Total number of FTEs
> - Breakdown of FTE's according to projects/consultancy, teaching/training and other
> - Breakdown of FTE's according to open-ended or fixed-term contract
> - If relevant, team's cost recovery target (%)

Verbatim responses to this query are recorded in
[responses.txt](./responses.txt). These response were parsed manually to derive
the following data:

- Host institution
- Total number of FTEs
- Number of FTE's working on project/consultancy
- Number of FTE's working on teaching/training
- Number of FTE's working on other areas
- Cost recover target (percentage)
- Number of FTE's on open-ended contracts

These data were combined with consolidated financial information (2015/16 to
2019/20) provided by [HESA][]. The following financial data for each institution
was added:

- Income from funding body grants
- Income from research grants and contracts

[HESA]: https://www.hesa.ac.uk/data-and-analysis/finances/table-1

The combined can be found in [data.csv](./data.csv) and with analysis in
[analysis.ipynb](./analysis.ipynb).

Dependencies for the analysis can be found in `requirements.txt`.
