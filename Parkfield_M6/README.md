# CyberShake-ETAS Simulations, Parkfield M6

[View ETAS Simulation Information and Plots](etas_plots)

CyberShake Study: Study 15.4 with 336 sites

## Table Of Contents
* [Mapping Information](#mapping-information)
* [Conditional Hypocenter Distributions](#conditional-hypocenter-distributions)
  * [San Andreas (Cholame) rev CHD](#san-andreas-cholame-rev-chd)
  * [San Andreas (Parkfield) CHD](#san-andreas-parkfield-chd)
  * [San Andreas (Carrizo) rev CHD](#san-andreas-carrizo-rev-chd)
  * [San Andreas (Big Bend) CHD](#san-andreas-big-bend-chd)
  * [San Andreas (Mojave N) CHD](#san-andreas-mojave-n-chd)
* [Hazard Curves](#hazard-curves)
  * [SBSM Hazard Curves](#sbsm-hazard-curves)
    * [CyberShake SBSM Hazard Curves](#cybershake-sbsm-hazard-curves)
    * [CyberShake SBSM 5s Hazard Gain Table](#cybershake-sbsm-5s-hazard-gain-table)
    * [GMPE SBSM Hazard Curves](#gmpe-sbsm-hazard-curves)
    * [GMPE SBSM 5s Hazard Gain Table](#gmpe-sbsm-5s-hazard-gain-table)
  * [MRSD Hazard Curves](#mrsd-hazard-curves)
    * [CyberShake MRSD Hazard Curves](#cybershake-mrsd-hazard-curves)
    * [CyberShake MRSD 5s Hazard Gain Table](#cybershake-mrsd-5s-hazard-gain-table)
    * [GMPE MRSD Hazard Curves](#gmpe-mrsd-hazard-curves)
    * [GMPE MRSD 5s Hazard Gain Table](#gmpe-mrsd-5s-hazard-gain-table)
  * [STNI Hazard Curves](#stni-hazard-curves)
    * [CyberShake STNI Hazard Curves](#cybershake-stni-hazard-curves)
    * [CyberShake STNI 5s Hazard Gain Table](#cybershake-stni-5s-hazard-gain-table)
    * [GMPE STNI Hazard Curves](#gmpe-stni-hazard-curves)
    * [GMPE STNI 5s Hazard Gain Table](#gmpe-stni-5s-hazard-gain-table)
  * [PDU Hazard Curves](#pdu-hazard-curves)
    * [CyberShake PDU Hazard Curves](#cybershake-pdu-hazard-curves)
    * [CyberShake PDU 5s Hazard Gain Table](#cybershake-pdu-5s-hazard-gain-table)
    * [GMPE PDU Hazard Curves](#gmpe-pdu-hazard-curves)
    * [GMPE PDU 5s Hazard Gain Table](#gmpe-pdu-5s-hazard-gain-table)
* [Hazard Maps](#hazard-maps)
  * [5s One Day Hazard Maps](#5s-one-day-hazard-maps)
    * [One Day 5s Sa (g) with POE=1.0E-4, Maps](#one-day-5s-sa-g-with-poe10e-4-maps)
      * [One Day 5s Sa (g) with POE=1.0E-4, CyberShake Maps](#one-day-5s-sa-g-with-poe10e-4-cybershake-maps)
      * [One Day 5s Sa (g) with POE=1.0E-4, GMPE Maps](#one-day-5s-sa-g-with-poe10e-4-gmpe-maps)
    * [One Day 5s Sa (g) with POE=0.001, Maps](#one-day-5s-sa-g-with-poe0001-maps)
      * [One Day 5s Sa (g) with POE=0.001, CyberShake Maps](#one-day-5s-sa-g-with-poe0001-cybershake-maps)
      * [One Day 5s Sa (g) with POE=0.001, GMPE Maps](#one-day-5s-sa-g-with-poe0001-gmpe-maps)
    * [One Day 5s Sa (g) with POE=0.01, Maps](#one-day-5s-sa-g-with-poe001-maps)
      * [One Day 5s Sa (g) with POE=0.01, CyberShake Maps](#one-day-5s-sa-g-with-poe001-cybershake-maps)
      * [One Day 5s Sa (g) with POE=0.01, GMPE Maps](#one-day-5s-sa-g-with-poe001-gmpe-maps)
    * [One Day POE 0.01 (g) 5s SA, Maps](#one-day-poe-001-g-5s-sa-maps)
      * [One Day POE 0.01 (g) 5s SA, CyberShake Maps](#one-day-poe-001-g-5s-sa-cybershake-maps)
      * [One Day POE 0.01 (g) 5s SA, GMPE Maps](#one-day-poe-001-g-5s-sa-gmpe-maps)
    * [One Day POE 0.1 (g) 5s SA, Maps](#one-day-poe-01-g-5s-sa-maps)
      * [One Day POE 0.1 (g) 5s SA, CyberShake Maps](#one-day-poe-01-g-5s-sa-cybershake-maps)
      * [One Day POE 0.1 (g) 5s SA, GMPE Maps](#one-day-poe-01-g-5s-sa-gmpe-maps)
    * [One Day POE 0.2 (g) 5s SA, Maps](#one-day-poe-02-g-5s-sa-maps)
      * [One Day POE 0.2 (g) 5s SA, CyberShake Maps](#one-day-poe-02-g-5s-sa-cybershake-maps)
      * [One Day POE 0.2 (g) 5s SA, GMPE Maps](#one-day-poe-02-g-5s-sa-gmpe-maps)
    * [One Day POE 0.5 (g) 5s SA, Maps](#one-day-poe-05-g-5s-sa-maps)
      * [One Day POE 0.5 (g) 5s SA, CyberShake Maps](#one-day-poe-05-g-5s-sa-cybershake-maps)
      * [One Day POE 0.5 (g) 5s SA, GMPE Maps](#one-day-poe-05-g-5s-sa-gmpe-maps)
  * [5s One Day EATS Gains Table](#5s-one-day-eats-gains-table)
  * [5s One Week Hazard Maps](#5s-one-week-hazard-maps)
    * [One Week 5s Sa (g) with POE=1.0E-4, Maps](#one-week-5s-sa-g-with-poe10e-4-maps)
      * [One Week 5s Sa (g) with POE=1.0E-4, CyberShake Maps](#one-week-5s-sa-g-with-poe10e-4-cybershake-maps)
      * [One Week 5s Sa (g) with POE=1.0E-4, GMPE Maps](#one-week-5s-sa-g-with-poe10e-4-gmpe-maps)
    * [One Week 5s Sa (g) with POE=0.001, Maps](#one-week-5s-sa-g-with-poe0001-maps)
      * [One Week 5s Sa (g) with POE=0.001, CyberShake Maps](#one-week-5s-sa-g-with-poe0001-cybershake-maps)
      * [One Week 5s Sa (g) with POE=0.001, GMPE Maps](#one-week-5s-sa-g-with-poe0001-gmpe-maps)
    * [One Week 5s Sa (g) with POE=0.01, Maps](#one-week-5s-sa-g-with-poe001-maps)
      * [One Week 5s Sa (g) with POE=0.01, CyberShake Maps](#one-week-5s-sa-g-with-poe001-cybershake-maps)
      * [One Week 5s Sa (g) with POE=0.01, GMPE Maps](#one-week-5s-sa-g-with-poe001-gmpe-maps)
    * [One Week POE 0.01 (g) 5s SA, Maps](#one-week-poe-001-g-5s-sa-maps)
      * [One Week POE 0.01 (g) 5s SA, CyberShake Maps](#one-week-poe-001-g-5s-sa-cybershake-maps)
      * [One Week POE 0.01 (g) 5s SA, GMPE Maps](#one-week-poe-001-g-5s-sa-gmpe-maps)
    * [One Week POE 0.1 (g) 5s SA, Maps](#one-week-poe-01-g-5s-sa-maps)
      * [One Week POE 0.1 (g) 5s SA, CyberShake Maps](#one-week-poe-01-g-5s-sa-cybershake-maps)
      * [One Week POE 0.1 (g) 5s SA, GMPE Maps](#one-week-poe-01-g-5s-sa-gmpe-maps)
    * [One Week POE 0.2 (g) 5s SA, Maps](#one-week-poe-02-g-5s-sa-maps)
      * [One Week POE 0.2 (g) 5s SA, CyberShake Maps](#one-week-poe-02-g-5s-sa-cybershake-maps)
      * [One Week POE 0.2 (g) 5s SA, GMPE Maps](#one-week-poe-02-g-5s-sa-gmpe-maps)
    * [One Week POE 0.5 (g) 5s SA, Maps](#one-week-poe-05-g-5s-sa-maps)
      * [One Week POE 0.5 (g) 5s SA, CyberShake Maps](#one-week-poe-05-g-5s-sa-cybershake-maps)
      * [One Week POE 0.5 (g) 5s SA, GMPE Maps](#one-week-poe-05-g-5s-sa-gmpe-maps)
  * [5s One Week EATS Gains Table](#5s-one-week-eats-gains-table)
  * [5s One Year Hazard Maps](#5s-one-year-hazard-maps)
    * [One Year 5s Sa (g) with POE=1.0E-4, Maps](#one-year-5s-sa-g-with-poe10e-4-maps)
      * [One Year 5s Sa (g) with POE=1.0E-4, CyberShake Maps](#one-year-5s-sa-g-with-poe10e-4-cybershake-maps)
      * [One Year 5s Sa (g) with POE=1.0E-4, GMPE Maps](#one-year-5s-sa-g-with-poe10e-4-gmpe-maps)
    * [One Year 5s Sa (g) with POE=0.001, Maps](#one-year-5s-sa-g-with-poe0001-maps)
      * [One Year 5s Sa (g) with POE=0.001, CyberShake Maps](#one-year-5s-sa-g-with-poe0001-cybershake-maps)
      * [One Year 5s Sa (g) with POE=0.001, GMPE Maps](#one-year-5s-sa-g-with-poe0001-gmpe-maps)
    * [One Year 5s Sa (g) with POE=0.01, Maps](#one-year-5s-sa-g-with-poe001-maps)
      * [One Year 5s Sa (g) with POE=0.01, CyberShake Maps](#one-year-5s-sa-g-with-poe001-cybershake-maps)
      * [One Year 5s Sa (g) with POE=0.01, GMPE Maps](#one-year-5s-sa-g-with-poe001-gmpe-maps)
    * [One Year POE 0.01 (g) 5s SA, Maps](#one-year-poe-001-g-5s-sa-maps)
      * [One Year POE 0.01 (g) 5s SA, CyberShake Maps](#one-year-poe-001-g-5s-sa-cybershake-maps)
      * [One Year POE 0.01 (g) 5s SA, GMPE Maps](#one-year-poe-001-g-5s-sa-gmpe-maps)
    * [One Year POE 0.1 (g) 5s SA, Maps](#one-year-poe-01-g-5s-sa-maps)
      * [One Year POE 0.1 (g) 5s SA, CyberShake Maps](#one-year-poe-01-g-5s-sa-cybershake-maps)
      * [One Year POE 0.1 (g) 5s SA, GMPE Maps](#one-year-poe-01-g-5s-sa-gmpe-maps)
    * [One Year POE 0.2 (g) 5s SA, Maps](#one-year-poe-02-g-5s-sa-maps)
      * [One Year POE 0.2 (g) 5s SA, CyberShake Maps](#one-year-poe-02-g-5s-sa-cybershake-maps)
      * [One Year POE 0.2 (g) 5s SA, GMPE Maps](#one-year-poe-02-g-5s-sa-gmpe-maps)
    * [One Year POE 0.5 (g) 5s SA, Maps](#one-year-poe-05-g-5s-sa-maps)
      * [One Year POE 0.5 (g) 5s SA, CyberShake Maps](#one-year-poe-05-g-5s-sa-cybershake-maps)
      * [One Year POE 0.5 (g) 5s SA, GMPE Maps](#one-year-poe-05-g-5s-sa-gmpe-maps)
  * [5s One Year EATS Gains Table](#5s-one-year-eats-gains-table)
## Mapping Information

| Num Catalogs | 500000 |
|-----|-----|
| Mapped Ruptures | 7615 |
| Mean variations per ruptures | 8.992646 |
| Median variations per ruptures | 10.0 |
| Min variations per ruptures | 1.0 |
| Max variations per ruptures | 22.0 |

## Conditional Hypocenter Distributions
*[(top)](#table-of-contents)*

### San Andreas (Cholame) rev CHD
*[(top)](#table-of-contents)*

| One Day | One Week | One Year |
|-----|-----|-----|
| ![CHD](resources/chd_San_Andreas_Cholame_rev_ONE_DAY_hypos_combined.png) | ![CHD](resources/chd_San_Andreas_Cholame_rev_ONE_WEEK_hypos_combined.png) | ![CHD](resources/chd_San_Andreas_Cholame_rev_ONE_YEAR_hypos_combined.png) |

### San Andreas (Parkfield) CHD
*[(top)](#table-of-contents)*

| One Day | One Week | One Year |
|-----|-----|-----|
| ![CHD](resources/chd_San_Andreas_Parkfield__ONE_DAY_hypos_combined.png) | ![CHD](resources/chd_San_Andreas_Parkfield__ONE_WEEK_hypos_combined.png) | ![CHD](resources/chd_San_Andreas_Parkfield__ONE_YEAR_hypos_combined.png) |

### San Andreas (Carrizo) rev CHD
*[(top)](#table-of-contents)*

| One Day | One Week | One Year |
|-----|-----|-----|
| ![CHD](resources/chd_San_Andreas_Carrizo_rev_ONE_DAY_hypos_combined.png) | ![CHD](resources/chd_San_Andreas_Carrizo_rev_ONE_WEEK_hypos_combined.png) | ![CHD](resources/chd_San_Andreas_Carrizo_rev_ONE_YEAR_hypos_combined.png) |

### San Andreas (Big Bend) CHD
*[(top)](#table-of-contents)*

| One Day | One Week | One Year |
|-----|-----|-----|
| ![CHD](resources/chd_San_Andreas_Big_Bend__ONE_DAY_hypos_combined.png) | ![CHD](resources/chd_San_Andreas_Big_Bend__ONE_WEEK_hypos_combined.png) | ![CHD](resources/chd_San_Andreas_Big_Bend__ONE_YEAR_hypos_combined.png) |

### San Andreas (Mojave N) CHD
*[(top)](#table-of-contents)*

| One Day | One Week | One Year |
|-----|-----|-----|
| ![CHD](resources/chd_San_Andreas_Mojave_N__ONE_DAY_hypos_combined.png) | ![CHD](resources/chd_San_Andreas_Mojave_N__ONE_WEEK_hypos_combined.png) | ![CHD](resources/chd_San_Andreas_Mojave_N__ONE_YEAR_hypos_combined.png) |

## Hazard Curves
*[(top)](#table-of-contents)*

### SBSM Hazard Curves
*[(top)](#table-of-contents)*

| Site Location Map |
|-----|
| ![site map](resources/SBSM_location_map.png) |

#### CyberShake SBSM Hazard Curves
*[(top)](#table-of-contents)*

| Time Span | 3s | 5s | 10s |
|-----|-----|-----|-----|
| One Day | ![plot](resources/hazard_curves_cs_SBSM_3s_one_day.png) | ![plot](resources/hazard_curves_cs_SBSM_5s_one_day.png) | ![plot](resources/hazard_curves_cs_SBSM_10s_one_day.png) |
| One Week | ![plot](resources/hazard_curves_cs_SBSM_3s_one_week.png) | ![plot](resources/hazard_curves_cs_SBSM_5s_one_week.png) | ![plot](resources/hazard_curves_cs_SBSM_10s_one_week.png) |
| One Year | ![plot](resources/hazard_curves_cs_SBSM_3s_one_year.png) | ![plot](resources/hazard_curves_cs_SBSM_5s_one_year.png) | ![plot](resources/hazard_curves_cs_SBSM_10s_one_year.png) |

#### CyberShake SBSM 5s Hazard Gain Table
*[(top)](#table-of-contents)*

| Dividend | Divisor | One Day Min | One Day Max | One Week Min | One Week Max | One Year Min | One Year Max |
|-----|-----|-----|-----|-----|-----|-----|-----|
| CyberShake, TD | CyberShake, TI | 1.088 at 1.585 g | 1.445 at 0.158 g | 1.088 at 1.585 g | 1.445 at 0.158 g | 1.088 at 1.585 g | 1.443 at 0.158 g |
| CyberShake, Uniform ETAS | CyberShake, TD | 0.393 at 1.059 g | 10.285 at 1.496 g | 0.393 at 1.059 g | 10.285 at 1.496 g | 0.393 at 1.059 g | 10.285 at 1.496 g |
| CyberShake, ETAS | CyberShake, TD | 0.393 at 1.059 g | 13.983 at 0.126 g | 0.393 at 1.059 g | 10.285 at 1.496 g | 0.393 at 1.059 g | 10.285 at 1.496 g |
| CyberShake, ETAS | CyberShake, Uniform ETAS | 0.235 at 0.794 g | 1.513 at 0.126 g | 0.628 at 0.750 g | 1.369 at 0.126 g | 0.977 at 0.422 g | 1.031 at 0.126 g |

#### GMPE SBSM Hazard Curves
*[(top)](#table-of-contents)*

| Time Span | 3s | 5s | 10s |
|-----|-----|-----|-----|
| One Day | ![plot](resources/hazard_curves_gmpe_SBSM_3s_one_day.png) | ![plot](resources/hazard_curves_gmpe_SBSM_5s_one_day.png) | ![plot](resources/hazard_curves_gmpe_SBSM_10s_one_day.png) |
| One Week | ![plot](resources/hazard_curves_gmpe_SBSM_3s_one_week.png) | ![plot](resources/hazard_curves_gmpe_SBSM_5s_one_week.png) | ![plot](resources/hazard_curves_gmpe_SBSM_10s_one_week.png) |
| One Year | ![plot](resources/hazard_curves_gmpe_SBSM_3s_one_year.png) | ![plot](resources/hazard_curves_gmpe_SBSM_5s_one_year.png) | ![plot](resources/hazard_curves_gmpe_SBSM_10s_one_year.png) |

#### GMPE SBSM 5s Hazard Gain Table
*[(top)](#table-of-contents)*

| Dividend | Divisor | One Day Min | One Day Max | One Week Min | One Week Max | One Year Min | One Year Max |
|-----|-----|-----|-----|-----|-----|-----|-----|
| ASK2014, TD | ASK2014, TI | 1.159 at 0.010 g | 1.348 at 0.100 g | 1.159 at 0.010 g | 1.348 at 0.100 g | 1.154 at 0.010 g | 1.346 at 0.100 g |
| ASK2014, ETAS | ASK2014, TD | 2.359 at 10.000 g | 9.021 at 0.032 g | 1.375 at 10.000 g | 2.750 at 0.032 g | 1.015 at 10.000 g | 1.062 at 0.025 g |
| ASK2014+BS13 Directivity, ETAS | ASK2014, TD | 8.006 at 0.010 g | 19.251 at 10.000 g | 2.554 at 0.010 g | 4.449 at 3.981 g | 1.056 at 0.010 g | 1.131 at 5.012 g |
| ASK2014+BS13 Directivity, ETAS | ASK2014, ETAS | 1.028 at 0.010 g | 8.159 at 10.000 g | 1.018 at 0.010 g | 3.170 at 10.000 g | 1.001 at 0.010 g | 1.112 at 7.943 g |

### MRSD Hazard Curves
*[(top)](#table-of-contents)*

| Site Location Map |
|-----|
| ![site map](resources/MRSD_location_map.png) |

#### CyberShake MRSD Hazard Curves
*[(top)](#table-of-contents)*

| Time Span | 3s | 5s | 10s |
|-----|-----|-----|-----|
| One Day | ![plot](resources/hazard_curves_cs_MRSD_3s_one_day.png) | ![plot](resources/hazard_curves_cs_MRSD_5s_one_day.png) | ![plot](resources/hazard_curves_cs_MRSD_10s_one_day.png) |
| One Week | ![plot](resources/hazard_curves_cs_MRSD_3s_one_week.png) | ![plot](resources/hazard_curves_cs_MRSD_5s_one_week.png) | ![plot](resources/hazard_curves_cs_MRSD_10s_one_week.png) |
| One Year | ![plot](resources/hazard_curves_cs_MRSD_3s_one_year.png) | ![plot](resources/hazard_curves_cs_MRSD_5s_one_year.png) | ![plot](resources/hazard_curves_cs_MRSD_10s_one_year.png) |

#### CyberShake MRSD 5s Hazard Gain Table
*[(top)](#table-of-contents)*

| Dividend | Divisor | One Day Min | One Day Max | One Week Min | One Week Max | One Year Min | One Year Max |
|-----|-----|-----|-----|-----|-----|-----|-----|
| CyberShake, TD | CyberShake, TI | 0.988 at 0.316 g | 1.494 at 0.100 g | 0.988 at 0.316 g | 1.494 at 0.100 g | 0.988 at 0.316 g | 1.494 at 0.100 g |
| CyberShake, Uniform ETAS | CyberShake, TD | 0.740 at 0.299 g | 20.456 at 0.060 g | 0.740 at 0.299 g | 5.087 at 0.056 g | 0.740 at 0.299 g | 1.157 at 0.056 g |
| CyberShake, ETAS | CyberShake, TD | 0.740 at 0.299 g | 30.038 at 0.075 g | 0.740 at 0.299 g | 6.746 at 0.075 g | 0.740 at 0.299 g | 1.208 at 0.075 g |
| CyberShake, ETAS | CyberShake, Uniform ETAS | 0.553 at 0.168 g | 1.573 at 0.075 g | 0.869 at 0.133 g | 1.425 at 0.075 g | 0.994 at 0.168 g | 1.060 at 0.075 g |

#### GMPE MRSD Hazard Curves
*[(top)](#table-of-contents)*

| Time Span | 3s | 5s | 10s |
|-----|-----|-----|-----|
| One Day | ![plot](resources/hazard_curves_gmpe_MRSD_3s_one_day.png) | ![plot](resources/hazard_curves_gmpe_MRSD_5s_one_day.png) | ![plot](resources/hazard_curves_gmpe_MRSD_10s_one_day.png) |
| One Week | ![plot](resources/hazard_curves_gmpe_MRSD_3s_one_week.png) | ![plot](resources/hazard_curves_gmpe_MRSD_5s_one_week.png) | ![plot](resources/hazard_curves_gmpe_MRSD_10s_one_week.png) |
| One Year | ![plot](resources/hazard_curves_gmpe_MRSD_3s_one_year.png) | ![plot](resources/hazard_curves_gmpe_MRSD_5s_one_year.png) | ![plot](resources/hazard_curves_gmpe_MRSD_10s_one_year.png) |

#### GMPE MRSD 5s Hazard Gain Table
*[(top)](#table-of-contents)*

| Dividend | Divisor | One Day Min | One Day Max | One Week Min | One Week Max | One Year Min | One Year Max |
|-----|-----|-----|-----|-----|-----|-----|-----|
| ASK2014, TD | ASK2014, TI | 0.833 at 5.012 g | 1.276 at 0.063 g | 0.821 at 6.310 g | 1.276 at 0.063 g | 0.872 at 7.943 g | 1.276 at 0.063 g |
| ASK2014, ETAS | ASK2014, TD | 3.199 at 3.981 g | 15.607 at 0.100 g | 1.000 at 7.943 g | 4.074 at 0.100 g | 1.000 at 10.000 g | 1.108 at 0.100 g |
| ASK2014+BS13 Directivity, ETAS | ASK2014, TD | 11.345 at 0.010 g | 47.129 at 0.501 g | 1.000 at 7.943 g | 10.492 at 0.501 g | 1.000 at 10.000 g | 1.334 at 0.501 g |
| ASK2014+BS13 Directivity, ETAS | ASK2014, ETAS | 1.064 at 0.010 g | 11.385 at 5.012 g | 1.000 at 7.943 g | 4.987 at 5.012 g | 0.995 at 7.943 g | 1.255 at 0.794 g |

### STNI Hazard Curves
*[(top)](#table-of-contents)*

| Site Location Map |
|-----|
| ![site map](resources/STNI_location_map.png) |

#### CyberShake STNI Hazard Curves
*[(top)](#table-of-contents)*

| Time Span | 3s | 5s | 10s |
|-----|-----|-----|-----|
| One Day | ![plot](resources/hazard_curves_cs_STNI_3s_one_day.png) | ![plot](resources/hazard_curves_cs_STNI_5s_one_day.png) | ![plot](resources/hazard_curves_cs_STNI_10s_one_day.png) |
| One Week | ![plot](resources/hazard_curves_cs_STNI_3s_one_week.png) | ![plot](resources/hazard_curves_cs_STNI_5s_one_week.png) | ![plot](resources/hazard_curves_cs_STNI_10s_one_week.png) |
| One Year | ![plot](resources/hazard_curves_cs_STNI_3s_one_year.png) | ![plot](resources/hazard_curves_cs_STNI_5s_one_year.png) | ![plot](resources/hazard_curves_cs_STNI_10s_one_year.png) |

#### CyberShake STNI 5s Hazard Gain Table
*[(top)](#table-of-contents)*

| Dividend | Divisor | One Day Min | One Day Max | One Week Min | One Week Max | One Year Min | One Year Max |
|-----|-----|-----|-----|-----|-----|-----|-----|
| CyberShake, TD | CyberShake, TI | 0.887 at 1.000 g | 1.266 at 0.126 g | 0.887 at 1.000 g | 1.266 at 0.126 g | 0.887 at 1.000 g | 1.265 at 0.126 g |
| CyberShake, Uniform ETAS | CyberShake, TD | 0.957 at 0.708 g | 16.049 at 0.094 g | 0.957 at 0.708 g | 4.166 at 0.094 g | 0.957 at 0.708 g | 2.440 at 1.189 g |
| CyberShake, ETAS | CyberShake, TD | 0.957 at 0.708 g | 29.767 at 0.133 g | 0.957 at 0.708 g | 6.965 at 0.133 g | 0.957 at 0.708 g | 2.440 at 1.189 g |
| CyberShake, ETAS | CyberShake, Uniform ETAS | 0.530 at 0.316 g | 2.272 at 0.168 g | 0.847 at 0.251 g | 1.911 at 0.168 g | 0.992 at 0.251 g | 1.093 at 0.133 g |

#### GMPE STNI Hazard Curves
*[(top)](#table-of-contents)*

| Time Span | 3s | 5s | 10s |
|-----|-----|-----|-----|
| One Day | ![plot](resources/hazard_curves_gmpe_STNI_3s_one_day.png) | ![plot](resources/hazard_curves_gmpe_STNI_5s_one_day.png) | ![plot](resources/hazard_curves_gmpe_STNI_10s_one_day.png) |
| One Week | ![plot](resources/hazard_curves_gmpe_STNI_3s_one_week.png) | ![plot](resources/hazard_curves_gmpe_STNI_5s_one_week.png) | ![plot](resources/hazard_curves_gmpe_STNI_10s_one_week.png) |
| One Year | ![plot](resources/hazard_curves_gmpe_STNI_3s_one_year.png) | ![plot](resources/hazard_curves_gmpe_STNI_5s_one_year.png) | ![plot](resources/hazard_curves_gmpe_STNI_10s_one_year.png) |

#### GMPE STNI 5s Hazard Gain Table
*[(top)](#table-of-contents)*

| Dividend | Divisor | One Day Min | One Day Max | One Week Min | One Week Max | One Year Min | One Year Max |
|-----|-----|-----|-----|-----|-----|-----|-----|
| ASK2014, TD | ASK2014, TI | 0.897 at 7.943 g | 1.226 at 0.126 g | 0.899 at 10.000 g | 1.226 at 0.126 g | 0.910 at 10.000 g | 1.226 at 0.126 g |
| ASK2014, ETAS | ASK2014, TD | 2.802 at 7.943 g | 14.499 at 0.126 g | 1.276 at 10.000 g | 3.827 at 0.126 g | 1.008 at 10.000 g | 1.097 at 0.126 g |
| ASK2014+BS13 Directivity, ETAS | ASK2014, TD | 8.824 at 0.010 g | 32.267 at 0.501 g | 2.746 at 0.010 g | 7.382 at 0.501 g | 1.063 at 0.010 g | 1.218 at 0.501 g |
| ASK2014+BS13 Directivity, ETAS | ASK2014, ETAS | 1.005 at 0.010 g | 5.378 at 10.000 g | 1.003 at 0.010 g | 3.150 at 1.995 g | 1.000 at 0.010 g | 1.149 at 1.000 g |

### PDU Hazard Curves
*[(top)](#table-of-contents)*

| Site Location Map |
|-----|
| ![site map](resources/PDU_location_map.png) |

#### CyberShake PDU Hazard Curves
*[(top)](#table-of-contents)*

| Time Span | 3s | 5s | 10s |
|-----|-----|-----|-----|
| One Day | ![plot](resources/hazard_curves_cs_PDU_3s_one_day.png) | ![plot](resources/hazard_curves_cs_PDU_5s_one_day.png) | ![plot](resources/hazard_curves_cs_PDU_10s_one_day.png) |
| One Week | ![plot](resources/hazard_curves_cs_PDU_3s_one_week.png) | ![plot](resources/hazard_curves_cs_PDU_5s_one_week.png) | ![plot](resources/hazard_curves_cs_PDU_10s_one_week.png) |
| One Year | ![plot](resources/hazard_curves_cs_PDU_3s_one_year.png) | ![plot](resources/hazard_curves_cs_PDU_5s_one_year.png) | ![plot](resources/hazard_curves_cs_PDU_10s_one_year.png) |

#### CyberShake PDU 5s Hazard Gain Table
*[(top)](#table-of-contents)*

| Dividend | Divisor | One Day Min | One Day Max | One Week Min | One Week Max | One Year Min | One Year Max |
|-----|-----|-----|-----|-----|-----|-----|-----|
| CyberShake, TD | CyberShake, TI | 1.193 at 0.010 g | 1.663 at 0.316 g | 1.193 at 0.010 g | 1.663 at 0.316 g | 1.188 at 0.010 g | 1.663 at 0.316 g |
| CyberShake, Uniform ETAS | CyberShake, TD | 0.788 at 0.376 g | 19.899 at 0.119 g | 0.788 at 0.376 g | 4.845 at 0.119 g | 0.788 at 0.376 g | 1.353 at 0.335 g |
| CyberShake, ETAS | CyberShake, TD | 0.788 at 0.376 g | 38.792 at 0.141 g | 0.788 at 0.376 g | 8.475 at 0.119 g | 0.788 at 0.376 g | 1.353 at 0.335 g |
| CyberShake, ETAS | CyberShake, Uniform ETAS | 0.219 at 0.251 g | 2.217 at 0.168 g | 0.619 at 0.251 g | 1.974 at 0.168 g | 0.966 at 0.224 g | 1.124 at 0.168 g |

#### GMPE PDU Hazard Curves
*[(top)](#table-of-contents)*

| Time Span | 3s | 5s | 10s |
|-----|-----|-----|-----|
| One Day | ![plot](resources/hazard_curves_gmpe_PDU_3s_one_day.png) | ![plot](resources/hazard_curves_gmpe_PDU_5s_one_day.png) | ![plot](resources/hazard_curves_gmpe_PDU_10s_one_day.png) |
| One Week | ![plot](resources/hazard_curves_gmpe_PDU_3s_one_week.png) | ![plot](resources/hazard_curves_gmpe_PDU_5s_one_week.png) | ![plot](resources/hazard_curves_gmpe_PDU_10s_one_week.png) |
| One Year | ![plot](resources/hazard_curves_gmpe_PDU_3s_one_year.png) | ![plot](resources/hazard_curves_gmpe_PDU_5s_one_year.png) | ![plot](resources/hazard_curves_gmpe_PDU_10s_one_year.png) |

#### GMPE PDU 5s Hazard Gain Table
*[(top)](#table-of-contents)*

| Dividend | Divisor | One Day Min | One Day Max | One Week Min | One Week Max | One Year Min | One Year Max |
|-----|-----|-----|-----|-----|-----|-----|-----|
| ASK2014, TD | ASK2014, TI | 1.135 at 0.010 g | 1.550 at 6.310 g | 1.135 at 0.010 g | 1.550 at 7.943 g | 1.131 at 0.010 g | 1.317 at 10.000 g |
| ASK2014, ETAS | ASK2014, TD | 9.297 at 0.010 g | 23.806 at 6.310 g | 2.839 at 0.010 g | 5.613 at 7.943 g | 1.066 at 0.010 g | 1.127 at 10.000 g |
| ASK2014+BS13 Directivity, ETAS | ASK2014, TD | 9.561 at 0.010 g | 342.871 at 6.310 g | 2.892 at 0.010 g | 77.677 at 7.943 g | 1.067 at 0.010 g | 3.416 at 10.000 g |
| ASK2014+BS13 Directivity, ETAS | ASK2014, ETAS | 1.028 at 0.010 g | 22.417 at 10.000 g | 1.019 at 0.010 g | 19.250 at 10.000 g | 1.002 at 0.010 g | 3.030 at 10.000 g |

## Hazard Maps
*[(top)](#table-of-contents)*

### 5s One Day Hazard Maps
*[(top)](#table-of-contents)*

#### One Day 5s Sa (g) with POE=1.0E-4, Maps
*[(top)](#table-of-contents)*

##### One Day 5s Sa (g) with POE=1.0E-4, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_cs_ti.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_cs_td_ti_diff.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_cs_etas_uni_ti_diff.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_cs_etas_ti_diff.png) |
| **CS-TD** | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_cs_td_ti_gain.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_cs_td.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_cs_etas_uni_td_diff.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_cs_etas_td_diff.png) |
| **CS-ETAS (Uniform)** | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_cs_etas_uni_ti_gain.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_cs_etas_uni_td_gain.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_cs_etas_uni.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_cs_etas_uni_diff.png) |
| **CS-ETAS** | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_cs_etas_ti_gain.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_cs_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_cs_etas_uni_gain.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_cs_etas.png) |

##### One Day 5s Sa (g) with POE=1.0E-4, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_gmpe_ti.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_gmpe_td_ti_diff.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_ti_diff.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_gmpe_etas_ti_diff.png) |
| **ASK2014-TD** | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_gmpe_td_ti_gain.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_gmpe_td.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_td_diff.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_gmpe_etas_td_diff.png) |
| **ASK2014-ETAS (Uniform)** | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_ti_gain.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_td_gain.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_gmpe_etas_uni.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_gmpe_etas_ti_gain.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_gmpe_etas.png) |

#### One Day 5s Sa (g) with POE=0.001, Maps
*[(top)](#table-of-contents)*

##### One Day 5s Sa (g) with POE=0.001, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_day_5s_iml_with_poe_0.001_cs_ti.png) | *(N/A)* | *(N/A)* | *(N/A)* |
| **CS-TD** | *(N/A)* | ![Plot](resources/map_one_day_5s_iml_with_poe_0.001_cs_td.png) | *(N/A)* | *(N/A)* |
| **CS-ETAS (Uniform)** | *(N/A)* | *(N/A)* | ![Plot](resources/map_one_day_5s_iml_with_poe_0.001_cs_etas_uni.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_0.001_cs_etas_uni_diff.png) |
| **CS-ETAS** | *(N/A)* | *(N/A)* | ![Plot](resources/map_one_day_5s_iml_with_poe_0.001_cs_etas_uni_gain.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_0.001_cs_etas.png) |

##### One Day 5s Sa (g) with POE=0.001, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_day_5s_iml_with_poe_0.001_gmpe_ti.png) | *(N/A)* | *(N/A)* | *(N/A)* |
| **ASK2014-TD** | *(N/A)* | ![Plot](resources/map_one_day_5s_iml_with_poe_0.001_gmpe_td.png) | *(N/A)* | *(N/A)* |
| **ASK2014-ETAS (Uniform)** | *(N/A)* | *(N/A)* | ![Plot](resources/map_one_day_5s_iml_with_poe_0.001_gmpe_etas_uni.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_0.001_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | *(N/A)* | *(N/A)* | ![Plot](resources/map_one_day_5s_iml_with_poe_0.001_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_0.001_gmpe_etas.png) |

#### One Day 5s Sa (g) with POE=0.01, Maps
*[(top)](#table-of-contents)*

##### One Day 5s Sa (g) with POE=0.01, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_day_5s_iml_with_poe_0.01_cs_ti.png) | *(N/A)* | *(N/A)* | *(N/A)* |
| **CS-TD** | *(N/A)* | ![Plot](resources/map_one_day_5s_iml_with_poe_0.01_cs_td.png) | *(N/A)* | *(N/A)* |
| **CS-ETAS (Uniform)** | *(N/A)* | *(N/A)* | ![Plot](resources/map_one_day_5s_iml_with_poe_0.01_cs_etas_uni.png) | *(N/A)* |
| **CS-ETAS** | *(N/A)* | *(N/A)* | *(N/A)* | ![Plot](resources/map_one_day_5s_iml_with_poe_0.01_cs_etas.png) |

##### One Day 5s Sa (g) with POE=0.01, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_day_5s_iml_with_poe_0.01_gmpe_ti.png) | *(N/A)* | *(N/A)* | *(N/A)* |
| **ASK2014-TD** | *(N/A)* | ![Plot](resources/map_one_day_5s_iml_with_poe_0.01_gmpe_td.png) | *(N/A)* | *(N/A)* |
| **ASK2014-ETAS (Uniform)** | *(N/A)* | *(N/A)* | ![Plot](resources/map_one_day_5s_iml_with_poe_0.01_gmpe_etas_uni.png) | *(N/A)* |
| **ASK2014-ETAS** | *(N/A)* | *(N/A)* | *(N/A)* | ![Plot](resources/map_one_day_5s_iml_with_poe_0.01_gmpe_etas.png) |

#### One Day POE 0.01 (g) 5s SA, Maps
*[(top)](#table-of-contents)*

##### One Day POE 0.01 (g) 5s SA, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_day_5s_poe_0.01g_cs_ti.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_cs_td_ti_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_cs_etas_uni_ti_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_cs_etas_ti_diff.png) |
| **CS-TD** | ![Plot](resources/map_one_day_5s_poe_0.01g_cs_td_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_cs_td.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_cs_etas_uni_td_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_cs_etas_td_diff.png) |
| **CS-ETAS (Uniform)** | ![Plot](resources/map_one_day_5s_poe_0.01g_cs_etas_uni_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_cs_etas_uni_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_cs_etas_uni.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_cs_etas_uni_diff.png) |
| **CS-ETAS** | ![Plot](resources/map_one_day_5s_poe_0.01g_cs_etas_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_cs_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_cs_etas.png) |

##### One Day POE 0.01 (g) 5s SA, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_day_5s_poe_0.01g_gmpe_ti.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_gmpe_td_ti_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_gmpe_etas_uni_ti_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_gmpe_etas_ti_diff.png) |
| **ASK2014-TD** | ![Plot](resources/map_one_day_5s_poe_0.01g_gmpe_td_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_gmpe_td.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_gmpe_etas_uni_td_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_gmpe_etas_td_diff.png) |
| **ASK2014-ETAS (Uniform)** | ![Plot](resources/map_one_day_5s_poe_0.01g_gmpe_etas_uni_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_gmpe_etas_uni_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_gmpe_etas_uni.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | ![Plot](resources/map_one_day_5s_poe_0.01g_gmpe_etas_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_gmpe_etas.png) |

#### One Day POE 0.1 (g) 5s SA, Maps
*[(top)](#table-of-contents)*

##### One Day POE 0.1 (g) 5s SA, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_day_5s_poe_0.1g_cs_ti.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_cs_td_ti_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_cs_etas_uni_ti_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_cs_etas_ti_diff.png) |
| **CS-TD** | ![Plot](resources/map_one_day_5s_poe_0.1g_cs_td_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_cs_td.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_cs_etas_uni_td_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_cs_etas_td_diff.png) |
| **CS-ETAS (Uniform)** | ![Plot](resources/map_one_day_5s_poe_0.1g_cs_etas_uni_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_cs_etas_uni_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_cs_etas_uni.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_cs_etas_uni_diff.png) |
| **CS-ETAS** | ![Plot](resources/map_one_day_5s_poe_0.1g_cs_etas_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_cs_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_cs_etas.png) |

##### One Day POE 0.1 (g) 5s SA, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_day_5s_poe_0.1g_gmpe_ti.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_gmpe_td_ti_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_gmpe_etas_uni_ti_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_gmpe_etas_ti_diff.png) |
| **ASK2014-TD** | ![Plot](resources/map_one_day_5s_poe_0.1g_gmpe_td_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_gmpe_td.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_gmpe_etas_uni_td_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_gmpe_etas_td_diff.png) |
| **ASK2014-ETAS (Uniform)** | ![Plot](resources/map_one_day_5s_poe_0.1g_gmpe_etas_uni_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_gmpe_etas_uni_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_gmpe_etas_uni.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | ![Plot](resources/map_one_day_5s_poe_0.1g_gmpe_etas_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_gmpe_etas.png) |

#### One Day POE 0.2 (g) 5s SA, Maps
*[(top)](#table-of-contents)*

##### One Day POE 0.2 (g) 5s SA, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_day_5s_poe_0.2g_cs_ti.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_cs_td_ti_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_cs_etas_uni_ti_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_cs_etas_ti_diff.png) |
| **CS-TD** | ![Plot](resources/map_one_day_5s_poe_0.2g_cs_td_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_cs_td.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_cs_etas_uni_td_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_cs_etas_td_diff.png) |
| **CS-ETAS (Uniform)** | ![Plot](resources/map_one_day_5s_poe_0.2g_cs_etas_uni_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_cs_etas_uni_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_cs_etas_uni.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_cs_etas_uni_diff.png) |
| **CS-ETAS** | ![Plot](resources/map_one_day_5s_poe_0.2g_cs_etas_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_cs_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_cs_etas.png) |

##### One Day POE 0.2 (g) 5s SA, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_day_5s_poe_0.2g_gmpe_ti.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_gmpe_td_ti_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_gmpe_etas_uni_ti_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_gmpe_etas_ti_diff.png) |
| **ASK2014-TD** | ![Plot](resources/map_one_day_5s_poe_0.2g_gmpe_td_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_gmpe_td.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_gmpe_etas_uni_td_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_gmpe_etas_td_diff.png) |
| **ASK2014-ETAS (Uniform)** | ![Plot](resources/map_one_day_5s_poe_0.2g_gmpe_etas_uni_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_gmpe_etas_uni_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_gmpe_etas_uni.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | ![Plot](resources/map_one_day_5s_poe_0.2g_gmpe_etas_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_gmpe_etas.png) |

#### One Day POE 0.5 (g) 5s SA, Maps
*[(top)](#table-of-contents)*

##### One Day POE 0.5 (g) 5s SA, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_day_5s_poe_0.5g_cs_ti.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_cs_td_ti_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_cs_etas_uni_ti_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_cs_etas_ti_diff.png) |
| **CS-TD** | ![Plot](resources/map_one_day_5s_poe_0.5g_cs_td_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_cs_td.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_cs_etas_uni_td_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_cs_etas_td_diff.png) |
| **CS-ETAS (Uniform)** | ![Plot](resources/map_one_day_5s_poe_0.5g_cs_etas_uni_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_cs_etas_uni_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_cs_etas_uni.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_cs_etas_uni_diff.png) |
| **CS-ETAS** | ![Plot](resources/map_one_day_5s_poe_0.5g_cs_etas_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_cs_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_cs_etas.png) |

##### One Day POE 0.5 (g) 5s SA, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_day_5s_poe_0.5g_gmpe_ti.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_gmpe_td_ti_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_gmpe_etas_uni_ti_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_gmpe_etas_ti_diff.png) |
| **ASK2014-TD** | ![Plot](resources/map_one_day_5s_poe_0.5g_gmpe_td_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_gmpe_td.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_gmpe_etas_uni_td_diff.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_gmpe_etas_td_diff.png) |
| **ASK2014-ETAS (Uniform)** | ![Plot](resources/map_one_day_5s_poe_0.5g_gmpe_etas_uni_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_gmpe_etas_uni_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_gmpe_etas_uni.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | ![Plot](resources/map_one_day_5s_poe_0.5g_gmpe_etas_ti_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_gmpe_etas.png) |

### 5s One Day EATS Gains Table
*[(top)](#table-of-contents)*

| Map Value | CyberShake ETAS/TD Gain | CyberShake ETAS/Uniform Gain | GMPE ETAS/TD Gain | GMPE ETAS/Uniform Gain |
|-----|-----|-----|-----|-----|
| **One Day 5s Sa (g) with POE=1.0E-4** | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_cs_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_cs_etas_uni_gain.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_gain.png) |
| **One Day 5s Sa (g) with POE=0.001** | *(N/A)* | ![Plot](resources/map_one_day_5s_iml_with_poe_0.001_cs_etas_uni_gain.png) | *(N/A)* | ![Plot](resources/map_one_day_5s_iml_with_poe_0.001_gmpe_etas_uni_gain.png) |
| **One Day 5s Sa (g) with POE=0.01** | *(N/A)* | *(N/A)* | *(N/A)* | *(N/A)* |
| **One Day POE 0.01 (g) 5s SA** | ![Plot](resources/map_one_day_5s_poe_0.01g_cs_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.01g_gmpe_etas_uni_gain.png) |
| **One Day POE 0.1 (g) 5s SA** | ![Plot](resources/map_one_day_5s_poe_0.1g_cs_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.1g_gmpe_etas_uni_gain.png) |
| **One Day POE 0.2 (g) 5s SA** | ![Plot](resources/map_one_day_5s_poe_0.2g_cs_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.2g_gmpe_etas_uni_gain.png) |
| **One Day POE 0.5 (g) 5s SA** | ![Plot](resources/map_one_day_5s_poe_0.5g_cs_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_day_5s_poe_0.5g_gmpe_etas_uni_gain.png) |

### 5s One Week Hazard Maps
*[(top)](#table-of-contents)*

#### One Week 5s Sa (g) with POE=1.0E-4, Maps
*[(top)](#table-of-contents)*

##### One Week 5s Sa (g) with POE=1.0E-4, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_cs_ti.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_cs_td_ti_diff.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_cs_etas_uni_ti_diff.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_cs_etas_ti_diff.png) |
| **CS-TD** | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_cs_td_ti_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_cs_td.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_cs_etas_uni_td_diff.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_cs_etas_td_diff.png) |
| **CS-ETAS (Uniform)** | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_cs_etas_uni_ti_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_cs_etas_uni_td_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_cs_etas_uni.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_cs_etas_uni_diff.png) |
| **CS-ETAS** | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_cs_etas_ti_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_cs_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_cs_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_cs_etas.png) |

##### One Week 5s Sa (g) with POE=1.0E-4, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_gmpe_ti.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_gmpe_td_ti_diff.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_ti_diff.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_gmpe_etas_ti_diff.png) |
| **ASK2014-TD** | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_gmpe_td_ti_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_gmpe_td.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_td_diff.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_gmpe_etas_td_diff.png) |
| **ASK2014-ETAS (Uniform)** | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_ti_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_td_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_gmpe_etas_uni.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_gmpe_etas_ti_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_gmpe_etas.png) |

#### One Week 5s Sa (g) with POE=0.001, Maps
*[(top)](#table-of-contents)*

##### One Week 5s Sa (g) with POE=0.001, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_cs_ti.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_cs_td_ti_diff.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_cs_etas_uni_ti_diff.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_cs_etas_ti_diff.png) |
| **CS-TD** | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_cs_td_ti_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_cs_td.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_cs_etas_uni_td_diff.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_cs_etas_td_diff.png) |
| **CS-ETAS (Uniform)** | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_cs_etas_uni_ti_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_cs_etas_uni_td_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_cs_etas_uni.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_cs_etas_uni_diff.png) |
| **CS-ETAS** | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_cs_etas_ti_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_cs_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_cs_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_cs_etas.png) |

##### One Week 5s Sa (g) with POE=0.001, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_gmpe_ti.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_gmpe_td_ti_diff.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_gmpe_etas_uni_ti_diff.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_gmpe_etas_ti_diff.png) |
| **ASK2014-TD** | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_gmpe_td_ti_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_gmpe_td.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_gmpe_etas_uni_td_diff.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_gmpe_etas_td_diff.png) |
| **ASK2014-ETAS (Uniform)** | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_gmpe_etas_uni_ti_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_gmpe_etas_uni_td_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_gmpe_etas_uni.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_gmpe_etas_ti_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_gmpe_etas.png) |

#### One Week 5s Sa (g) with POE=0.01, Maps
*[(top)](#table-of-contents)*

##### One Week 5s Sa (g) with POE=0.01, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_week_5s_iml_with_poe_0.01_cs_ti.png) | *(N/A)* | *(N/A)* | *(N/A)* |
| **CS-TD** | *(N/A)* | ![Plot](resources/map_one_week_5s_iml_with_poe_0.01_cs_td.png) | *(N/A)* | *(N/A)* |
| **CS-ETAS (Uniform)** | *(N/A)* | *(N/A)* | ![Plot](resources/map_one_week_5s_iml_with_poe_0.01_cs_etas_uni.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.01_cs_etas_uni_diff.png) |
| **CS-ETAS** | *(N/A)* | *(N/A)* | ![Plot](resources/map_one_week_5s_iml_with_poe_0.01_cs_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.01_cs_etas.png) |

##### One Week 5s Sa (g) with POE=0.01, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_week_5s_iml_with_poe_0.01_gmpe_ti.png) | *(N/A)* | *(N/A)* | *(N/A)* |
| **ASK2014-TD** | *(N/A)* | ![Plot](resources/map_one_week_5s_iml_with_poe_0.01_gmpe_td.png) | *(N/A)* | *(N/A)* |
| **ASK2014-ETAS (Uniform)** | *(N/A)* | *(N/A)* | ![Plot](resources/map_one_week_5s_iml_with_poe_0.01_gmpe_etas_uni.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.01_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | *(N/A)* | *(N/A)* | ![Plot](resources/map_one_week_5s_iml_with_poe_0.01_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.01_gmpe_etas.png) |

#### One Week POE 0.01 (g) 5s SA, Maps
*[(top)](#table-of-contents)*

##### One Week POE 0.01 (g) 5s SA, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_week_5s_poe_0.01g_cs_ti.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_cs_td_ti_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_cs_etas_uni_ti_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_cs_etas_ti_diff.png) |
| **CS-TD** | ![Plot](resources/map_one_week_5s_poe_0.01g_cs_td_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_cs_td.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_cs_etas_uni_td_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_cs_etas_td_diff.png) |
| **CS-ETAS (Uniform)** | ![Plot](resources/map_one_week_5s_poe_0.01g_cs_etas_uni_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_cs_etas_uni_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_cs_etas_uni.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_cs_etas_uni_diff.png) |
| **CS-ETAS** | ![Plot](resources/map_one_week_5s_poe_0.01g_cs_etas_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_cs_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_cs_etas.png) |

##### One Week POE 0.01 (g) 5s SA, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_week_5s_poe_0.01g_gmpe_ti.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_gmpe_td_ti_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_gmpe_etas_uni_ti_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_gmpe_etas_ti_diff.png) |
| **ASK2014-TD** | ![Plot](resources/map_one_week_5s_poe_0.01g_gmpe_td_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_gmpe_td.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_gmpe_etas_uni_td_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_gmpe_etas_td_diff.png) |
| **ASK2014-ETAS (Uniform)** | ![Plot](resources/map_one_week_5s_poe_0.01g_gmpe_etas_uni_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_gmpe_etas_uni_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_gmpe_etas_uni.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | ![Plot](resources/map_one_week_5s_poe_0.01g_gmpe_etas_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_gmpe_etas.png) |

#### One Week POE 0.1 (g) 5s SA, Maps
*[(top)](#table-of-contents)*

##### One Week POE 0.1 (g) 5s SA, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_week_5s_poe_0.1g_cs_ti.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_cs_td_ti_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_cs_etas_uni_ti_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_cs_etas_ti_diff.png) |
| **CS-TD** | ![Plot](resources/map_one_week_5s_poe_0.1g_cs_td_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_cs_td.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_cs_etas_uni_td_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_cs_etas_td_diff.png) |
| **CS-ETAS (Uniform)** | ![Plot](resources/map_one_week_5s_poe_0.1g_cs_etas_uni_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_cs_etas_uni_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_cs_etas_uni.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_cs_etas_uni_diff.png) |
| **CS-ETAS** | ![Plot](resources/map_one_week_5s_poe_0.1g_cs_etas_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_cs_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_cs_etas.png) |

##### One Week POE 0.1 (g) 5s SA, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_week_5s_poe_0.1g_gmpe_ti.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_gmpe_td_ti_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_gmpe_etas_uni_ti_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_gmpe_etas_ti_diff.png) |
| **ASK2014-TD** | ![Plot](resources/map_one_week_5s_poe_0.1g_gmpe_td_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_gmpe_td.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_gmpe_etas_uni_td_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_gmpe_etas_td_diff.png) |
| **ASK2014-ETAS (Uniform)** | ![Plot](resources/map_one_week_5s_poe_0.1g_gmpe_etas_uni_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_gmpe_etas_uni_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_gmpe_etas_uni.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | ![Plot](resources/map_one_week_5s_poe_0.1g_gmpe_etas_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_gmpe_etas.png) |

#### One Week POE 0.2 (g) 5s SA, Maps
*[(top)](#table-of-contents)*

##### One Week POE 0.2 (g) 5s SA, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_week_5s_poe_0.2g_cs_ti.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_cs_td_ti_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_cs_etas_uni_ti_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_cs_etas_ti_diff.png) |
| **CS-TD** | ![Plot](resources/map_one_week_5s_poe_0.2g_cs_td_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_cs_td.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_cs_etas_uni_td_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_cs_etas_td_diff.png) |
| **CS-ETAS (Uniform)** | ![Plot](resources/map_one_week_5s_poe_0.2g_cs_etas_uni_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_cs_etas_uni_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_cs_etas_uni.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_cs_etas_uni_diff.png) |
| **CS-ETAS** | ![Plot](resources/map_one_week_5s_poe_0.2g_cs_etas_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_cs_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_cs_etas.png) |

##### One Week POE 0.2 (g) 5s SA, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_week_5s_poe_0.2g_gmpe_ti.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_gmpe_td_ti_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_gmpe_etas_uni_ti_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_gmpe_etas_ti_diff.png) |
| **ASK2014-TD** | ![Plot](resources/map_one_week_5s_poe_0.2g_gmpe_td_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_gmpe_td.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_gmpe_etas_uni_td_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_gmpe_etas_td_diff.png) |
| **ASK2014-ETAS (Uniform)** | ![Plot](resources/map_one_week_5s_poe_0.2g_gmpe_etas_uni_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_gmpe_etas_uni_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_gmpe_etas_uni.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | ![Plot](resources/map_one_week_5s_poe_0.2g_gmpe_etas_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_gmpe_etas.png) |

#### One Week POE 0.5 (g) 5s SA, Maps
*[(top)](#table-of-contents)*

##### One Week POE 0.5 (g) 5s SA, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_week_5s_poe_0.5g_cs_ti.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_cs_td_ti_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_cs_etas_uni_ti_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_cs_etas_ti_diff.png) |
| **CS-TD** | ![Plot](resources/map_one_week_5s_poe_0.5g_cs_td_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_cs_td.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_cs_etas_uni_td_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_cs_etas_td_diff.png) |
| **CS-ETAS (Uniform)** | ![Plot](resources/map_one_week_5s_poe_0.5g_cs_etas_uni_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_cs_etas_uni_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_cs_etas_uni.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_cs_etas_uni_diff.png) |
| **CS-ETAS** | ![Plot](resources/map_one_week_5s_poe_0.5g_cs_etas_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_cs_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_cs_etas.png) |

##### One Week POE 0.5 (g) 5s SA, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_week_5s_poe_0.5g_gmpe_ti.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_gmpe_td_ti_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_gmpe_etas_uni_ti_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_gmpe_etas_ti_diff.png) |
| **ASK2014-TD** | ![Plot](resources/map_one_week_5s_poe_0.5g_gmpe_td_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_gmpe_td.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_gmpe_etas_uni_td_diff.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_gmpe_etas_td_diff.png) |
| **ASK2014-ETAS (Uniform)** | ![Plot](resources/map_one_week_5s_poe_0.5g_gmpe_etas_uni_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_gmpe_etas_uni_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_gmpe_etas_uni.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | ![Plot](resources/map_one_week_5s_poe_0.5g_gmpe_etas_ti_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_gmpe_etas.png) |

### 5s One Week EATS Gains Table
*[(top)](#table-of-contents)*

| Map Value | CyberShake ETAS/TD Gain | CyberShake ETAS/Uniform Gain | GMPE ETAS/TD Gain | GMPE ETAS/Uniform Gain |
|-----|-----|-----|-----|-----|
| **One Week 5s Sa (g) with POE=1.0E-4** | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_cs_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_cs_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_gain.png) |
| **One Week 5s Sa (g) with POE=0.001** | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_cs_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_cs_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_iml_with_poe_0.001_gmpe_etas_uni_gain.png) |
| **One Week 5s Sa (g) with POE=0.01** | *(N/A)* | ![Plot](resources/map_one_week_5s_iml_with_poe_0.01_cs_etas_uni_gain.png) | *(N/A)* | ![Plot](resources/map_one_week_5s_iml_with_poe_0.01_gmpe_etas_uni_gain.png) |
| **One Week POE 0.01 (g) 5s SA** | ![Plot](resources/map_one_week_5s_poe_0.01g_cs_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.01g_gmpe_etas_uni_gain.png) |
| **One Week POE 0.1 (g) 5s SA** | ![Plot](resources/map_one_week_5s_poe_0.1g_cs_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.1g_gmpe_etas_uni_gain.png) |
| **One Week POE 0.2 (g) 5s SA** | ![Plot](resources/map_one_week_5s_poe_0.2g_cs_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.2g_gmpe_etas_uni_gain.png) |
| **One Week POE 0.5 (g) 5s SA** | ![Plot](resources/map_one_week_5s_poe_0.5g_cs_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_week_5s_poe_0.5g_gmpe_etas_uni_gain.png) |

### 5s One Year Hazard Maps
*[(top)](#table-of-contents)*

#### One Year 5s Sa (g) with POE=1.0E-4, Maps
*[(top)](#table-of-contents)*

##### One Year 5s Sa (g) with POE=1.0E-4, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_cs_ti.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_cs_td_ti_diff.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_cs_etas_uni_ti_diff.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_cs_etas_ti_diff.png) |
| **CS-TD** | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_cs_td_ti_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_cs_td.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_cs_etas_uni_td_diff.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_cs_etas_td_diff.png) |
| **CS-ETAS (Uniform)** | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_cs_etas_uni_ti_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_cs_etas_uni_td_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_cs_etas_uni.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_cs_etas_uni_diff.png) |
| **CS-ETAS** | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_cs_etas_ti_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_cs_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_cs_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_cs_etas.png) |

##### One Year 5s Sa (g) with POE=1.0E-4, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_gmpe_ti.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_gmpe_td_ti_diff.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_ti_diff.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_gmpe_etas_ti_diff.png) |
| **ASK2014-TD** | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_gmpe_td_ti_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_gmpe_td.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_td_diff.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_gmpe_etas_td_diff.png) |
| **ASK2014-ETAS (Uniform)** | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_ti_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_td_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_gmpe_etas_uni.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_gmpe_etas_ti_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_gmpe_etas.png) |

#### One Year 5s Sa (g) with POE=0.001, Maps
*[(top)](#table-of-contents)*

##### One Year 5s Sa (g) with POE=0.001, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_cs_ti.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_cs_td_ti_diff.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_cs_etas_uni_ti_diff.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_cs_etas_ti_diff.png) |
| **CS-TD** | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_cs_td_ti_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_cs_td.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_cs_etas_uni_td_diff.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_cs_etas_td_diff.png) |
| **CS-ETAS (Uniform)** | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_cs_etas_uni_ti_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_cs_etas_uni_td_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_cs_etas_uni.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_cs_etas_uni_diff.png) |
| **CS-ETAS** | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_cs_etas_ti_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_cs_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_cs_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_cs_etas.png) |

##### One Year 5s Sa (g) with POE=0.001, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_gmpe_ti.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_gmpe_td_ti_diff.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_gmpe_etas_uni_ti_diff.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_gmpe_etas_ti_diff.png) |
| **ASK2014-TD** | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_gmpe_td_ti_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_gmpe_td.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_gmpe_etas_uni_td_diff.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_gmpe_etas_td_diff.png) |
| **ASK2014-ETAS (Uniform)** | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_gmpe_etas_uni_ti_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_gmpe_etas_uni_td_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_gmpe_etas_uni.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_gmpe_etas_ti_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_gmpe_etas.png) |

#### One Year 5s Sa (g) with POE=0.01, Maps
*[(top)](#table-of-contents)*

##### One Year 5s Sa (g) with POE=0.01, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_cs_ti.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_cs_td_ti_diff.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_cs_etas_uni_ti_diff.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_cs_etas_ti_diff.png) |
| **CS-TD** | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_cs_td_ti_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_cs_td.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_cs_etas_uni_td_diff.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_cs_etas_td_diff.png) |
| **CS-ETAS (Uniform)** | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_cs_etas_uni_ti_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_cs_etas_uni_td_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_cs_etas_uni.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_cs_etas_uni_diff.png) |
| **CS-ETAS** | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_cs_etas_ti_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_cs_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_cs_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_cs_etas.png) |

##### One Year 5s Sa (g) with POE=0.01, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_gmpe_ti.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_gmpe_td_ti_diff.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_gmpe_etas_uni_ti_diff.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_gmpe_etas_ti_diff.png) |
| **ASK2014-TD** | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_gmpe_td_ti_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_gmpe_td.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_gmpe_etas_uni_td_diff.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_gmpe_etas_td_diff.png) |
| **ASK2014-ETAS (Uniform)** | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_gmpe_etas_uni_ti_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_gmpe_etas_uni_td_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_gmpe_etas_uni.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_gmpe_etas_ti_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_gmpe_etas.png) |

#### One Year POE 0.01 (g) 5s SA, Maps
*[(top)](#table-of-contents)*

##### One Year POE 0.01 (g) 5s SA, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_year_5s_poe_0.01g_cs_ti.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_cs_td_ti_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_cs_etas_uni_ti_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_cs_etas_ti_diff.png) |
| **CS-TD** | ![Plot](resources/map_one_year_5s_poe_0.01g_cs_td_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_cs_td.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_cs_etas_uni_td_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_cs_etas_td_diff.png) |
| **CS-ETAS (Uniform)** | ![Plot](resources/map_one_year_5s_poe_0.01g_cs_etas_uni_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_cs_etas_uni_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_cs_etas_uni.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_cs_etas_uni_diff.png) |
| **CS-ETAS** | ![Plot](resources/map_one_year_5s_poe_0.01g_cs_etas_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_cs_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_cs_etas.png) |

##### One Year POE 0.01 (g) 5s SA, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_year_5s_poe_0.01g_gmpe_ti.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_gmpe_td_ti_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_gmpe_etas_uni_ti_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_gmpe_etas_ti_diff.png) |
| **ASK2014-TD** | ![Plot](resources/map_one_year_5s_poe_0.01g_gmpe_td_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_gmpe_td.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_gmpe_etas_uni_td_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_gmpe_etas_td_diff.png) |
| **ASK2014-ETAS (Uniform)** | ![Plot](resources/map_one_year_5s_poe_0.01g_gmpe_etas_uni_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_gmpe_etas_uni_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_gmpe_etas_uni.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | ![Plot](resources/map_one_year_5s_poe_0.01g_gmpe_etas_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_gmpe_etas.png) |

#### One Year POE 0.1 (g) 5s SA, Maps
*[(top)](#table-of-contents)*

##### One Year POE 0.1 (g) 5s SA, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_year_5s_poe_0.1g_cs_ti.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_cs_td_ti_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_cs_etas_uni_ti_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_cs_etas_ti_diff.png) |
| **CS-TD** | ![Plot](resources/map_one_year_5s_poe_0.1g_cs_td_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_cs_td.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_cs_etas_uni_td_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_cs_etas_td_diff.png) |
| **CS-ETAS (Uniform)** | ![Plot](resources/map_one_year_5s_poe_0.1g_cs_etas_uni_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_cs_etas_uni_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_cs_etas_uni.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_cs_etas_uni_diff.png) |
| **CS-ETAS** | ![Plot](resources/map_one_year_5s_poe_0.1g_cs_etas_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_cs_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_cs_etas.png) |

##### One Year POE 0.1 (g) 5s SA, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_year_5s_poe_0.1g_gmpe_ti.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_gmpe_td_ti_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_gmpe_etas_uni_ti_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_gmpe_etas_ti_diff.png) |
| **ASK2014-TD** | ![Plot](resources/map_one_year_5s_poe_0.1g_gmpe_td_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_gmpe_td.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_gmpe_etas_uni_td_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_gmpe_etas_td_diff.png) |
| **ASK2014-ETAS (Uniform)** | ![Plot](resources/map_one_year_5s_poe_0.1g_gmpe_etas_uni_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_gmpe_etas_uni_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_gmpe_etas_uni.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | ![Plot](resources/map_one_year_5s_poe_0.1g_gmpe_etas_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_gmpe_etas.png) |

#### One Year POE 0.2 (g) 5s SA, Maps
*[(top)](#table-of-contents)*

##### One Year POE 0.2 (g) 5s SA, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_year_5s_poe_0.2g_cs_ti.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_cs_td_ti_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_cs_etas_uni_ti_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_cs_etas_ti_diff.png) |
| **CS-TD** | ![Plot](resources/map_one_year_5s_poe_0.2g_cs_td_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_cs_td.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_cs_etas_uni_td_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_cs_etas_td_diff.png) |
| **CS-ETAS (Uniform)** | ![Plot](resources/map_one_year_5s_poe_0.2g_cs_etas_uni_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_cs_etas_uni_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_cs_etas_uni.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_cs_etas_uni_diff.png) |
| **CS-ETAS** | ![Plot](resources/map_one_year_5s_poe_0.2g_cs_etas_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_cs_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_cs_etas.png) |

##### One Year POE 0.2 (g) 5s SA, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_year_5s_poe_0.2g_gmpe_ti.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_gmpe_td_ti_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_gmpe_etas_uni_ti_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_gmpe_etas_ti_diff.png) |
| **ASK2014-TD** | ![Plot](resources/map_one_year_5s_poe_0.2g_gmpe_td_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_gmpe_td.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_gmpe_etas_uni_td_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_gmpe_etas_td_diff.png) |
| **ASK2014-ETAS (Uniform)** | ![Plot](resources/map_one_year_5s_poe_0.2g_gmpe_etas_uni_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_gmpe_etas_uni_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_gmpe_etas_uni.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | ![Plot](resources/map_one_year_5s_poe_0.2g_gmpe_etas_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_gmpe_etas.png) |

#### One Year POE 0.5 (g) 5s SA, Maps
*[(top)](#table-of-contents)*

##### One Year POE 0.5 (g) 5s SA, CyberShake Maps
*[(top)](#table-of-contents)*

|  | CS-TI | CS-TD | CS-ETAS-Uniform | CS-ETAS |
|-----|-----|-----|-----|-----|
| **CS-TI** | ![Plot](resources/map_one_year_5s_poe_0.5g_cs_ti.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_cs_td_ti_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_cs_etas_uni_ti_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_cs_etas_ti_diff.png) |
| **CS-TD** | ![Plot](resources/map_one_year_5s_poe_0.5g_cs_td_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_cs_td.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_cs_etas_uni_td_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_cs_etas_td_diff.png) |
| **CS-ETAS (Uniform)** | ![Plot](resources/map_one_year_5s_poe_0.5g_cs_etas_uni_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_cs_etas_uni_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_cs_etas_uni.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_cs_etas_uni_diff.png) |
| **CS-ETAS** | ![Plot](resources/map_one_year_5s_poe_0.5g_cs_etas_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_cs_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_cs_etas.png) |

##### One Year POE 0.5 (g) 5s SA, GMPE Maps
*[(top)](#table-of-contents)*

|  | ASK2014-TI | ASK2014-TD | ASK2014-ETAS-Uniform | ASK2014-ETAS |
|-----|-----|-----|-----|-----|
| **ASK2014-TI** | ![Plot](resources/map_one_year_5s_poe_0.5g_gmpe_ti.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_gmpe_td_ti_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_gmpe_etas_uni_ti_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_gmpe_etas_ti_diff.png) |
| **ASK2014-TD** | ![Plot](resources/map_one_year_5s_poe_0.5g_gmpe_td_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_gmpe_td.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_gmpe_etas_uni_td_diff.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_gmpe_etas_td_diff.png) |
| **ASK2014-ETAS (Uniform)** | ![Plot](resources/map_one_year_5s_poe_0.5g_gmpe_etas_uni_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_gmpe_etas_uni_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_gmpe_etas_uni.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_gmpe_etas_uni_diff.png) |
| **ASK2014-ETAS** | ![Plot](resources/map_one_year_5s_poe_0.5g_gmpe_etas_ti_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_gmpe_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_gmpe_etas.png) |

### 5s One Year EATS Gains Table
*[(top)](#table-of-contents)*

| Map Value | CyberShake ETAS/TD Gain | CyberShake ETAS/Uniform Gain | GMPE ETAS/TD Gain | GMPE ETAS/Uniform Gain |
|-----|-----|-----|-----|-----|
| **One Year 5s Sa (g) with POE=1.0E-4** | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_cs_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_cs_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_1.0E-4_gmpe_etas_uni_gain.png) |
| **One Year 5s Sa (g) with POE=0.001** | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_cs_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_cs_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.001_gmpe_etas_uni_gain.png) |
| **One Year 5s Sa (g) with POE=0.01** | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_cs_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_cs_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_iml_with_poe_0.01_gmpe_etas_uni_gain.png) |
| **One Year POE 0.01 (g) 5s SA** | ![Plot](resources/map_one_year_5s_poe_0.01g_cs_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.01g_gmpe_etas_uni_gain.png) |
| **One Year POE 0.1 (g) 5s SA** | ![Plot](resources/map_one_year_5s_poe_0.1g_cs_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.1g_gmpe_etas_uni_gain.png) |
| **One Year POE 0.2 (g) 5s SA** | ![Plot](resources/map_one_year_5s_poe_0.2g_cs_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.2g_gmpe_etas_uni_gain.png) |
| **One Year POE 0.5 (g) 5s SA** | ![Plot](resources/map_one_year_5s_poe_0.5g_cs_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_cs_etas_uni_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_gmpe_etas_td_gain.png) | ![Plot](resources/map_one_year_5s_poe_0.5g_gmpe_etas_uni_gain.png) |

