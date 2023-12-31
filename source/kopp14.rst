==================
Kopp et al. (2014)
==================

:Title: Probabilistic 21st and 22nd century sea-level projections at a global network of tide-gauge sites
:Key Points:
    - Rates of local sea-level rise differs from rate of global sea-level rise
    - Differences arise from land motion, ocean dynamics, and Antarctic mass balance
    - Local sea-level rise can dramatically increase flood probabilities

:Corresponding author: Robert E. Kopp

:Citation: Kopp, R. E., R. M. Horton, C. M. Little, J. X. Mitrovica, M. Oppenheimer, D. J. Rasmussen, B. H. Strauss, and C. Tebaldi (2014), Probabilistic 21st and 22nd century sea-level projections at a global network of tide-gauge sites, Earth's Future, 2, 383 – 406, doi:10.1002/2014EF000239.

:URL: https://agupubs.onlinelibrary.wiley.com/doi/10.1002/2014EF000239

Abstract
--------

Sea-level rise due to both climate change and non-climatic factors threatens coastal settlements, infrastructure, and ecosystems. Projections of mean global sea-level (GSL) rise provide insufficient information to plan adaptive responses; local decisions require local projections that accommodate different risk tolerances and time frames and that can be linked to storm surge projections. Here we present a global set of local sea-level (LSL) projections to inform decisions on timescales ranging from the coming decades through the 22nd century. We provide complete probability distributions, informed by a combination of expert community assessment, expert elicitation, and process modeling. Between the years 2000 and 2100, we project a very likely (90% probability) GSL rise of 0.5 to 1.2 m under representative concentration pathway (RCP) 8.5, 0.4 to 0.9 m under RCP 4.5, and 0.3 to 0.8 m under RCP 2.6. Site-to-site differences in LSL projections are due to varying non-climatic background uplift or subsidence, oceanographic effects, and spatially variable responses of the geoid and the lithosphere to shrinking land ice. The Antarctic ice sheet (AIS) constitutes a growing share of variance in GSL and LSL projections. In the global average and at many locations, it is the dominant source of variance in late 21st century projections, though at some sites oceanographic processes contribute the largest share throughout the century. LSL rise dramatically reshapes flood risk, greatly increasing the expected number of "1-in-10" and "1-in-100" year events.

Introduction
------------

Sea-level rise figures prominently among the consequences of climate change. It impacts settlements and ecosystems both through permanent inundation of the lowest-lying areas and by increasing the frequency and/or severity of storm surge over a much larger region. In Miami-Dade County, Florida, for example, a uniform 90-cm sea-level rise would permanently inundate the residences of about 5% of the county’s population, about the same fraction currently threatened by the storm tide of a 1-in-100 year flood event [Tebaldi et al., 2012]. A 1-in-100 year flood on top of such a sea-level rise would, assuming geographically uniform flooding, expose an additional 35% of the population (Climate Central, Surging Seas, 2013, retrieved from SurgingSeas.org, updated November 2013).

The future rate of mean global sea-level (GSL) rise will be controlled primarily by the thermal expansion of ocean water and by mass loss from glaciers, ice caps, and ice sheets [Church et al., 2013]. Changes in land water storage, through groundwater depletion and reservoir impoundment, may have influenced twentieth-century sea-level change [Gregory et al., 2013] but are expected to be relatively minor contributors compared to other factors in the current century [Church et al., 2013].

Local sea-level (LSL) change can differ significantly from GSL rise [Milne et al., 2009; Stammer et al., 2013], so for adaptation planning and risk management, localized assessments are critical. The spatial variability of LSL change arises from: (1) non-uniform changes in ocean dynamics, heat content, and salinity [Levermann et al., 2005; Yin et al., 2009], (2) perturbations in the Earth’s gravitational ﬁeld and crustal height (together known as static-equilibrium effects) associated with the redistribution of mass between the cryosphere and the ocean [Kopp et al., 2010; Mitrovica et al., 2011], (3) glacial isostatic adjustment (GIA) [Farrell and Clark, 1976], and (4) vertical land motion due to tectonics, local groundwater, and hydrocarbon withdrawal, and natural sediment compaction and transport [e.g., Miller et al., 2013].

Most past assessments of LSL change have focused on specific regions, such as the Netherlands [Katsman et al., 2011], the U.S. Paciﬁc coast [National Research Council, 2012], New York City [Horton et al., 2011; New York City Panel on Climate Change, 2013], and New Jersey [Miller et al., 2013]. Slangen et al. [2012], Slangen et al. [2014], Perrette et al. [2013], and Church et al. [2013] [AR5] have produced global projections of LSL using Coupled Model Intercomparsion Project (CMIP) projections [Taylor et al., 2012] for thermal expansion and ocean dynamics, along with estimates of net land ice changes, their associated static-equilibrium eﬀects and GIA.

Here we expand upon past efforts to project LSL globally. First, we present a complete probability distribution. This is critical for planning purposes; the likely (67% probability) ranges presented in AR5 and many other previous efforts provide no information about the highest 17% of outcomes, which may well be key to risk management. Second, we indicatively extend our projections to 2200, in order to inform both decision-making regarding long-term infrastructure investment decisions and their longer term land use consequences, and also greenhouse gas mitigation decisions in the context of long-term sea-level rise commitments [Levermann et al., 2013]. Finally, using a Gaussian process model [Kopp, 2013] of historical tide-gauge data [Holgate et al., 2013], we include probabilistic estimates of local non-climatic factors.

We first present our framework and projections for selected locations (projections for all tide-gauge locations are included in the Supporting Information), then assess the effects of sea-level rise on coastal flooding risk at these locations. Throughout, we seek to employ transparent assumptions and an easily replicable methodology that is useful for risk assessment and can be readily updated with new information.


Methods
-------

LSL projections require the projection and aggregation of the individual components of sea-level change [e.g., Milne et al., 2009] at each site of interest. Here, we project three ice sheet components (the Greenland Ice Sheet, GIS; the West Antarctic ice sheet, WAIS; and the East Antarctic ice sheet, EAIS); glacier and ice cap (GIC) surface mass balance (SMB); global mean thermal expansion and regional ocean steric and ocean dynamic effects (which we collectively call oceanographic processes); land water storage; and long-term, local, non-climatic sea-level change due to factors such as GIA, sediment compaction, and tectonics. In our base case, we allow correlations, derived from the SMB model, between different mountain glaciers but otherwise assume that, conditional upon a global radiative forcing pathway, the components are independent of one another. To calculate GSL and LSL probability distributions, we employ 10,000 Latin hypercube samples from time-dependent probability distributions of cumulative sea-level rise contributions for each of the individual components. The sources of information used to develop these distributions are described below and summarized in Figure 1.

.. figure:: figures/kopp14/fig01.jpg
   :align: center
   :width: 50%

   Figure 1: Logical ﬂow of sources of information used in local sea-level projections. GCMs, global climate models; GIC, glaciers and ice caps; SMB: surface mass balance.

We construct separate projections for three representative concentration pathways (RCPs): RCP 2.6, RCP 4.5, and RCP 8.5 [Meinshausen et al., 2011], which correspond respectively to likely global mean temperature increases in 2081 – 2100 of 1.9-2.3˚C, 2.0-3.6˚C, and 3.2-5.4˚C above 1850-1900 levels [Intergovernmental Panel on Climate Change, 2013]. We do not consider RCP 6.0, as 21st-century sea-level rise projections for this pathway are nearly identical to those for RCP 4.5, and few CMIP Phase 5 (CMIP5) model runs for RCP 6.0 extend beyond 2100 [Taylor et al., 2012]. The RCPs do not represent socioeconomic scenarios but can be compared to emissions in no-policy socioeconomic projections such as the Shared Socioeconomic Pathways (SSPs) [O’Neill et al., 2014]. Radiative forcing in RCP 6.0 in the second half of the century is comparable to that in the lowest emissions SSP (SSP 1), while RCP 8.5 is above four of the SSPs but below the highest-emission SSP [Riahi, 2013]. Thus, RCP 8.5 can be viewed as corresponding to high-end business-as-usual emissions and RCP 4.5 as a moderate mitigation policy scenario. RCP 2.6 requires net-negative global emissions in the last quarter of the 21st century, implying a combination of intensive greenhouse gas mitigation and at least modest active carbon dioxide removal.

Ice Sheets
~~~~~~~~~~

Our projections of 21st-century changes in mass balance of GIS and the Antarctic ice sheet (AIS) are generated by combining the projections of AR5 and the expert elicitation of Bamber and Aspinall [2013] [BA13]. AR5 is used to characterize median and likely ranges of sea-level change, while BA13 is used to calibrate the shape of the tails (Supporting Information Figure S1 and Table S1).

.. figure:: figures/kopp14/figS01.png
   :align: center
   :width: 50%

   Figure S1:  Exceedance probabilities for GIS (left) and AIS (right) mass loss between 2000 and 2100 in RCP 8.5, in meters equivalent sea level. Green curves are derived from Bamber and Aspinall [2013], blue curves from the median and likely range of AR5, and red curves are a hybrid based on the green curves but shifted and scaled to match the median and likely range of AR5.

Table S1: Ice sheet mass loss in sensitivity cases (cm equivalent sea level, RCP 8.5 in 2100)

+------------+-------+-------+--------+---------+---------+-------+--------+--------+---------+---------+
|    cm      |                   GIS                      |                   AIS                       |
+------------+-------+-------+--------+---------+---------+-------+--------+--------+---------+---------+
|            |  50   | 17-83 |  5-95  | 0.5-99.5|  99.9   |  50   | 17-83  |  5-95  | 0.5-99.5|  99.9   |
+------------+-------+-------+--------+---------+---------+-------+--------+--------+---------+---------+
|   Default  |  14   | 8-25  |  5-39  | 3-70    |  <95    |  4    | -8-15  | -11-33 | -14-91  | <155    |
+------------+-------+-------+--------+---------+---------+-------+--------+--------+---------+---------+
|    AR5     |  14   | 8-25  |  5-39  | 3-68    |  <95    |  4    | -8-15  | -16-23 | -26-35  | <40     |
+------------+-------+-------+--------+---------+---------+-------+--------+--------+---------+---------+
|    BA      |  14   | 10-21 |  9-29  | 7-48    |  <65    |  14   | 2-41   | -2-84  | -4-220  | <375    |
+------------+-------+-------+--------+---------+---------+-------+--------+--------+---------+---------+
| Alt. Corr. |  14   | 8-25  |  5-39  | 3-70    |  <95    |  4    | -8-15  | -12-33 | -14-85  | <185    |
+------------+-------+-------+--------+---------+---------+-------+--------+--------+---------+---------+


AR5 separately assesses AIS and GIS mass balance changes driven by SMB and ice sheet dynamics. For ice sheet dynamics, AR5 determined that there was insufficient knowledge to differentiate between RCP 2.6 and 4.5 (and 8.5 for AIS). Projections of total ice sheet mass loss – given as a likely cumulative sea-level rise contribution – are thus partially scenario-independent. BA13 probed more deeply into the tail of ice sheet mass loss projections, inquiring into the 5th-95th percentile ranges of GIS, EAIS, and WAIS. However, BA13 does not differentiate between SMB and ice sheet dynamics or between RCPs.

We reconcile the projections as described in the Supporting Information. For AIS, the reconciled RCP 8.5 projections (median/likely/very likely [90% probability] of 4/−8 to 15/−11 to 33 cm) are significantly reduced in range relative to BA13 (median/likely/very likely of 13/2 to 41/−2 to 83 cm); for GIS, the reconciled projections are almost identical to those based directly on AR5 and have a likely range (8 – 25 cm) close to the very likely range estimated from BA13 (9-29 cm) (Supporting Information Table S1).

Ice sheet mass balance changes do not cause globally uniform sea-level rise. To account for the differing patterns of static-equilibrium sea-level rise caused by land ice mass loss, we apply sea-level fingerprints, calculated after Mitrovica et al. [2011] (Supporting Information Figure S2). These ﬁngerprints assume mass loss from each ice sheet is uniform; in most regions, the error introduced by this assumption is minimal [Mitrovica et al., 2011].

.. figure:: figures/kopp14/figS02.png
   :align: center
   :width: 50%

   Figure S2: Static equilibrium sea-level fingerprints employed for (a) GIS, (b) EAIS, (c) WAIS, and (d) median glaciers and ice cap mass loss. Units are meters of local sea level change per meter global sea level change.


Glacier and Ice Caps
~~~~~~~~~~~~~~~~~~~~

For each RCP, we generate mass balance projections for 17 different source regions of glaciers and ice caps (described in the Supporting Information). For each source region, we employ a multivariate t-distribution of ice mass change with a mean and covariance estimated from the process model results of Marzeion et al. [2012]. Each source region has a distinct static-equilibrium sea-level fingerprint, calculated in the same fashion as for ice sheet mass loss (Supporting Information Figure S2).

The projections based on Marzeion et al. [2012] are modestly narrower and have a slightly higher median than those of AR5: a likely range of 9-15 cm from non-Antarctic glaciers by 2100 for RCP 2.6 (vs. 4-16 cm for AR5) and 14-21 cm for RCP 8.5 (vs. 9-23 cm for AR5). We opt for the Marzeion et al. [2012] projections because of the availability of disaggregated output representing projections based on a suite of global climate models (GCMs) for each source region.


Oceanographic Processes
~~~~~~~~~~~~~~~~~~~~~~~

Projections of changes in GSL due to thermal expansion and in LSL due to regional steric and dynamic effects are based upon the CMIP5 GCMs. In particular, we employ a t-distribution with the mean and covariance of a multi-model ensemble constructed from the CMIP5 archive (Supporting Information Figures S3 and S4, Table S2). Values used are 19-year running averages. For each model, we use a single realization. The sea-level change at each tide-gauge location is assumed to be represented by the nearest ocean grid cell value of each GCM.

.. figure:: figures/kopp14/figS03.png
   :align: center
   :width: 50%

   Figure S3: CMIP5 thermal expansion projections (left) and after smoothing and drift correction (right). Black = GSL curve of Church and White [2011]. Dashed = mean/max/min of GSL with glacier and ice cap projections removed.

   
.. figure:: figures/kopp14/figS04.png
   :align: center
   :width: 50%

   Figure S4: Map of (top) median and (middle) width of likely range of ocean dynamic contribution to sea-level rise between 2000 and 2100 for RCP 8.5 (not including the contribution of global mean thermal expansion). (Bottom) Number of model projections retained at each site in RCP 8.5.


Table S2: CMIP5 models used for thermal expansion and oceanographic processes

The horizontal resolution of the CMIP5 ocean models is ~1 degree. In these coarse-resolution models, sea level at the coast may differ from the open ocean due to local biases driven by unresolved processes (e.g., coastal currents) and bathymetry [Holt et al., 2009] or via the influence of small-scale processes (e.g., eddies) on larger-scale steric and dynamic changes [Penduff et al., 2010, 2011]. Although there is some evidence that climate-forced trends in sea level are not sensitive to resolution [Penduff et al., 2011; Suzuki et al., 2005], higher-resolution coastal modeling is required to determine whether the probabilities estimated at the GCM grid scale are significantly changed by sub-grid processes.

GCM projections exhibit a range of late nineteenth-century sea-level behavior largely attributable to model drift. Uncorrected GCM-based estimates of the rate of mean global sea-level change from 1861 to 1900 range from −0.4 to +1.1 mm/yr. To correct for global-mean model drift, we apply a linear correction term to each model. The linear correction adjusts the rate of GSL rise over 1861-1900 to match a rate of thermal expansion estimated by removing the multi-model average of GIC mass loss from Marzeion et al. [2012] from the GSL curve of Church and White [2011]. After correction, the rate of thermal expansion over 1861–1900 is 0.3 ± 0.9 (2σ) mm/yr (Supporting Information Figure S3).

Consistent with AR5’s judgment that the 5th-95th percentile of CMIP5 output represents a likely (67% probability) range for global mean thermal expansion, we multiply the standard deviation of the t-distribution for oceanographic processes by 1.7.

Land Water Storage
~~~~~~~~~~~~~~~~~~

Following the approach of Rahmstorf et al. [2012], we estimate GSL change due to changes in water storage on land based upon the relationship between such changes and population (Supporting Information Figure S5). For changes in reservoir storage, we use the historical cumulative impoundment estimate of Chao et al. [2008]. We assume that reservoir construction is a sigmoidal function of population:

.. math::

   I = a \times \mathrm{erf}\left(\frac{{P(t) - b}}{{c}}\right) + I_0
   
where I is impoundment expressed in mm equivalent sea level (esl), P(t) is world population as a function of time, and the remaining variables are constants. The results imply a maximum additional impoundment of 6 mm (esl) on top of the current 30 mm; based on the discrepancy between the “nominal” and “actual” impoundment estimated by Chao et al. [2008], we conservatively allow a 2σ error in this estimate of ±50 %.

For the rate of groundwater depletion, we fit the estimates of Wada et al. [2012] and Konikow [2011] as linear functions of population, forced through the origin. The estimate of Wada et al. [2012] is based on fluxes estimated from a global hydrological model of groundwater recharge and a global database of groundwater abstraction, while that of Konikow [2011] uses a range of approaches depending on the data available for each aquifer. We take the mean and standard deviation of the two slopes estimated (0.06 ± 0.02 mm/yr/billion people) and allow an additional 2 error of ±50%, a level based upon the errors estimated by the authors of the two impoundment studies. In our main calculation, we do not include the water resource assessment model-based estimate of Pokhrel et al. [2012], which is about a factor of three higher than the other two estimates; we include this estimate in a sensitivity case.

We employ population projections derived from United Nations Department of Economics and Social Aﬀairs [2014]. We treat population as distributed following a triangular distribution, with the median, minimum, and maximum values corresponding to the middle, low, and high U.N. scenarios (10.9, 6.8, and 16.6 billion people in 2100, respectively). For scenarios in which population declines, we allow some reduction in impoundment, but do not allow impoundment to decrease below its year 2000 level.


Glacial Isostatic Adjustment, Tectonics, and Other Non-Climatic Local Effects
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

GIA, tectonics, and other non-climatic local effects that can be approximated as linear trends over the twentieth century are assumed to continue unchanged in the 21st and 22nd centuries. This is a good assumption for GIA, but imperfect for other processes. Tectonic processes can operate unsteadily, and a linear trend estimated from the historical record may be inaccurate. LSL rise related to fluid withdrawal is subject to engineering, resource depletion, market factors and policy controls, and might either increase or decrease in the future relative to historical levels. In addition, the trend estimates can encompass slow ocean dynamic changes that are close to constant over the historical record but could change in the future. Nonetheless, for a global analysis, assuming the continuation of observed historical changes offers the best currently feasible approach.

We estimate historical rates using a spatiotemporal Gaussian process model akin to that employed by Kopp [2013]. Sea level as recorded in the tide-gauge records (Permanent Service for Mean Sea Level, Tide-gauge data, retrieved from http://www.psmsl.org/data/obtaining/, accessed January 2014) is represented as the sum of three Gaussian processes: (1) a globally uniform process, (2) a regionally varying, temporally linear process, and (3) a regionally varying, temporally autocorrelated non-linear process. We allow for spatial non-stationarity in the Gaussian process prior by optimizing the hyperparameters separately for each of 15 regions (Supporting Information Table S4 and Figure S6). The posterior estimate of the second (linear) process at each site is used for forward projections. Mathematical details are provided in the Supporting Information.

Table S4: Optimized model hyperparameters by region


.. figure:: figures/kopp14/figS06.png
   :align: center
   :width: 50%

   Figure S6: Tide gauge sites and regions used in background rate calculation.


Post-2100 Projections
~~~~~~~~~~~~~~~~~~~~~

Indicative post-2100 projections are developed according to the methods described in the previous sections. For ice sheet mass balance, we continue the constant 21st century acceleration. For non-climatic factors that are approximated as linear in the 21st century, we continue the constant 21st century rate. For land water storage, we extend the population projections using the 22nd century growth rates of United Nations Department of Economics and Social Aﬀairs [2004] and use the same relationships of impoundment and groundwater depletion to population as in the 21st century (Supporting Information Figure S5). The number of GCM-based model results for GIC and oceanographic processes drops significantly beyond 2100 (Supporting Information Table S2), leading in these terms to a modest discontinuity and a reduction in variance in these terms at the start of the 22nd century (Supporting Information Figure S7). Acknowledging the limitations of these assumptions, we present post-2100 projections in tables rounded to the nearest decimeter.

Flood Probabilities
~~~~~~~~~~~~~~~~~~~

To examine the implications of our projections for coastal flooding, we combine Latin hypercube samples from the sea-level distribution for an illustrative subset of sites with maximum-likelihood generalized Pareto distributions (GPDs) estimated from observed storm tides after Tebaldi et al. [2012], updated to use the full historic record of hourly water levels available at each location. Hourly data for non-U.S. sites are from the University of Hawaii Sea Level Center (retrieved from uhslc.soest.hawaii.edu, May 2014). The estimated GPDs do not take into account any future changes in storm frequency, intensity, or track [e.g., Knutson et al., 2010], so projected future flood probabilities should be viewed primarily as an illustration.

Using the maximum-likelihood GPDs, we compute return levels corresponding to a set of representative return periods (e.g., the 1-in-10 or 1-in-100 year flood events). For each decade of each realization of LSL change, we then add the projected sea-level change and re-estimate a GPD. The result for each realization is a trajectory of probabilities over time for each of the original return levels. For example, for the 10-year event, the initial probability at 2000 is 10% per year and increases over time as sea-level rises. Cumulatively summing each decade’s expectation through the century, we compute the expected number of the original events by 2100. Under stationary sea levels, there would be one expected 1-in-100 year event and ten expected 1-in-10 year events between 2001 and 2100.


Sea-Level Projections
---------------------

Mean Global Sea-Level Projections
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The cumulative 21st century GSL contribution of each component is shown in Figure 2 (for RCP 8.5) and in Table 1 and Supporting Information Figure S7 (for all RCPs). In the 21st century, thermal expansion and GIC provide the largest contributions to the median outcome and have narrower uncertainty ranges than the ice sheet contributions. AIS has the broadest uncertainty range, extending from a small negative contribution to sea level (presumably due to warming-induced increased snow accumulation) to a large positive contribution (requiring a substantial and/or widespread dynamic change).


.. figure:: figures/kopp14/fig02.jpg
   :align: center
   :width: 50%

   Figure 2: Projections of cumulative contributions of (a) the Greenland ice sheet, (b) the Antarctic ice sheet, (c) thermal expansion, and (d) glaciers to sea-level rise in RCP 8.5. Heavy = median, light = 67% range, dashed = 5th – 95th percentile; dotted = 0.5th-99.5th percentiles.


**Table 1**: GSL Projections. TE: Thermal expansion, LWS: Land water storage, H14: Horton et al. [2014], J12: Jevrejeva et al. [2012], S12: Schaeffer et al. [2012]. All values are cm above 2000 CE baseline except for AR5, which is above a 1986–2005 baseline.

+----------------------------------+-----------------------------------------------+---------------------------------------+-----------------------------------------------------+
|                                  |               RCP 8.5                         |                RCP 4.5                |                RCP 2.6                              |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+
|             cm                   | 50  | 17-83    | 5-95      | 0.5-99.5  | 99.9 | 50  | 17-83    | 5-95     | 0.5-99.5  | 99.9 | 50  | 17-83    | 5-95     | 0.5-99.5  | 99.9 |
+==================================+=====+==========+===========+===========+======+=====+==========+==========+===========+======+=====+==========+==========+===========+======+
| 2100 - Components                                                                                                                                                              |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+
| GIC                              | 18  | 14-21    | 11-24     | 7-29      | <30  | 13  | 10-17    | 7-19     | 3-23      | <25  | 12  | 9-15     | 7-17     | 3-20      | <25  |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+
| GIS                              | 14  | 8-25     | 5-39      | 3-70      | <95  |  9  | 4-15     | 2-23     | 0-40      | <55  | 6   | 4-12     | 3-17     | 2-31      | <45  |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+
| AIS                              |  4  | -8 to 15 | -11 to 33 | -14 to 91 | <155 |  5  | -5 to 16 | -9 to 33 | -11 to 88 | <150 | 6   | -4 to 17 | -8 to 35 | -10 to 93 | <155 |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+
| TE                               | 37  | 28-46    | 22-52     | 12-62     | <65  | 26  | 18-34    | 13-40    | 4-48      | <55  | 19  | 13-26    | 8-31     | 1-38      | <40  |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+
| LWS                              |  5  | 3-7      | 2-8       | -0 to 11  | <11  |  5  | 3-7      | 2-8      | -0 to 11  | <11  | 5   | 3-7      | 2-8      |  -0 to 11 | <11  |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+
| Total                            | 79  | 62-100   | 52-121    | 39-176    | <245 | 59  | 45-77    | 36-93    | 24-147    | <215 | 50  | 37-65    | 29-82    | 19-141    | <210 |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+
| Projections by year                                                                                                                                                            |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+
| 2030                             | 14  | 12-17    | 11-18     | 8-21      | <25  | 14  | 12-16    | 10-18    | 8-20      | <20  | 14  | 12-16    |  10-18   | 8-20      | <20  |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+
| 2050                             | 29  | 24-34    | 21-38     | 16-49     | <60  | 26  | 21-31    | 18-35    | 14-44     | <55  | 25  | 21-29    |  18-33   | 14-43     | <55  |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+
| 2100                             | 79  | 62-100   | 52-121    | 39-176    | <245 | 59  | 45-77    | 36-93    | 24-147    | <215 | 50  | 37-65    |  29-82   | 19-141    | <210 |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+
| 2150                             | 130 | 100-180  | 80-230    | 60-370    | <540 | 90  | 60-130   | 40-170   | 20-310    | <480 | 70  | 50-110   |  30-150  | 20-290    | <460 |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+
| 2200                             | 200 | 130-280  | 100-370   | 60-630    | <950 | 130 | 70-200   | 40-270   | 10-520    | <830 | 100 | 50-160   |  30-240  | 10-500    | <810 |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+
| Other projections for 2100                                                                                                                                                     |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+
| AR5                              | 73  | 53–97    |           |           |      | 52  | 35–70    |          |           |      | 43  | 28–60    |          |           |      |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+
| H14                              |     | 70–120   | 50–150    |           |      |     |          |          |           |      |     | 40–60    |  25-70   |           |      |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+
| J12                              | 110 |          | 81–165    |           |      | 75  |          | 52–110   |           |      | 57  |          |  36–83   |           |      |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+
| S12                              |     |          |           |           |      | 90  |          | 64–121   |           |      | 75  |          |  52–96   |           |      |
+----------------------------------+-----+----------+-----------+-----------+------+-----+----------+----------+-----------+------+-----+----------+----------+-----------+------+

.. figure:: figures/kopp14/figS07.png
   :align: center
   :width: 50%

   Figure S7: Projections of (a) Greenland ice sheet, (b) Antarctic ice sheet, (c) thermal expansion, and (d) glacier contributions to sea-level rise in RCP 8.5 (red), RCP 4.5 (blue) and RCP 2.6 (green). Heavy = median, dashed = 67% range.


Adding samples from the component distributions together indicates a likely GSL rise (Figure 3 and Table 1) in RCP 8.5 of 0.6 – 1.0 m by 2100, with a very likely range of 0.5 – 1.2 m and a virtually certain (99% probability) range of 0.4 – 1.8 m. The right-skewed “fat tail” of the projections arises from the ice sheet components. Even in the low-emissions RCP 2.6 pathway, sea-level rise by 2100 very likely exceeds the 32 cm that would be projected from a simple linear continuation of the 1993 – 2009 rate [Church and White, 2011].

.. figure:: figures/kopp14/fig03.jpg
   :align: center
   :width: 50%

   Figure 3: Projections of GSL rise for the three RCPs. Heavy = median, dashed = 5th – 95th percentile, dotted = 0.5th – 99.5th percentiles.

Through the middle of the current century, GSL rise is nearly indistinguishable between the three forcing pathways (Figure 3 and Table 1). Only in the second half of the century do differences of >6 cm begin to emerge in either the median or the tails of the projections. By 2100, median projections reach 0.8 m for RCP 8.5, 0.6 m for RCP 4.5 and 0.5 m for RCP 2.6. By 2200, upper tail outcomes are clearly higher in the high-forcing pathway, yet there remains significant overlap in the ranges of all three pathways, with likely GSL rise by 2200 of 1.3 – 2.8 m in RCP 8.5 and 0.5 – 1.6 m in RCP 2.6. The overlap between RCPs is due in significant part to the large and scenario-independent uncertainty of AIS dynamics, even as the thermal expansion, GIC and, to a lesser extent, GIS contributions begin to differentiate (Supporting Information Figure S7).

The importance of different components to the GSL uncertainty varies with time. While in 2020 about two-thirds of the total variance in GSL is due to uncertainty in projections of thermal expansion, by 2050 in RCP 8.5 changes in ice sheet volume are responsible for more than half the variance and changes in thermal expansion for only about one-third. By 2100, AIS alone is responsible for half the variance, with an additional 30% due to GIS uncertainty and only 15% due to uncertainty in thermal expansion (Figure 4). Because the uncertainty in AIS mass loss is largely scenario-independent, its dominant contribution to variance holds across RCPs; indeed, it is even more dominant in lower emissions pathways where the contributions from other sources are smaller and more strongly constrained (Supporting Information Figure S8).

.. figure:: figures/kopp14/fig04.jpg
   :align: center
   :width: 50%

   Figure 4: Sources of variance in raw (a, c) and fractional terms (b, d), globally (a – b) and at New York City (c – d) in RCP 8.5. AIS: Antarctic ice sheet, GIS: Greenland ice sheet, TE: thermal expansion, Ocean: oceanographic processes, GIC: glaciers and ice caps, LWS: land water storage, Bkgd: local background effects.


.. figure:: figures/kopp14/figS08.png
   :align: center
   :width: 50%

   Figure S8: Sources of variance in raw (left) and fractional terms (right), for a range of sites under RCP 2.6.

Comparison With Other Global Projections
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

By construction, our *likely* projections of GSL in 2100 are close to those of AR5 (Table 1), though differ slightly (e.g., in RCP 8.5 in 2100, 0.6 – 1.0 m vs. AR5’s 0.5 – 1.0 m) due to: (1) the drift correction to a possibly non-zero (0.3 ± 0.9 mm/yr) background thermal expansion, (2) the use of Marzeion et al. [2012] for GIC, and (3) the use of a year 2000 as opposed to 1985 – 2005 baseline. AR5 projections of GSL rise are lower than those from other sources, such as semi-empirical models [Rahmstorf , 2007; Schaeﬀer et al., 2012; Vermeer and Rahmstorf , 2009] and expert surveys [Horton et al., 2014]. However, AR5 only projects likely ranges; higher magnitudes of ice loss are implied if less likely outcomes are considered [Little et al., 2013a].

By using plausible information to complement the AR5 analysis, we project a very likely GSL rise in 2100 of 0.4 – 0.9 m for RCP 4.5, which compares to the 90% probability semi-empirical projections of 0.5 – 1.1 m [Jevrejeva et al., 2012] and 0.6 – 1.2 m [Schaeffer et al., 2012]. The widths of the semi-empirical very likely ranges are similar to those of our projections, with the entire distribution shifted to higher values. The 95th percentiles of these two semi-empirical projections resemble the 98th and 99th percentiles of our projection, respectively.

Horton et al. [2014] conducted a survey of 90 experts with a substantial published record in sea-level research. Their survey found likely/very likely sea-level rise by 2100 of 0.7 – 1.2/0.5 – 1.5 m under RCP 8.5 and 0.4 – 0.6/0.3 – 0.7 m under RCP 2.6. Our projections for RCP 2.6 are similar to those of the surveyed experts, with a slightly fatter upper tail, while the experts’ responses for RCP 8.5 are considerably fatter-tailed than our projections. The surveyed experts’ 83rd and 95th percentiles correspond to our 95th and 99th percentiles, respectively. Although Horton et al. [2014] did not probe the reasons why their surveyed experts different from AR5, we suggest it may be related to expectations about the behavior of Antarctica. As noted previously, high-end estimates of Antarctic mass loss from the expert elicitation of BA13 are higher than would be expected from the likely range of AR5 projections; our reconciled ice sheet projections significantly lower this contribution. (See also the sensitivity tests in section 4 for comparison.)

Our 99.9th percentile estimate for 2100 under RCP 8.5, 2.5 m, is consistent with other estimates of the maximum physically possible rate of sea-level rise in the 21st century [e.g., Miller et al., 2013]. It is higher than the 2.0 m estimate of Pfeffer et al. [2008], which corresponds to our 99.7th percentile. Comparing the individual contribution to Pfeffer et al.’s high-end projection shows that their projected GIC mass loss (55 cm) exceeds our highest projected value (32 cm), while their projections of GIS and AIS mass loss (53 and 62 cm, respectively) correspond to our 98th and 99th percentiles. Their projection of thermal expansion (30 cm) includes no uncertainty and corresponds to our 22nd percentile [cf., Sriver et al., 2012]. They do not include changes in sea-level rise resulting from changes in land water storage. As noted previously, the tail of the sea-level rise projections is dominated by the uncertainty in AIS mass loss, which is lower in Pfeffer et al. [2008] than in either our projections or BA13.

Local Sea-Level Projections: Patterns
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Figure 5 displays the median LSL projections for RCP 8.5 in 2100 and the projection uncertainty, as reflected by the difference between the 17th and 83rd percentile levels. In Figure 6, we illustrate the relationship between LSL and GSL using three indices: (1) the median value of R, which we define as the ratio of LSL change driven by land ice and oceanographic components to GSL change driven by those same components (Figure 6a), (2) the uncertainty in R, reflected in Figure 6b by the difference between its 17th and 83rd percentile levels, and (3) the magnitude and uncertainty of background, non-climatic LSL change (Figure 6c). For sites where R is close to 1 and exhibits little uncertainty, GSL projections with adjustment for local land motion provide a reasonable estimate of LSL; for other sites, more detailed projections, such as those in this article, are necessary.

.. figure:: figures/kopp14/fig05.jpg
   :align: center
   :width: 50%

   Figure 5: (a) Median projection and (b) width of likely range of local sea-level rise (m) in 2100 under RCP 8.5.

.. figure:: figures/kopp14/fig06.jpg
   :align: center
   :width: 50%

   Figure 6: (a) Median ratio R of climatically driven LSL change to climatically driven GSL exchange (i.e., excluding land water storage and local land motion) in RCP 8.5 in 2100; (b) width of the 17th – 83rd percentile range of R; (c) mean estimates of background rate of sea-level rise due to GIA, tectonics, and other local factors (mm/yr). Open circles in bottom indicate sites where 2 $\sigma$ range spans zero.

The median value of R (Figure 6a) is within 5 % of unity at about a quarter of tide-gauge sites, with higher values in much of Oceania, the Indian Ocean, and southern Africa resulting from the static-equilibrium effects of land ice mass loss. R generally declines toward higher latitudes due to static-equilibrium effects, but with values elevated in northeastern North America and to a lesser extent the North and Baltic Seas by oceanographic processes. This pattern — with sea-level rise dampened near land ice and enhanced far from it and in the northwestern North Atlantic — resembles that found by previous studies [Kopp et al., 2010; Perrette et al., 2013; Slangen et al., 2012, 2014]. Uncertainty in R (Figure 6b) is also relatively small (likely range width of < 30 %) in the inhabited southern hemisphere and low-latitude northern hemisphere, with the range increasing northwards due to both the sensitivity of static-equilibrium effects to the particular distribution of shrinking land ice reservoirs and — especially in northeastern North America, the Baltic Sea, and the Russian Arctic — uncertainty in oceanographic processes (Supporting Information Figure S4).

Added on top of the climatically driven factors reflected in R are the global effects of land water storage (not shown in Figure 6) and the effects of local land motion (Figure 6c). Moderately high rates of land subsidence can be associated with GIA, as in the northeastern United States (e.g., 1.3 ± 0.2 mm/yr at New York City), while more extreme rates generally include contributions from fluid withdrawal, delta processes, and/or tectonics. Subsidence driven by fluid withdrawal and delta processes is high at sites such as Bangkok, Thailand (background rate of 11.9 ± 1.1 mm/yr at the Fort Phracula Chomklao tide gauge), Grand Isle, Louisiana (7.2 ± 0.5 mm/yr), Manila, the Philippines (background rate of 4.9 ± 0.6 mm/yr), and Kolkata, India (5.1 ± 1.0 mm/yr). Episodic tectonic factors play an important role in both subsidence and uplift in Japan, where average background rates can range from − 5.2 ± 0.7 mm/yr at Onahama to 18.0 ± 1.6 mm/yr at Toba. At high latitudes, GIA-related uplift gives rise to high background rates of sea-level fall, as can be seen in places like Juneau, Alaska, (− 14.9 ± 0.5 mm/yr), and Ratan, Sweden (− 9.3 ± 0.2 mm/yr). While some previous global projections have used physical models to incorporate GIA [e.g., Slangen et al., 2012, 2014], the current projections are to our knowledge the first to employ observationally based rates.

Local Sea-Level Projections: Examples
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To illustrate the importance of local factors for sea-level rise projections, we consider several sites along the coasts of the United States where different factors dominate LSL change (Tables 2 and 3). While we focus on projections for RCP 8.5 as a way of highlighting the differences between GSL and LSL, similar considerations apply to other RCPs, which are shown in the tables.

**Table 2**: LSL Projections for New York, NY, USA (Bkgd: 1.31 ± 0.18 mm/yr), Sewell’s Point, VA, USA (Bkgd: 2.45 ± 0.29 mm/yr), Key West, FL, USA (Bkgd: 0.46 ± 0.41 mm/yy), Galveston, TX, USA (Bkgd: 4.56 ± 0.27 mm/yr), San Francisco, CA, USA (Bkgd: − 0.08 ± 0.18 mm/yr), Juneau, AK, USA (Bkgd: − 14.91 ± 0.53 mm/yr), Honolulu, HI, USA (Bkgd: − 0.20 ± 0.39 mm/yr), Cuxhaven, Germany (Bkgd: 1.00 ± 0.17 mm/yr), Stockholm, Sweden (Bkgd: − 5.01 ± 0.12 mm/yr), Kushimoto, Japan (Bkgd: 1.46 ± 0.80 mm/yr), Valparaiso, Chile (Bkgd: − 2.47 ± 0.79 mm/yr) in RCP 8.5, RCP 4.5 and RCP 2.6 emission scenarios.

**Table 3**: Components of LSL rise in 2100 for New York, NY, USA, Sewell’s Point, VA, USA, Key West, FL, USA, Galveston, TX, USA, San Francisco, CA, USA, Juneau, AK, USA, Honolulu, HI, USA, Cuxhaven, Germany, Stockholm, Sweden, Kushimoto, Japan, Valparaiso, Chile in RCP 8.5, RCP 4.5 and RCP 2.6 emission scenarios.

New York City experiences greater-than-global sea-level rise under almost all plausible projections, with a likely range of 0.7 – 1.3 m by 2100 under RCP 8.5. Three factors enhance sea-level rise at New York. First, due to its location on the subsiding peripheral bulge of the former Laurentide Ice Sheet, the site experiences GIA-related sea-level rise of 1.3 ± 0.2 mm/yr. Second, the rotational effects of WAIS mass loss increase
the region’s sea-level response to WAIS mass loss by about 20% [Mitrovica et al., 2009]. Third, as noted
in earlier papers [Kopp et al., 2010; Yin et al., 2009; Yin and Goddard, 2013], changes in the Gulf Stream may result in dynamic sea-level rise in the mid-Atlantic United States. This enhancement can be seen by examining the difference between oceanographic sea-level rise at New York and the global average, which has a median of 14 cm and a likely range of −6 to +35 cm. These three effects are partially counteracted by the ∼55 % reduction in the sea-level response due to GIS mass loss, associated with the gravitationally induced migration of water away from of this relatively proximal ice mass. Indeed, the climatic factors that amplify and reduce LSL rise relative to GSL rise are nearly balanced in the median projection (R = 1.03, with a likely range of 0.73 – 1.30), with GIA effects pushing local rise to levels that exceed the global rise.

Sewell’s Point in Norfolk, VA, is projected to experience higher-than-global mean sea-level rise due to the same factors as New York City: subsidence due to GIA, enhanced influence of WAIS mass loss, and exposure to changes in the Gulf Stream. Being located farther south along the U.S. East Coast, Norfolk experiences somewhat smaller ocean dynamic changes (median and likely ocean dynamic sea-level rise increment of 9 cm and −8 to 26 cm) but greater sea-level rise due to GIS mass loss (experiencing about ∼45 % less sea-level rise than the global mean). Its R value (1.00, likely range of 0.75 – 1.22) is similar to New York City. However, whereas New York City sits upon bedrock, Norfolk is located on the soft sediments of the Coastal Plain [Miller et al., 2013]. As a consequence, it is exposed to sea-level rise due to both natural sediment compaction and compaction caused by groundwater withdrawal, which increases the background non-climatic rate of sea-level rise to 2.5 ± 0.3 mm/yr. Accordingly, the likely range of LSL rise for RCP 8.5 in 2100 is 0.8 – 1.3 m.

Sea-level rise at Key West, Florida, is closer to the global mean, with a likely range in RCP 8.5 by 2100 of 0.6 – 1.1 m (median R = 1.00, likely range of 0.83 – 1.15, background rise of 0.5 ± 0.4 mm/yr). By contrast, the deltaic western Gulf of Mexico coastline experiences some of the fastest rates of sea-level rise in the world as a result of groundwater withdrawal and hydrocarbon production [Kolker et al., 2011; White and Tremblay, 1995]. At Galveston, Texas, a background subsidence rate of 4.6 ± 0.3 mm/yr drives a likely range of sea-level rise by 2100 in RCP 8.5 of 1.0 – 1.5 m. Because the uncertainty in subsidence rate is small relative to other sources of uncertainty, this causes a shift in the range rather than a broadening of overall uncertainty, as occurs at New York City (reflected in a likely R of 0.78 – 1.13, which is narrower than at New York City).

The Paciﬁc Coast of the contiguous United States is subject to considerable short length-scale sea-level rise variability due to tectonics, as can be seen by comparing the background non-climatic rate of sea-level rise at Los Angeles (− 1.1 ± 0.3 mm/yr) and nearby Santa Monica (− 0.6 ± 0.3 mm/yr). In general, sea-level rise on this coast is close to the global average, with a likely range in 2100 under RCP 8.5 at San Francisco of 0.6 – 1.0 m (median R = 0.96, likely 0.84 – 1.08, background rate of − 0.1 ± 0.2 mm/yr). The slightly lower-than-global projection is a result of smaller Greenland and GIC contributions due to proximity to these land ice reservoirs, though counterbalanced by enhanced sea-level rise from AIS mass loss. Ocean dynamic factors are projected to play a minimal role.

Farther north, the proximity of historic and modern glaciers controls LSL projections. At Juneau, predicted sea-level rise is dominated by a glacio-isostatic sea-level fall of 14.9 ± 0.5 mm/yr, interpreted as resulting primarily from the ongoing response to post-Little Ice Age glacial mass loss, with a secondary contribution from post-Last Glacial Maximum GIA [Larsen et al., 2005]. Moreover, shrinking glaciers in Alaska and western Canada cause about 2.4 mm of LSL fall at Juneau for every mm of global sea-level rise, which reduces the overall magnitude of sea-level rise caused by projected glacial mass loss (median R = 0.71, likely 0.59 – 0.83). As a consequence, under RCP 8.5 Juneau is likely to experience a sea level fall of 0.7 – 1.1 m by 2100.

Hawai‘i and other central Paciﬁc islands experience significantly greater-than-average sea-level rise resulting from land ice mass loss (20% enhancement for GIS, EAIS, and the median combination of shrinking glaciers, and 30% for WAIS, giving rise to median R = 1.13 and likely 0.98 – 1.26). The likely range of sea-level rise at Honolulu, Hawai‘i, is slightly higher than the global mean (0.6 – 1.1 m in 2100 under RCP 8.5, with a background rate of − 0.2 ± 0.4 mm/yr). The amplification relative to the global mean is more apparent in the tail of the projections, where ice sheet mass loss contributions constitute a larger proportion of the sea-level rise. As a consequence, the tail of sea-level rise is fatter at Hawai‘i than globally, with a 95th percentile in RCP 8.5 of 1.4 m (compared to GSL of 1.2 m) and a 99.5th percentile of 2.1 m (compared to GSL of 1.8 m).

A similar range of behaviors is seen outside the United States. At Cuxhaven, on the German North Sea coast, a slightly higher-than-global likely range of 0.6 – 1.1 m arises from a background subsidence rate of 1.0 ± 0.2 mm/yr. Because of its relative proximity to Greenland, Cuxhaven is less exposed to climatically driven sea-level rise than average (median R = 0.89, likely 0.62 – 1.15); unlike sites in eastern North America that are similarly close to Greenland, it does not experience a countervailing oceanographic sea-level rise. The city of Stockholm, Sweden, like Juneau, is experiencing a strong GIA-related uplift of −5.0 ± 0.1 mm/yr, leading to a likely sea-level rise of −0.4 to +0.8 m. Being farther from a large, actively shrinking glacier, however, Stockholm is in the median more exposed than Juneau to climatically driven sea-level change (median R = 0.83, likely 0.41 – 1.20).

Like Honolulu, the town of Kushimoto, in Wakayama Prefacture, Japan, is in the far-ﬁeld of the major ice sheets and most major glaciers. It is also exposed to a likely ocean dynamic sea-level rise of −5 to +18 cm in 2100. Together, these factors lead to a median R = 1.14, likely 0.98 – 1.28. Kushimoto also is experiencing tectonic subsidence, leading to a likely sea-level rise in 2100 of 0.8 – 1.3 m.

The city of Valparaiso, on the Chilean Paciﬁc coast, is experiencing tectonic uplift of 2.5 ± 0.8 and exposed to a likely ocean dynamic sea-level fall of −2 to 9 cm. Although it experiences about 30% less-than-global sea-level rise due to WAIS mass loss, it experiences a larger-than-average response to GIS, EAIS, and most glaciers; accordingly its overall sensitivity to sea-level rise is close to the global average (median R = 0.99, likely 0.90 – 1.08). All these factors together yield a likely 2100 sea-level rise 0.4 – 0.8 m.


Variance and Sensitivity Assessment
-----------------------------------

As shown in the previous section, LSL rise is controlled by different factors — both climatic and non-climatic — at different locations and intervals over the next two centuries. The analysis also reveals that the adopted risk tolerance (choice of exceedance probability) influences the importance of different components. Median outcomes will vary regionally, driven strongly by varying levels of subsidence and, in certain regions, oceanographic processes. High-end (low-probability) outcomes are driven, globally and in most locations, by uncertainty in the ice sheet contribution, with the Antarctic signal becoming dominant in the highest end of the tail, particularly later in the century (Figure 4 and Supporting Information Figures S8 and S9). This contribution varies less by location.

.. figure:: figures/kopp14/figS09.png
   :align: center
   :width: 50%

   Figure S9: Sources of variance in raw (left) and fractional terms (right), for a range of sites under RCP 8.5.


To test the robustness of our results, we examine three alternate assumptions regarding ice sheet mass loss and two alternative assumptions regarding the robustness of GCM projections (Supporting Information Tables S1 and S3):

1. AR: using a lognormal fit to the AR5 median and likely ranges of ice sheet mass balance (GIS almost unchanged from reconciled projections; for AIS, very likely range of −15 to 23 cm in RCP 8.5 by 2100)
2. BA: using a lognormal fit to the BA13 median and very likely projections of ice sheet mass balance (GIS: median 14 cm and very likely 9 – 29 cm; AIS: median 14 cm, very likely −2 to 83 cm)
3. Alt. Corr.: assuming positive correlations of 0.7 between WAIS and GIS and a negative correlation of −0.2 between EAIS and the other two ice sheets, following the main projections of Bamber and Aspinall [2013]
4. High GCM Confidence: assuming the very likely ranges estimated by the GCMs for oceanographic changes are very likely rather than likely ranges.
5. Reduced degrees of freedom (DOF): Assuming the GCMs collectively provide only six independent estimates of GIC and oceanographic change, due to non-independence of models.
6. Higher groundwater depletion (GWD): The ratio of groundwater depletion to population is treated as a triangular distribution, with the minimum, median, and maximum estimated respectively from Konikow [2011], Wada et al. [2012] and Pokhrel et al. [2012].

**Table S1**: Ice sheet mass loss in sensitivity cases (cm equivalent sea level, RCP 8.5 in 2100)

**Table S3**: Sensitivity tests (cm, RCP 8.5 in 2100) for GSL and LSL in set of locations.

At a global level and at most locations, the two alternative characterizations of ice sheet mass changes have the largest effects, with the median sea-level rise under RCP 8.5 in 2100 varying between 79 cm under default assumptions and case AR and 91 cm under case BA. The effect is larger in the tails, with 99.5th percentile projections of 140 cm under AR, 176 cm under default assumptions, 187 cm under Alt. Corr., and 300 cm under BA. Varying the confidence in GCMs, by contrast, has little global effect. Although the per-capita rate of groundwater depletion estimated from Pokhrel et al. [2012] is about three times that of the Wada et al. [2012], the overall effect of the Higher GWD assumption is small due to the magnitude of other uncertainties; this case experiences 3 cm extra GSL rise at the 5th percentile, 4 cm at the median, and 6 cm at the 99.5th percentile.

While all LSL projections are sensitive to assumptions about ice sheet behavior, some are sensitive to assumptions about confidence in GCM output. Due to the wide range of projections in the CMIP5 ensemble at New York City [Yin, 2012], the 99.5th percentile projections are 212 cm under default assumptions, 205 cm under High GCM Confidence, and 232 cm under Reduced DOF. Even at New York City, however, GCM uncertainty remains secondary to ice sheet uncertainty; the 99.5th percentile is 178 cm under AR, 212 cm under Alt. Corr., and 359 cm under BA. Moreover, the significance of GCM uncertainty can be quite small: at the sites discussed above, the difference between the 99.5th percentiles of the High GCM Conﬁdence and Reduced DOF cases under RCP 8.5 in 2100 is 27 cm at New York, 19 cm at Sewell’s Point, 12 cm at Cuxhaven, 9 cm at Galveston, and 6 cm or less at Honolulu, Juneau, Key West, Kushimoto, San Francisco, and Valparaiso. A large difference (55 cm) at Stockholm may reflect differences between GCMs in the representation of the semi-closed Baltic Sea.

These sensitivity analyses are not exhaustive. There remains a need for improved ice sheet models to allow robust projections of the ice sheet component without heavy reliance upon expert elicitation. However, the development of such models is hindered by the limited consensus on the magnitude of positive and negative feedbacks on ice loss, such as those involving (a) temperature and snow albedo [Picard et al., 2012], (b) forest ﬁres and snow albedo [Keegan et al., 2014], (c) snowfall and ice sheet discharge [Winkelmann et al., 2012], (d) grounding line retreat [Joughin et al., 2014; Rignot et al., 2014; Schoof , 2007],(e) static-equilibrium sea-level and grounding line retreat [Gomez et al., 2010, 2012, 2013], (f ) meltwater, ocean temperature, sea ice, and snowfall [Bintanja et al., 2013], and (g) ice-cliff collapse [Bassis and Walker, 2012; Pollard and DeConto, 2013]. The wide range of projections and underlying uncertainties in continental-scale model projections pose challenges for interpreting the likelihood of their results [Bindschadler et al., 2013]. It is possible, however, that incomplete information could be better integrated in a probabilistic framework [Little et al., 2013a, 2013b].

Furthermore, structural errors in models of other sea level components remain probable. These errors (e.g., a systematic bias caused by a missing process and/or feedback) may have a large impact on tails. Here, we do not attempt to perform a systematic analysis. However, we believe that this framework may be used to effectively allow for these possibilities to be considered. The subjective judgment applied in formulating these distributions is explicit and may be revisited over time.

Implications for Coastal Flooding
---------------------------------

Since our projections provide full probability distributions, they can be combined with extreme value distributions to estimate the expected number of years in which flooding exceeds a given elevation, integrated over a given interval of time. Note that this is different from the expected number of flood events in a single year; the question here is not, “what is the probability of a flood of at least height X, given the projected sea-level change in 2050?” but, “in how many years between 2000 and 2050 do we expect floods of at least height X, given the projected pathway of sea level change?” Table 4 shows the expected number of years under each RCP with current “1-in-10 year” (10% probability per year) and “1-in-100 year” (1% probability per year) flood events for a selection of sites over 2001 – 2030, 2001 – 2050, and 2001 – 2100. Figure 7 shows the expected fraction of years with at least one event at the New York City, Key West, Cuxhaven, and Kushimoto tide gauges for a range of heights and the same periods of time under RCP 8.5; additional tide gauges and RCPs are shown in Supporting Information Figure S10.

**Table 4**: Expected number of years with flood events of a given height under different RCPs. Heights for U.S. sites are with respect to the local mean higher high water datum for the 1983–2001 epoch. Heights for non-U.S. sites are with respect to the local mean sea level datum for the 1983–2001 epoch.

.. figure:: figures/kopp14/fig07.jpg
   :align: center
   :width: 50%

   Figure 7: Expected fraction of years with flooding at tide gauges in excess of a given height under stationary sea level (black) and RCP 8.5 over 2001 – 2030 (blue), 2050 (green) and 2100 (red). Grey vertical lines indicate the current 1-in-10 and 1-in-100 year flood levels. Heights are relative to mean higher high water for U.S. sites and mean sea level for non-U.S. sites.


.. figure:: figures/kopp14/figS10.png
   :align: center
   :width: 50%

   Figure S10. Expected fraction of years with flooding at tide gauges in excess of a given height under stationary sea level (solid black), RCP 2.6 (dot-dashed), RCP 4.5 (dashed) and RCP 8.5 (solid), over 2001 to 2030 (blue), 2050 (green) and 2100 (red). Grey vertical lines indicate the current 1-in-10 and 1-in-100 year flood levels. Heights are relative to mean higher high water for U.S. sites and mean sea level for non-U.S. sites.

At seven of the nine sites considered (New York, Sewell’s Point, Key West, Galveston, San Francisco, Kushimoto, and Valparaiso, though not Cuxhaven or Stockholm), the expected number of years with current 1-in-10 year flood events, integrated over the 21st century, is under all RCPs at least five times larger than the 10 that would be predicted without sea-level rise. At the same seven sites, the expected number of years in the 21st century with current 1-in-100 year flood events is at least four times higher under RCP 2.6 and at least 8 times higher under RCP 8.5 than the 1 that would be expected without sea-level rise.

The increase in expected flood events is influenced both by the magnitude of projected LSL rise and by the range of past flood events. The latter is reflected in the difference between the 1-in-10 year and 1-in-100 year flood elevations, which will be larger at tide gauges that have experienced more extreme flood events. New York City and Cuxhaven are projected to experience fairly high sea-level rise (likely 0.7 to 1.3 m and 0.6 to 1.1 m by 2100 under RCP 8.5, respectively) but have also historically experienced large flood events, with the 1-in-100 year flood level about 70 cm higher than the 1-in-10 year flood level. Under RCP 8.5, these two sites respectively expect nine and four 1-in-100 year floods over the 21st century — the same as would be expected for 1-in-11 year and 1-in-25 year events without sea-level rise.

Stockholm has experienced fairly few large flood events, with the 1-in-100 year flood level only about 20 cm higher than the 1-in-10 year flood level, but also has a low projected sea-level rise (likely –0.2 to 0.5 m). As a consequence, it also expects nine 1-in-100 year floods over the 21st century under RCP 8.5. Key West, by contrast, has a projected sea-level rise similar to Cuxhaven but has not experienced as many large flood events. The 1-in-100 year flood level there is only about 23 cm higher than the 1-in-10 year flood level. Accordingly, it is expected to experience 48 years over the 21st century with a 1-in-100 year flood event, about the same as would be expected for a 1-in-2 year event without sea-level rise

The most extreme case among the nine sites considered is Kushimoto, which both has a large projected sea-level rise (likely 0.8 – 1.3 m by 2100) and has experienced few large flood events, with the 1-in-100 year flood level just 10 cm higher than the 1-in-10 year flood level. Over the course of the 21st century, under all RCPs, Kushimoto is expected to experience more than 60 years with flooding exceeding the current 1-in-100 year flood level.

Sea-level rise allowances [Hunter et al., 2013] quantify the amount by which a structure needs to be raised so that its current flood probability remains unchanged. For example, the U.S. National Flood Insurance Program’s Special Flood Hazard Areas are deﬁned as areas with a 1% per year flood probability [National Flood Insurance Program, 2013]. A corresponding sea-level rise allowance would indicate the height above the current 1-in-100 year flood zone that would maintain an average 1% per year flood probability over the period of interest. Note that, because the allowance is with respect to flood risk integrated over time, its magnitude is less than that of the sea-level change expected by the end of the period of interest. At New York City, a project with a 2001–2030 lifetime, such as a house with a 30-year mortgage, would need to be elevated by 17 cm above the no-sea-level-rise 1-in-100 year flood zone to maintain a 1% per year flood probability. An infrastructure project with a 2001–2050 lifetime would need to be raised 26 cm, while a project with a 2001–2100 life time would need to be elevated by 52–69 cm, depending on the emissions trajectory (Figure 7).


Cautions
--------

In addition to highlighting the sensitivities and research needs noted in section 4, we raise several cautions in interpreting our projections.

First, in the near-term, internal variability in sea-level rise [e.g., Bromirski et al., 2011] makes estimation of precise timing of LSL change difficult. Most sites experience interannual variability with a 2 sigma ($\sigma$) range of about 4 – 10 cm [Hay et al., 2013; Kopp et al., 2010]. At the illustrative sites we consider, the difference between the 17th and 83rd percentile projections exceeds the decimeter level between 2030 and 2050. Until this threshold is reached, year-to-year variability will be comparable to the uncertainty in projections.

Second, as previously noted, historically estimated background rates of local, non-climatic processes may not continue unchanged. For example, while we project 72 ± 5 cm of 21st century sea-level rise due to non-climatic factors at Grand Isle, Louisiana, changes in fluid withdrawal could reduce the projection [Blum and Roberts, 2012].

Third, our background rate estimates are the result of an algorithm applied to a global database of tide-gauge data, with different sites having been subjected to different degrees of quality control. Some tide-gauge sites may have experienced datum shifts or other local sources of errors not identified by the analysis. We recommend that users of projections for practical applications in specific regions scrutinize local tide-gauge records for such effects.

Fourth, our flood probability estimates should be viewed indicatively. They are based on hourly tide-gauge records that may be of insufficient length to capture accurately the statistics of rare flood events. They do not account for projected changes in tropical or extratropical cyclone climatology, such as the expectation that Category 4 and 5 hurricanes may become more frequent in the North Atlantic [e.g., Bender et al., 2010] and perhaps globally [Emanuel, 2013]. They are developed for specific tide-gauge locations where flood risk is likely indicative of, but not identical to, risk for the wider vicinity, due to variation in local topography and hydrodynamics. Nonetheless, they do highlight the inadequacy of flood risk assessments based on historic flood probabilities for guiding long-term decisions in the face of ongoing sea-level rise.


Conclusions
-----------

Assessments of climate change risk, whether in the context of evaluation of economic costs or the planning of resilient coastal communities and ecosystem reserves, require projections of sea-level changes that characterize not just likely sea-level changes but also tail risk. Moreover, these projections must estimate sea-level change at specific locations, not just at the global mean. They must also cover a range of timescales relevant for planning purposes, from the 30-year time scale of a typical U.S. mortgage, to the > 50 year lifetime of long-lived infrastructure projects, to the > 1 century lifetime of the development effects of infrastructure investments. In this article, we synthesize several lines of information, including model projections, formal expert elicitation, and expert assessment as embodied in the Intergovernmental Panel on Climate Change’s Fifth Assessment Report, to generate projections that fulfill all three desiderata.

Under RCP 8.5, we project a very likely mean global sea-level rise of 0.5 – 1.2 m by 2100 and 1.0 – 3.7 m by 2200, which under the strong emissions mitigation of RCP 2.6 is lowered to 0.3 – 0.8 m by 2100 and 0.3 – 2.4 m by 2200. Local sea-level rise projections differ from the global mean due to differing background rates of non-climatic sea-level change, spatially variable responses to different land ice reservoirs due to static-equilibrium effects, and spatially variable ocean steric and dynamic changes. Static-equilibrium effects lead to a tendency for greater-than-global sea-level rise in the central and western Paciﬁc Ocean. Mid-latitude and high-latitude sites in North America and Europe are generally less exposed to climatically driven sea-level change, with the exception of northeastern North America, which has potential for a high oceanographic sea-level contribution. At most sites, by the end of the century, uncertainty is due primarily to uncertainty in AIS mass loss, though oceanographic uncertainty is also a major term at sites where oceanographic processes may make a significant contribution to sea-level rise.

Probabilistic projections of future local sea-level rise pathways can be combined with statistical or hydrodynamic flood projections to estimate flood probabilities that more accurately assess the risks relevant to structures and populations. Projected sea-level rise can dramatically change estimated risks; at the Battery in New York City, for example, we project over the 21st century an expected nine years with “1-in-100 year”’ flood events under RCP 8.5 and four under RCP 2.6. Such projections, especially if improved or augmented by more detailed storm and flood models that include factors such as changes in tropical and extratropical cyclone climatology and by hydrodynamic models of overland flooding, can guide insurance, land use planning, and other forms of coastal climate change risk management.


Supplementary methods
---------------------

Ice sheet mass loss
~~~~~~~~~~~~~~~~~~~

To reconcile the AR5 and BA13 projections of ice sheet mass loss, we first fit log-normal distributions to the rates of ice mass change in 2100 for AR5 and BA13. Assuming linear increases in ice loss rates from the levels of 2000–2011 [Shepherd et al., 2012], we calculate a distribution of cumulative ice sheet mass loss at each time point. We then shift the BA13-derived projections by a constant, so that their medians agree with those of the AR5-derived projections. Since BA13 separates WAIS and EAIS while AR5 does not, we approximate the median ‘AR5’ WAIS contribution by scaling the AR5 median AIS estimate by the ratio of the median BA13 WAIS projection to the median BA13 AIS projection. Finally, we apply a multiplier to the difference from the median so that the derived distribution matches the 67% probability AR5 range. We use separate multipliers for outcomes above and below the median projections. For example, for RCP 8.5 in 2100, we decrease the RCP 8.5 projections for AIS by 10 cm (from 14 cm to 4 cm), then multiply positive deviations from the median by 0.4 and negative deviations by 1.0. We use the same scale factors for WAIS and for total AIS. The resulting distributions are shown in Table S1 and Figure S1.


Glacier and ice caps
~~~~~~~~~~~~~~~~~~~~

We project mass loss for seventeen glacier and ice cap source regions: Alaska, Western Canada and the United States, Ellesmere Island, Ban Island, the Greenland periphery, Iceland, Svalbard, Scandinavia, Kamchatka, Novaya Zemlya, the Alps, the Caucasus, the northern Himalayas, the southern Himalayas, the low latitude Andes, Patagonia, and New Zealand. (Following AR5, Antarctic peripheral glaciers and ice caps are included in the calculation of AIS mass loss.)


Oceanographic processes
~~~~~~~~~~~~~~~~~~~~~~~

The ‘zostoga’ or (for the GFDL models) ‘zosga’ variables were used for GSL, while for LSL the global term was added to the local dynamic sea level anomaly, given by the difference between ‘zos’ and the global mean of ‘zos’.

To account for identifiable problems with specific models (for example, the way some models, such as MIROC-ESM, handle inland seas), we remove on a site-by-site basis projections that have an amplitude in 2100 more than ten times the median local amplitude. In cases where the standard deviation of projections in 2100 (after removal of the extreme outliers identified by the median amplitude) is greater than 20 cm, we also remove models that deviate from the mean by more than three standard deviations. Finally, to account for discrepancies in the accounting of sea surface height where there is sea ice coverage, we exclude MIROC and GISS models at latitudes greater than 50 degrees. Figure S4 shows the median and likely range of the projected ocean dynamic contribution to RCP 8.5 in 2100 (excluding the effects of global mean thermal expansion), as well as the number of models contributing to the assessment at each site after the removal of outliers.


Gaussian process model for tide gauge data
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The Gaussian process prior for sea level has a mean given by the GIA projections of the ICE-5G VM2-90 model [Peltier , 2004] and a covariance given by the covariance function $k(r_1,t_1,r_2,t_2)$. The covariance is the sum of three terms: one representing GSL change ($k_{global}$), one representing linear local and regional sea-level changes ($k_{linear}$), and one representing non-linear local and regional sea-level changes ($k_{nonlin}$). The covariance function is given by
$$ k(r_1,t_1,r_2,t_2) = k_{global}(t_1,t_2) + k_{linear}(r_1,t_1,r_2,t_2) + k_{linear}(r_1,t_1,r_2,t_2) + k_{nonlin}(r_1,t_1,r_2,t_2) $$ (S1)

$$ k_{global}(t_1,t_2) = \theta^2_1 t_1 t_2 + \theta^2_2 C(| t_2-t_1 | /\theta_3,\theta_4) $$ (S2)

$$ k_{linear}(r_1,t_1,r_2,t_2) = \theta^2_5 t_1 t_2 \times (\theta_7 \delta_{r1,r2} + (1 - \theta_7) \times D(\alpha(r_1, r_2)/\theta_6)) + \delta_{r1,r2} \theta^2_\Delta $$ (S3)

$$ k_{nonlin}(r_1,t_1,r_2,t_2) = \theta^2_8 C( | t_2 - t_1 | /\theta_9,\theta_{10}) \times (\theta_{11}\delta_{r1,r2} + (1 - \theta_{11}) \times D(\alpha(r_1, r_2)/\theta_{12})) $$ (S4)

$$ \theta_\Delta = 50 \sqrt{\theta^2_1 + \theta^2_5} $$ (S5)

$$ C(r,v) = \frac{2^{1-v}}{\Gamma(v)} (\sqrt{2v}r)^v K_v (\sqrt{2v}r) $$ (S6)

$$ D(r) = (1 + \sqrt{5}r + 5r^2 / 3) \times \exp{(-\sqrt{5}r)} $$ (S7)

where $\theta_i$ are hyperparameters, $C$ is a Matérn covariance function with smoothness parameter $v$, $\Gamma$ is the gamma function, $K_v$ is a modified Bessel function of the second kind, $D$ is a twice-differentiable Matérn covariance function with smoothness parameter $v = 5/2$, $\delta_{i,j}$ is the Kroneker delta function (equal to 1 if $i = j$ and 0 otherwise), and $\alpha(r_1,r_2)$ is the angular distance between points $r_1$ and $r_2$ [Rasmussen and Williams, 2006]. The product terms $(t_1t_2)$ represent linear deviations from the prior mean; the times $t_i$ are measured with respect to the year 2005 CE.

The hyperparameters reflect prior estimates of: the amplitude of the rate of linear GSL change ($\theta_1$), the amplitude of non-linear GSL change ($\theta_2$), the timescale of non-linear GSL change ($\theta_3$), the smoothness of non-linear GSL change ($\theta_4$), the amplitude of the rate of linear LSL change ($\theta_5$), the spatial scale of regionally-coherent linear LSL change ($\theta_6$), the fraction of linear LSL change that is not regionally coherent ($\theta_7 \in [0, 1]$), the amplitude of non-linear LSL change ($\theta_8$), the timescale of non-linear LSL change ($\theta_9$), the smoothness of non-linear LSL change ($\theta_{10}$), the fraction of non-linear LSL change that is not regionally coherent ($\theta_{11} \in [0, 1]$), the spatial scale of regionally-coherent non-linear LSL change ($\theta_{12}$), and the amplitude of datum offsets between tide gauges ($\theta_{\Delta}$).

The regions for hyperparameter tuning (Table S4, Figure S6) are defined using the coastlines defined by the Permanent Service for Mean Sea Level (PSMSL) [Holgate et al., 2013] (Permanent Service for Mean Sea Level, Tide gauge data, retrieved from http://www.psmsl.org/data/obtaining/, accessed January 2014). There is limited overlap between regions; for prediction in areas where regions overlap, the prediction from the region with more data is used.

For each region, we first optimize the hyperparameters of $k_{global}$ to maximize the likelihood of the GSL curve of Church and White [2011]. Then, we optimize the hyperparameters through a four step process: first optimizing assuming no spatial correlation ($\theta_7,\theta_{11} = 1$), then optimizing the spatial correlation of the background linear term, then re-optimizing assuming no spatial correlation in the non-linear terms ($\theta_{11} = 1$), then finally optimizing the spatial correlation of the Matérn terms. For the hyperparameter optimization, we only consider the longest half of all tide gauges in a region provided that there are more than five tide gauges in the region; otherwise (as occurs in the Antarctic and Iceland/Svalbard regions), we include any tide gauge with a record length of at least 15 years.

Within each region, we estimate the regional and local linear rates using the optimized model for that region, applied to the tide gauge data from the region and the GSL curve of Church and White [2011]. We then fit the regional field of linear rates with a Gaussian process having mean 0 and covariance function

$$ \theta_5^2 t_1 t_2 \times (\theta_7^2 D (\alpha(r_1,r_2)/\theta_6^{\prime}) + (1 - \theta_7)^2 D (\alpha(r_1,r_2)/\theta_6)) $$,

optimizing $\theta_6^{\prime}$ under the constraint that $\theta_6^{\prime} < \theta_6$. This additional step allows for spatial continuity in rates at a finer length scale than $\theta_6$. Optimized hyperparameters are listed in Table S4.


References
----------

Bamber, J. L., and W. P. Aspinall (2013), An expert judgement assessment of future sea level rise from the ice sheets, Nat. Clim. Change, 3, 424 – 427, doi:10.1038/nclimate1778.
Bassis, J. N., and C. C. Walker (2012), Upper and lower limits on the stability of calving glaciers from the yield strength envelope of ice, Proc. R. Soc. A Math. Phys. Eng. Sci., 468(2140), 913 – 931, doi:10.1098/rspa.2011.0422.
Bender, M. A., T. R. Knutson, R. E. Tuleya, J. J. Sirutis, G. A. Vecchi, S. T. Garner, and I. M. Held (2010), Modeled impact of anthropogenic warming on the frequency of intense Atlantic hurricanes, Science, 327(5964), 454 – 458, doi:10.1126/science.1180568.
Bindschadler, R. A., et al. (2013), Ice-sheet model sensitivities to environmental forcing and their use in projecting future sea level (the SeaRISE project), J. Glaciol., 59(214), 195 – 224, doi:10.3189/2013JoG12J125.
Bintanja, R., G. J. Van Oldenborgh, S. S. Drijfhout, B. Wouters, and C. A. Katsman (2013), Important role for ocean warming and increased ice-shelf melt in Antarctic sea-ice expansion, Nat. Geosci., 6(5), 376 – 379, doi:10.1038/ngeo1767.
Blum, M. D., and H. H. Roberts (2012), The Mississippi delta region: past, present, and future, Annu. Rev. Earth Planet. Sci., 40, 655 – 683, doi:10.1146/annurev-earth-042711-105248.
Bromirski, P. D., A. J. Miller, R. E. Flick, and G. Auad (2011), Dynamical suppression of sea level rise along the Paciﬁc coast of North America: Indications for imminent acceleration, J. Geophys. Res., 116, C07,005, doi:10.1029/2010JC006759.
Chao, B. F., Y. H. Wu, and Y. S. Li (2008), Impact of artiﬁcial reservoir water impoundment on global sea level, Science, 320(5873), 212 – 214, doi:10.1126/science.1154580.
Church, J. A., et al. (2013), Chap. 13: Sea level change, in Climate Change 2013: The Physical Science Basis, edited by T. F. Stocker, D. Qin, G.-K. Plattner, M. Tignor, S. K. Allen, J. Boschung, A. Nauels, Y. Xia, V. Bex, and P. Midgley, pp. 1137 – 1216, Cambridge Univ. Press, Cambridge, U. K..
Church, J., and N. White (2011), Sea-level rise from the late 19th to the early 21st century, Surv. Geophys., 32(4), 585 – 602, doi:10.1007/s10712-011-9119-1.
Emanuel, K. A. (2013), Downscaling CMIP5 climate models shows increased tropical cyclone activity over the 21st century, Proc. Natl. Acad. Sci. U. S. A., 110(30), 12,219 – 12,224, doi:10.1073/pnas.1301293110.
Farrell, W. E., and J. A. Clark (1976), On postglacial sea level, Geophys. J. Roy. Astron. Soc., 46(3), 647 – 667, doi:10.1111/j.1365-246X.1976.tb01252.x.
Gomez, N., J. X. Mitrovica, P. Huybers, and P. U. Clark (2010), Sea level as a stabilizing factor for marine-ice-sheet grounding lines, Nat. Geosci., 3(12), 850 – 853, doi:10.1038/ngeo1012.
Gomez, N., D. Pollard, J. X. Mitrovica, P. Huybers, and P. U. Clark (2012), Evolution of a coupled marine ice sheet–sea level model, J. Geophys. Res., 117, F01,013, doi:10.1029/2011JF002128.
Gomez, N., D. Pollard, and J. X. Mitrovica (2013), A 3-D coupled ice sheet: Sea level model applied to Antarctica through the last 40 ky, Earth Planet. Sci. Lett., 384, 88 – 99, doi:10.1016/j.epsl.2013.09.042.
Gregory, J. M., et al. (2013), Twentieth-century global-mean sea-level rise: is the whole greater than the sum of the parts?, J. Clim., 26, 4476 – 4499, doi:10.1175/JCLI-D-12-00319.1.
Hay, C. C., E. Morrow, R. E. Kopp, and J. X. Mitrovica (2013), Estimating the sources of global sea level rise with data assimilation techniques, Proc. Natl. Acad. Sci. U. S. A., 110(S1), 3692 – 3699, doi:10.1073/pnas.1117683109.
Holgate, S. J., A. Matthews, P. L. Woodworth, L. J. Rickards, M. E. Tamisiea, E. Bradshaw, P. R. Foden, K. M. Gordon, S. Jevrejeva, and J. Pugh (2013), New data systems and products at the permanent service for mean sea level, J. Coastal Res., 29(3), 493 – 504, doi:10.2112/JCOASTRES-D-12-00175.1.
Holt, J., et al. (2009), Modelling the global coastal ocean, Philos. Trans. R. Soc. A Math. Phys. Eng. Sci., 367(1890), 939 – 951, doi:10.1098/rsta.2008.0210.
Horton, B. P., S. Rahmstorf, S. E. Engelhart, and A. C. Kemp (2014), Expert assessment of sea-level rise by AD 2100 and AD 2300, Quat. Sci. Rev., 84, 1 – 6, doi:10.1016/j.quascirev.2013.11.002.
Horton, R. M., V. Gornitz, D. A. Bader, A. C. Ruane, R. Goldberg, and C. Rosenzweig (2011), Climate hazard assessment for stakeholder adaptation planning in New York City, J. Appl. Meteorol. Climatol., 50(11), 2247 – 2266, doi:10.1175/2011JAMC2521.1.
Hunter, J., J. Church, N. White, and X. Zhang (2013), Towards a global regionally varying allowance for sea-level rise, Ocean Eng., 71, 17 – 27, doi:10.1016/j.oceaneng.2012.12.041.
Intergovernmental Panel on Climate Change (2013), Summary for policy makers, in Climate Change 2013: The Physical Science Basis, edited by T. F. Stocker, D. Qin, G.-K. Plattner, M. Tignor, S. K. Allen, J. Boschung, A. Nauels, Y. Xia, V. Bex, and P. Midgley, pp. 3 – 29, Cambridge Univ. Press, Cambridge, U. K.
Jevrejeva, S., J. Moore, and A. Grinsted (2012), Sea level projections to AD2500 with a new generation of climate change scenarios, Global Planet. Change, 80 – 81, 14 – 20, doi:10.1016/j.gloplacha.2011.09.006.
Joughin, I., B. E. Smith, and B. Medley (2014), Marine ice sheet collapse potentially underway for the Thwaites Glacier Basin, West Antarctica, Science, 344, 735 – 738, doi:10.1126/science.1249055.
Katsman, C., et al. (2011), Exploring high-end scenarios for local sea level rise to develop ﬂood protection strategies for a low-lying delta — the Netherlands as an example, Clim. Change, 109(3), 617 – 645, doi:10.1007/s10584-011-0037-5.
Keegan, K. M., M. R. Albert, J. R. McConnell, and I. Baker (2014), Climate change and forest ﬁres synergistically drive widespread melt events of the greenland ice sheet, Proc. Natl. Acad. Sci. U. S. A., doi:10.1073/pnas.1405397111.
Knutson, T. R., J. L. McBride, J. Chan, K. Emanuel, G. Holland, C. Landsea, I. Held, J. P. Kossin, A. K. Srivastava, and M. Sugi (2010), Tropical cyclones and climate change, Nat. Geosci., 3(3), 157 – 163, doi:10.1038/ngeo779.
Kolker, A. S., M. A. Allison, and S. Hameed (2011), An evaluation of subsidence rates and sea-level variability in the northern Gulf of Mexico, Geophys. Res. Lett., 38(21), L21,404, doi:10.1029/2011GL049458.
Konikow, L. F. (2011), Contribution of global groundwater depletion since 1900 to sea-level rise, Geophys. Res. Lett., 38, L17,401, doi:10.1029/2011GL048604.
Kopp, R. E. (2013), Does the mid-Atlantic United States sea level acceleration hot spot reﬂect ocean dynamic variability?, Geophys. Res. Lett., 40, 3981 – 3985, doi:10.1002/GRL.50781.
Kopp, R. E., J. X. Mitrovica, S. M. Griffies, J. Yin, C. C. Hay, and R. J. Stouﬀer (2010), The impact of Greenland melt on local sea levels: a partially coupled analysis of dynamic and static equilibrium effects in idealized water-hosing experiments, Clim. Change, 103, 619 – 625, doi:10.1007/s10584-010-9935-1.
Larsen, C. F., R. J. Motyka, J. T. Freymueller, K. A. Echelmeyer, and E. R. Ivins (2005), Rapid viscoelastic uplift in southeast Alaska caused by post-Little Ice Age glacial retreat, Earth Planet. Sci. Lett., 237(3 – 4), 548 – 560, doi:10.1016/j.epsl.2005.06.032.
Levermann, A., A. Griesel, M. Hofmann, M. Montoya, and S. Rahmstorf (2005), Dynamic sea level changes following changes in the thermohaline circulation, Clim. Dyn., 24(4), 347 – 354, doi:10.1007/s00382-004-0505-y.
Levermann, A., P. U. Clark, B. Marzeion, G. A. Milne, D. Pollard, V. Radic, and A. Robinson (2013), The multimillennial sea-level commitment of global warming, Proc. Natl. Acad. Sci. U. S. A., 110(34), 13,745 – 13,750, doi:10.1073/pnas.1219414110.
Little, C. M., N. M. Urban, and M. Oppenheimer (2013a), Probabilistic framework for assessing the ice sheet contribution to sea level change, Proc. Natl. Acad. Sci. U. S. A., 110(9), 3264 – 3269, doi:10.1073/pnas.1214457110.
Little, C. M., M. Oppenheimer, and N. M. Urban (2013b), Upper bounds on twenty-ﬁrst-century Antarctic ice loss assessed using a probabilistic framework, Nat. Clim. Change, 3, 654 – 659, doi:10.1038/nclimate1845.
Marzeion, B., A. H. Jarosch, and M. Hofer (2012), Past and future sea-level change from the surface mass balance of glaciers, Cryosphere, 6, 1295 – 1322, doi:10.5194/tc-6-1295-2012.
Meinshausen, M., et al. (2011), The RCP greenhouse gas concentrations and their extensions from 1765 to 2300, Clim. Change, 109(1-2), 213 – 241, doi:10.1007/s10584-011-0156-z.
Miller, K. G., R. E. Kopp, B. P. Horton, J. V. Browning, and A. C. Kemp (2013), A geological perspective on sea-level rise and impacts along the U.S. mid-Atlantic coast, Earth’s Future, 1, 3 – 18, doi:10.1002/2013EF000135.
Milne, G. A., W. R. Gehrels, C. W. Hughes, and M. E. Tamisiea (2009), Identifying the causes of sea-level change, Nat. Geosci., 2(7), 471 – 478, doi:10.1038/ngeo544.
Mitrovica, J. X., N. Gomez, and P. U. Clark (2009), The sea-level ﬁngerprint of West Antarctic collapse, Science, 323(5915), 753, doi:10.1126/science.1166510.
Mitrovica, J. X., N. Gomez, E. Morrow, C. Hay, K. Latychev, and M. E. Tamisiea (2011), On the robustness of predictions of sea level ﬁngerprints, Geophys. J. Int., 187(2), 729 – 742, doi:10.1111/j.1365-246X.2011.05090.x.
National Flood Insurance Program (2013), General provisions, in Code of Federal Regulations, Title 44 — Emergency Management and Assistance § 59 , pp. 182 – 198 , U.S. Government Printing Oﬃce, Washington, D. C.
National Research Council (2012), Sea-Level Rise for the Coasts of California, Oregon, and Washington: Past, Present, and Future, The National Acad. Press, Washington, D. C.
New York City Panel on Climate Change (2013), Climate Risk Information 2013: Observations, Climate Change Projections and Maps, edited by C. Rosenzweig, and W. Solecki, NPCC2. Prepared for use by the City of New York Special Initiative on Rebuilding and Resiliency, New York.
O’Neill, B. C., E. Kriegler, K. Riahi, K. L. Ebi, S. Hallegatte, T. R. Carter, R. Mathur, and D. P. v. Vuuren (2014), A new scenario framework for climate change research: the concept of shared socioeconomic pathways, Clim. Change, 122, 387 – 400, doi:10.1007/s10584-013-0905-2.
Penduﬀ, T., M. Juza, L. Brodeau, G. C. Smith, B. Barnier, J.-M. Molines, A.-M. Treguier, and G. Madec (2010), Impact of global ocean model resolution on sea-level variability with emphasis on interannual time scales, Ocean Sci., 6(1), 269 – 284, doi:10.5194/os-6-269-2010.
Penduﬀ, T., M. Juza, B. Barnier, J. Zika, W. K. Dewar, A.-M. Treguier, J.-M. Molines, and N. Audiﬀren (2011), Sea level expression of intrinsic and forced ocean variabilities at interannual time scales, J. Clim., 24(21), 5652 – 5670, doi:10.1175/JCLI-D-11-00077.1.
Perrette, M., F. Landerer, R. Riva, K. Frieler, and M. Meinshausen (2013), A scaling approach to project regional sea level rise and its uncertainties, Earth Syst. Dyn., 4, 11 – 29, doi:10.5194/esd-4-11-2013.
Pfeﬀer, W. T., J. T. Harper, and S. O’Neel (2008), Kinematic constraints on glacier contributions to 21st-century sea-level rise, Science, 321(5894), 1340 – 1343, doi:10.1126/science.1159099.
Picard, G., F. Domine, G. Krinner, L. Arnaud, and E. Lefebvre (2012), Inhibition of the positive snow-albedo feedback by precipitation in interior Antarctica, Nat. Clim. Change, 2, 795 – 798, doi:10.1038/nclimate1590.
Pokhrel, Y. N., N. Hanasaki, P. J.-F. Yeh, T. J. Yamada, S. Kanae, and T. Oki (2012), Model estimates of sea-level change due to anthropogenic impacts on terrestrial water storage, Nat. Geosci., doi:10.1038/ngeo1476.
Pollard, D., and R. M. DeConto (2013), Modeling drastic ice retreat in Antarctic subglacial basins, Abstract GC34A-03 presented at 2013 Fall Meeting, AGU, San Francisco, Calif.
Rahmstorf, S. (2007), A semi-empirical approach to projecting future sea-level rise, Science, 315(5810), 368 – 370, doi:10.1126/science.1135456.
Rahmstorf, S., M. Perrette, and M. Vermeer (2012), Testing the robustness of semi-empirical sea level projections, Clim. Dyn., 39(3-4), 861 – 875, doi:10.1007/s00382-011-1226-7.
Riahi, K. (2013), Preliminary IAM scenarios based on the RCP/SSP framework, in Climate Change Impacts/Integrated Assessment XIX, Energy Modeling Forum, Snowmass, Colo. [Available at http://emf.stanford.edu/docs/340.]
Rignot, E., J. Mouginot, M. Morlighem, H. Seroussi, and B. Scheuchl (2014), Widespread, rapid grounding line retreat of Pine Island, Thwaites, Smith, and Kohler glaciers, West Antarctica, from 1992 to 2011, Geophys. Res. Lett., doi:10.1002/2014GL060140.
Schaeﬀer, M., W. Hare, S. Rahmstorf, and M. Vermeer (2012), Long-term sea-level rise implied by 1.5∘C and 2∘C warming levels, Nat.Clim. Change, 2, 867 – 870, doi:10.1038/nclimate1584.
Schoof, C. (2007), Ice sheet grounding line dynamics: Steady states, stability, and hysteresis, J. Geophys. Res., 112, F03S28, doi:10.1029/2006JF000664.
Slangen, A. B., C. A. Katsman, R. S. van de Wal, L. L. Vermeersen, and R. E. Riva (2012), Towards regional projections of twenty-ﬁrst century sea-level change based on IPCC SRES scenarios, Clim. Dyn., 38, 1191 – 1209, doi:10.1007/s00382-011-1057-6.
Slangen, A. B., M. Carson, C. A. Katsman, R. S. W. van de Wal, A. Köhl, L. L. A. Vermeersen, and D. Stammer (2014), Projecting twenty-ﬁrst century regional sea level changes, Clim. Change, 124, 317 – 332, doi:10.1007/s10584-014-1080-9.
Sriver, R. L., N. M. Urban, R. Olson, and K. Keller (2012), Toward a physically plausible upper bound of sea-level rise projections, Clim. Change, 115(3-4), 893 – 902, doi:10.1007/s10584-012-0610-6.
Stammer, D., A. Cazenave, R. M. Ponte, and M. E. Tamisiea (2013), Causes for contemporary regional sea level changes, Ann. Rev. Mar. Sci., 5(1), 21 – 46, doi:10.1146/annurev-marine-121211-172406.
Suzuki, T., H. Hasumi, T. T. Sakamoto, T. Nishimura, A. Abe-Ouchi, T. Segawa, N. Okada, A. Oka, and S. Emori (2005), Projection of future sea level and its variability in a high-resolution climate model: Ocean processes and Greenland and Antarctic ice-melt contributions, Geophys. Res. Lett., 32(19), L19,706, doi:10.1029/2005GL023677.
Taylor, K. E., R. J. Stouﬀer, and G. A. Meehl (2012), An overview of CMIP5 and the experiment design, Bull. Am. Meteorol. Soc., 93(4), 485 – 498, doi:10.1175/BAMS-D-11-00094.1.
Tebaldi, C., B. H. Strauss, and C. E. Zervas (2012), Modelling sea level rise impacts on storm surges along US coasts, Environ. Res. Lett., 7(1), 014,032, doi:10.1088/1748-9326/7/1/014032.
United Nations Department of Economics and Social Aﬀairs (2004), World Population in 2300, ESA/P/WP.187/Rev.1, New York.
United Nations Department of Economics and Social Aﬀairs (2014), World Population Prospects: The 2012 Revision, ESA/P/WP.227, New York.
Vermeer, M., and S. Rahmstorf (2009), Global sea level linked to global temperature, Proc. Natl. Acad. Sci. U. S. A., 106(51), 21,527 – 21,532, doi:10.1073/pnas.0907765106.
Wada, Y., L. P. H. van Beek, F. C. Sperna Weiland, B. F. Chao, Y.-H. Wu, and M. F. P. Bierkens (2012), Past and future contribution of global groundwater depletion to sea-level rise, Geophys. Res. Lett., 39(9), L09,402, doi:10.1029/2012GL051230.
White, W. A., and T. A. Tremblay (1995), Submergence of wetlands as a result of human-induced subsidence and faulting along the upper Texas Gulf Coast, J. Coastal Res., 11, 788 – 807.
Winkelmann, R., A. Levermann, M. A. Martin, and K. Frieler (2012), Increased future ice discharge from Antarctica owing to higher snowfall, Nature, 492(7428), 239 – 242, doi:10.1038/nature11616.
Yin, J. (2012), Century to multi-century sea level rise projections from CMIP5 models, Geophys. Res. Lett., 39(17), L17,709, doi:10.1029/2012GL052947.
Yin, J., and P. B. Goddard (2013), Oceanic control of sea level rise patterns along the east coast of the United States, Geophys. Res. Lett., 40, 5514 – 5520, doi:10.1002/2013GL057992.
Yin, J., M. E. Schlesinger, and R. J. Stouﬀer (2009), Model projections of rapid sea-level rise on the northeast coast of the United States, Nat. Geosci., 2(4), 262 – 266, doi:10.1038/ngeo462.


