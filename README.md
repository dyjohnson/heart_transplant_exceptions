# Association of High-Priority Exceptions with Waitlist Mortality Among Heart Transplant Candidates

The data preparation and analysis code for *Association of High-Priority Exceptions with Waitlist Mortality Among Heart Transplant Candidates* by Johnson et al, published in The Journal of Heart and Lung Transplantation 5/22/2023. Full manuscript available at https://doi.org/10.1016/j.healun.2023.05.009

Data source was the Q2 2022 Scientific Registry of Transplant Recipients(SRTR) Standard Analysis Files (SAF), https://www.srtr.org/requesting-srtr-data/about-srtr-standard-analysis-files/

The data prepration file creates a long time-series dataset for each candidate from listing until death (as measured by Social Security death and Organ Procurement and Transplantation Network death master files).

The CONSORT diagram file creates a CONSORT diagram detailing the inclusion and exclusion criteria of candidates.

The candidate characteristics file creates a demographics table of the candidates in the dataset.

The descriptive plots file creates graphs illustrating the usage of exceptions under the new heart allocation system. 

The funnel plot file creates a funnel plot describing the statuses and outcomes of patients during their first 100 days on the waitlist.

The Cox models file fits mixed-effects Cox proportional hazard models to the time-series dataset and generates estimates of waitlist survival benefit associated with exceptions.

The statistical appendix contains detailed methodology.

Please reach out to dyjohnson@uchicago.edu with any questions
