====================
Yuan and Kopp (2021)
====================

:Title: Emulating Ocean Dynamic Sea Level by Two-Layer Pattern Scaling
:Key Points:
    - An emulator for DSL changes is developed based on a two-layer energy balance model and a two-layer pattern scaling technique
    - The two-layer emulator can better capture the evolution of DSL in corresponding coupled GCMs than scaling of global mean surface temperature
    - The two-layer emulator allows estimation of the probability of future DSL changes in various emission scenarios over multiple centuries

:Corresponding author: J. Yuan

:Citation: Yuan, J., & Kopp, R. E. (2021). Emulating ocean dynamic sea level by two-layer pattern scaling. Journal of Advances in Modeling Earth Systems, 13, e2020MS002323, https://doi.org/10.1029/2020MS002323

Abstract
--------

Ocean dynamic sea level (DSL) change is a key driver of relative sea level (RSL) change. Projections of DSL change are generally obtained from simulations using atmosphere-ocean general circulation models (GCMs). Here, we develop a two-layer climate emulator to interpolate between emission scenarios simulated with GCMs and extend projections beyond the time horizon of available simulations. This emulator captures the evolution of DSL changes in corresponding GCMs, especially over middle and low latitudes. Compared with an emulator using univariate pattern scaling, the two-layer emulator more accurately reflects GCM behavior and captures non-linearities and non-stationarity in the relationship between DSL and global-mean warming, with a reduction in global-averaged error during 2271-2290 of 36%, 24%, and 34% in RCP2.6, RCP4.5, and RCP8.5, respectively. Using the emulator, we develop a probabilistic ensemble of DSL projections through 2300 for four scenarios: Representative Concentration Pathway (RCP) 2.6, RCP 4.5, RCP 8.5, and Shared Socioeconomic Pathway (SSP) 3-7.0. The magnitude and uncertainty of projected DSL changes decrease from the high-to the low-emission scenarios, indicating a reduced DSL rise hazard in low- and moderate-emission scenarios (RCP2.6 and RCP4.5) compared to the high-emission scenarios (SSP3-7.0 and RCP8.5).

Plain Language Summary
----------------------
As climate warms, sea-level rise poses a major threat to coastal communities and ecosystems. A key driver of local sea level change is ocean dynamic sea level change, which is associated with changes in ocean density and circulation. The primary tools used to project changes in dynamic sea level are atmosphere-ocean general circulation models, which are computationally expensive. Here we develop an emulator for dynamic sea level changes that is, built upon a two-layer energy balance model. Considering both the rapid response of well-mixed surface layer and the delayed response of the deep ocean to forcing, the emulator facilitates the estimation of probability distributions of future dynamic sea level change under different emission scenarios and the extension of projections beyond the time horizon of available simulations from some atmosphere-ocean general circulation models. This emulator captures the evolution of dynamic sea level changes in the atmosphere-ocean general circulation models to which it is tuned, including the non-linear and non-stationary relationship between the dynamic sea level and global warming. The emulator thus facilitates the estimation of future local sea-level changes.

Introduction
------------

Sea-level rise impacts coastal communities and ecosystems through permanent inundation, increasingly common tidal flooding, and increasingly frequent and severe storm-driven flooding. Global-mean sea level (GMSL) is rising at an accelerating rate, and under most scenarios is projected to continue accelerating over the 21st century (Oppenheimer et al., 2019). Regional relative sea level (RSL) change differs from global-mean sea-level change due to a variety of processes operating on diverse timescales, including the gravitational, rotational, and deformational effects associated with mass redistribution and ocean dynamic effects associated with changes in surface winds, ocean currents, and heat and freshwater fluxes (Gregory et al., 2016, 2019; Kopp et al., 2015; Perrette et al., 2013; Stammer et al., 2013).

Atmosphere-ocean general circulation models (GCMs) are the primary tool used to project ocean dynamic sea level (DSL) change, but the computational demands of these models limit the utility of GCM ensembles for estimating the likelihood of different levels of future sea-level change. Ensembles such as the Coupled Model Intercomparison Project Phase 5 (CMIP5, Landerer et al., 2014; Taylor et al., 2012) are composed of models contributed based on voluntary effort, not the product of systematic experimental design; as such, they are an "ensemble of opportunity" rather than a probabilistic ensemble (Tebaldi & Knutti, 2007). The CMIP future projection experiments are driven by a small number of forcing scenarios - Representative Concentration Pathways (RCPs) in the case of CMIP5 - and model simulations are of different lengths; some simulations run the RCPs to the year 2100, while others extend these to 2300.

The computationally intensive nature of GCMs makes it challenging to produce large perturbed-physics ensembles that represent uncertainties in key feedback parameters, as well as to simulate forcing conditions intermediate between the RCPs. Simple climate models (SCMs) provide an alternative tool for estimating the uncertainties of future projections at the global scale, as they can capture the overall physics of climate evolution and can be run very fast even on a personal computer (Held et al., 2010; Meinshausen et al., 2011; Millar et al., 2017; Perrette et al., 2013). However, SCMs represent the climate at a highly aggregated (e.g., global or hemispheric) scale, and thus cannot produce spatial patterns of climate change at each time step.

Pattern scaling approaches are often used to translate the global mean surface air temperature (GSAT) change into regional-scale changes for impact analysis (Mitchell, 2003; Rasmussen et al., 2016; Santer, 1990; Tebaldi & Arblaster, 2014; Tebaldi et al.,2011). Generally speaking, pattern scaling uses a simple statistical model (often, linear regression) to relate local climatic changes to a variable such as GSAT change, assum.ing the patterns of local response to external forcing remain constant under increased forcing (Tebaldi & Arblaster, 2014).


Some previous studies use the pattern scaling approach to estimate the uncertainty in DSL projections (Bilbao et al., 2015; M. D. Palmer et al., 2020; Perrette et al., 2013). For example, Perrette et al. (2013) regressed DSL change on GSAT. At New York City, they found that r\ :sup:`2` \values across models vary between 0.02 and 0.85, and also that the linear relationship between DSL and GSAT becomes weaker after the 21st century. Bilbao et al. (2015) examined the relationship between DSL and several variables, including GSAT, global-mean sea-surface temperature, ocean volume mean temperature, and global-mean thermosteric sea-level rise (GMTSLR). They found that GSAT performed best in predicting 21st-century DSL change in a high emissions scenario (RCP 8.5), while ocean-volume mean temperature and GMTSLR performed better in lower emissions scenarios (RCP 2.6 and 4.5). They speculated that this difference reflects a more important role for surface warming relative to deep warming in a more strongly forced scenario. They found that, across models and scenarios, area-weighted average root mean square error in pattern-scaled 2081–2100 DSL change ranged from ~1 to 3 cm.

Building upon Bilbao et al. (2015)'s speculation about the relative importance of shallow and deep warming under different scenarios, we developed a bivariate pattern scaling, which uses a multiple linear regression with two predictors: GSAT and global-mean deep ocean temperature change. The two temperature changes can be generated by a two-layer energy-balance model (2LM) (Held et al., 2010; Winton et al., 2010), which has proved to be a useful tool for understanding the responses of climate system to climate forcing (Geoffroy et al, 2013a, 2013b). Shallow and deep temperatures from a 2LM have previously been employed in an emulator to extend 21st century CMIP5 projections of GMTSLR to 2300 (M. D. Palmer et al., 2018), and M. D. Palmer et al. (2020) used GSAT from the two-layer model and univariate pattern scaling (based on GSAT) to emulate CMIP5 projections of DSL change.

In this study, we develop an emulator for DSL changes using both GSAT and deep-ocean temperature change projected by a 2LM. Here we drive the 2LM with radiative forcings from the Finite Amplitude Impulse Response model (FaIR), a SCM which includes a reduced-complexity carbon cycle and calculates atmospheric CO\ :sub:`2` \concentrations, radiative forcing and temperature changes based on emissions (Millar et al., 2017; Smith et al., 2017, 2018). FaIR was designed to more accurately reflect the temporal evolution of GSAT in response to a pulse emission, and it has been used in previous studies to produce observation-constrained future projections (Millar et al., 2017; Smith et al., 2017, 2018). In this study, we develop an emulator for GMTSLR and DSL change using surface and deep-ocean temperature changes generated by the FaIR-2LM (Section 2.2). As the univariate pattern scaling fails to capture the delayed response of the deep ocean to warming, we employ FaIR-2LM and two-layer pattern scaling to project future DSL changes, taking into account uncertainty in climate sensitivity, and demonstrate their ability to interpolate between climate scenarios run by GCMs. Compared to M. D. Palmer et al. (2018, 2020), which also use a 2LM to emulate GMTSLR or DSL projections, our approach differs in: (1) employing radiative forcings calculated based on emissions; (2) applying a format of 2LM considering efficacy factor of deep ocean heat uptake; (3) using both surface and deep-ocean temperature for pattern scaling (more details are described in supporting information).

Section 2 describes data and methodology, including the details of FaIR-2LM, the calibration of the FaIR.2LM based on selected CMIP5 GCMs, the two-layer pattern scaling methodology, and the application of this system to emulate DSL projections. Section 3 evaluates the performance of the two-layer pattern scaling. Section 4 shows the resulting ensemble of DSL projections. Finally, Section 5 discusses and summarizes the results.

Data and Methods
----------------

Data
~~~~

We use the zos variable from five CMIP5 general circulation models (GCMs) in RCP 2.6, 4.5, and 8.5 sce.narios: MPI-ESM-LR, bcc-csm1-1, HadGEM2-ES, GISS-E2-R, IPSL-CM5A-LR. These five GCMs are used because they were used to calibrate the parameters of the 2LM by Geoffroy et al. (2013) and provide multi-century data (to 2300) for zos in all three scenarios. DSL is taken as zos with its global mean removed, consistent with the definition of Gregory et al. (2019). The drift is removed from DSL by subtracting a linear function of time fitted to the pre-industrial control simulation from each scenario experiments, at each grid point. In addition, we remove the climatology in a baseline period (1986-2005) from DSL. The global mean surface air temperature (GSAT) and GMTSLR from the five models in the three scenarios are also used to evaluate the performance of FaIR-2LM.

FaIR-Two Layer Model (FaIR-2LM) and Calibration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This study develops a hybrid SCM model by replacing the temperature module in FaIR 1.3 (Smith et al., 2018) with a 2LM. In FaIR 1.3, GSAT changes are the sum of two components, representing fast and slow responses to effective radiative forcing (ERF) (Equation 22 in Smith et al., 2018). The fast and slow components of temperature changes in FaIR 1.3 mathematically depend on multiple coefficients (e.g., thermal response timescales) that are obtained from the ensemble mean of multiple CMIP5 models (Geoffroy, et al., 2013b). Since these components do not have an unambiguous physical meaning, it is challenging to link them to sea-level change. Therefore, we replace the temperature module in FaIR 1.3 by the 2LM to construct FaIR.2LM. In each step of FaIR-2LM, the 2LM is driven by radiative forcing from FaIR 1.3, and produces the GSAT anomaly, which feeds back to the FaIR carbon cycle (Figure S1).

.. figure:: figures/yuankopp21/figS01.jpg
   :align: center
   :width: 50%

   Figure S1: Schematic diagram of the FaIR-2LM (modified from Figure 1 of Smith et al. 2018).
   
We employ a 2LM that includes an efficacy term for deep ocean heat uptake (Geoffroy, et al., 2013a; Held et al., 2010; Winton et al., 2010):

C \frac{dT}{dt} = \mathcal{F} - \lambda T - \epsilon \gamma (T - T_0)  (1)

C_0 \frac{dT_0}{dt} = \gamma (T - T_0) (2)

where \mathcal{F} denotes the adjusted radiative forcing, C and C_0 are the heat capacity of the well-mixed upper layer and the deep ocean layer, respectively, and T and T_0 represent the global mean temperature anomalies of the upper and lower layer, respectively. Following Equation 22 in Geoffroy, et al. (2013b) and using C = 8.2 W yr m^{-2} K^{-1} and C_0 = 109 W yr m^{-2} K^{-1} based on an average across multiple CMIP5 GCMs (Geoffroy, et al., 2013a), we estimate the average depths of the upper layer and lower layer are 86 m and 1141 m, respectively. T is equivalent to GSAT perturbation (Held et al., 2010). \lambda is the parameter for climate feedback, \gamme is the coefficient of deep ocean heat uptake, and \epsilon is the efficacy factor of deep ocean heat uptake, which represents the uneven spatial distribution of heat exchanges between the two layers.

To calibrate FaIR-2LM, we adjust parameter settings (listed in Table 1) based on previous studies (Forster et al., 2013; Geoffroy, Saint-Martin, et al., 2013a; Zelinka et al., 2014). The radiative forcing in FaIR-2LM is driven by the default emission trajectory for each scenario in FaIR 1.3, but scaled by two parameters determined for each GCM: (1) the radiative forcing of CO_2 doubling (F_{2 \times CO_2}) reported by Forster et al. (2013), and (2) the present-day aerosol forcing (a*f_{pd}) estimated in previous studies (Forster et al., 2013; Zelinka et al., 2014), or -0.9 W m^{-2} - the median of range estimated by the Fifth Assessment Report of Intergovernmental Panel on Climate Change (IPCC AR5) (Stocker et al., 2013) - for models not reported in previous studies. The five parameters in Equations 1 and 2 (i.e., \lambda, \gamma, \epsilon, C, C_0) are the same as those in Geoffroy et al. (2013) for the corresponding GCMs.

Table 1: FaIR-2LM Parameters adjusted to match the GSAT in CMIP5 GCMs. :math:`\lambda` (W m\ :sup:`-2` K\ :sup:`-1`), :math:`\gamma` (W m\ :sup:`-2` K\ :sup:`-1`), :math:`\epsilon`, C (W yr m\ :sup:`-2` K\ :sup:`-1`), and :math:`C_0` (W yr m\ :sup:`-2` K\ :sup:`-1`) are reported by Geoffroy et al. (2013). The units for :math:`F_{2 \times CO_2}` and :math:`af_{pd}` are W m\ :sup:`-2`.

+--------------+-----------------+-----------------+------------------+-----+-------------+---------------------------+-----------------+
| CMIP5 GCMs   | :math:`\lambda` | :math:`\gamma`  | :math:`\epsilon` | C   | :math:`C_0` | :math:`F_{2 \times CO_2}` | :math:`af_{pd}` |
+--------------+-----------------+-----------------+------------------+-----+-------------+---------------------------+-----------------+
| bcc-csm1-1   |      1.28       | 0.59            | 1.27             | 8.4 | 56          | 3.23                      | -0.9            |
+--------------+-----------------+-----------------+------------------+-----+-------------+---------------------------+-----------------+
| GISS-E2-R    |   2.03          | 1.06            | 1.44             | 6.1 | 134         | 3.78                      | -0.9            |
+--------------+-----------------+-----------------+------------------+-----+-------------+---------------------------+-----------------+
| HadGEM2-ES   | 0.61            | 0.49            | 1.54             | 7.5 | 98          | 2.93                      | -1.23           |
+--------------+-----------------+-----------------+------------------+-----+-------------+---------------------------+-----------------+
| IPSL-CM5A-LR | 0.79            | 0.57            | 1.14             | 8.1 | 100         | 3.1                       | -0.68           |
+--------------+-----------------+-----------------+------------------+-----+-------------+---------------------------+-----------------+
| MPI-ESM-LR   | 1.21            | 0.62            | 1.42             | 8.5 | 78          | 4.09                      | -0.9            |
+--------------+-----------------+-----------------+------------------+-----+-------------+---------------------------+-----------------+

GSAT produced by the calibrated FaIR-2LM is compared with that from the corresponding GCMs in the three scenarios (Fig. S2). For the five GCMs, the GSAT simulated by FaIR-2LM is close to the GSAT from the corresponding GCM, with the root mean square error (RMSE) determined over the entire simulation period in a range of 0.15-0.23 K for RCP2.6, 0.14-0.32 K for RCP4.5, and 0.20-0.43 K for RCP8.5.

GMTSLR is driven by the thermal expansion of sea water volume due to the increase in ocean heat uptake. To calibrate GMTSLR in FaIR-2LM to match a specific GCM, we first correct the drift in the GCM's GMTSLR field by removing the linear trend in the pre-industrial control simulation, assuming the drift is not sensitive to the external forcing (Hobbs et al., 2016).

Then, we emulate GMTSLR based on the T and T_0 from FaIR-2LM following the approach described in Kuhlbrodt and Gregory (2012):

{GMTSLR} = \sigma \times (C \Delta T + C_0 \Delta T_0)

where \sigma is the expansion efficiency of heat in units of 10^{-24} m J^{-1}. The \sigma value is calibrated by optimizing GMTSLR emulated from FaIR-2LM to match the GMTSLR simulated from the corresponding GCM.


Two-Layer Pattern Scaling
~~~~~~~~~~~~~~~~~~~~~~~~~

[...]

Projecting DSL Using FaIR-2LM and Patterns
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

[...]


Evaluation of Two-Layer Pattern Scaling
---------------------------------------

[...]
