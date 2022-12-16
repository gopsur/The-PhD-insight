$$\color{olive}{\ • Observations \\ }$$
           $\color{blue}{In \\ laptop}$ : '/Users/gopika.s/Documents/ToD/data2/observation/observation/obs_updated/'


    1. COBE SST: 
          > cobesst_ref_1891_1950_tr_new.nc , cobesst_ref_1920_1970_tr_new.nc
          > Download : https://psl.noaa.gov/data/gridded/data.cobe.html
          > Period : Original Period used in the paper : 1891-2021
          > period used in the paper: 1891:2020
          > Original grid : 1° latitude by 1° longitude, regridded to 2° latitude by 2° longitude
          > Reference : Folland CK, Parker DE (1995) Correction of instrumental biases in historical sea surface temperature data. Q J R Meteorol Soc 121:319–367. https://doi.org/10.1002/qj.49712152206
    2. ERSST v5
          > ersst_v5_ref_1891_1950_tr_new.nc , ersst_v5_ref_1920_1970_tr_new.nc
          > Download : https://psl.noaa.gov/data/gridded/data.noaa.ersst.v5.html
          > Period : Original Period used in the paper : 1891-2022
          > period used in the paper: 1891:2020
          > Original grid : 2° latitude by 2° longitude, regridded to 2° latitude by 2° longitude
          > Reference : Huang B, Thorne Peter W et al (2017) Extended reconstructed sea surface temperature version 5 (ERSSTv5), upgrades, valida- tions, and intercomparisons. J Climate. https://doi.org/10.1175/ JCLI-D-16-0836.1
    3. HadSST.3.1.1.0
          > hadisst_ref_1891_1950_tr_new.nc , hadisst_ref_1920_1970_tr_new.nc
          > Download : https://www.metoffice.gov.uk/hadobs/hadsst3/data/download.html
          > Period : Original Period used in the paper : 1891-2022
          > period used in the paper: 1891:2020
          > Original grid : 5° latitude by 5° longitude, regridded to 2° latitude by 2° longitude
          > Reference : Rayner NA, Parker DE, Horton EB, Folland CK, Alexander LV, Rowell DP, Kent EC, Kaplan A (2003) Global analyses of sea surface temperature, sea ice, and night marine air temperature since the late nineteenth century. J Geophys Res 108(D14):4407. https:// doi.org/10.1029/2002JD002670
    4. Kaplan SST V2
          > kaplan_ref_1891_1950_tr_new.nc , kaplan_ref_1920_1970_tr_new.nc
          > Download: https://www.psl.noaa.gov/data/gridded/data.kaplan_sst.html
          > Period : Original Period used in the paper : 1891-2022
          > period used in the paper: 1891:2020
          > Original grid : 5° latitude by 5° longitude, regridded to 2° latitude by 2° longitude
          > Reference : Kaplan, A., M. Cane, Y. Kushnir, A. Clement, M. Blumenthal, and B. Rajagopalan, Analyses of global sea surface temperature 1856-1991, Journal of Geophysical Research, 103, 18,567-18,589, 1998
          
$$\color{green}{\ • Models \\ }$$
           $\color{blue}{In \\ laptop}$ : '/Users/islab/Documents/islab/gopz/data2/cmip_data/'


    1. CMIP5 : cmip5_ref1890_1950_tr_34m.nc, cmip5_ref1920_1970_tr.nc
          > 34 models used, Ref period 1920-1970 36 are there convert to 34 inside the script
          > Regridded to 2° latitude by 2° longitude
          > period used in the paper: 1891:2020 and 1891:2100
            1.	bcc-csm1-1
            2.	bcc-csm1-1-m
            3.	CanESM2
            4.	CMCC-CESM
            5.	CMCC-CMS
            6.	CNRM-CM5
            7.	ACCESS1-3
            8.	CSIRO-Mk3-6-0
            9.	FIO-ESM
            10.	IPSL-CM5A-LR
            11.	IPSL-CM5A-MR
            12.	IPSL-CM5B-LR
            13.	FGOALS-s2
            14.	MIROC5
            15.	MIROC-ESM
            16.	MIROC-ESM-CHEM
            17.	HadGEM2-CC
            18.	MPI-ESM-LR
            19.	MPI-ESM-MR
            20.	MRI-CGCM3
            21.	MRI-ESM1
            22.	GISS-E2-H
            23.	GISS-E2-H-CC
            24.	GISS-E2-R
            25.	GISS-E2-R-CC
            26.	CCSM4
            27.	NorESM1-M
            28.	NorESM1-ME
            29.	HadGEM2-AO
            30.	GFDL-CM3
            31.	GFDL-ESM2G
            32.	GFDL-ESM2M
            33.	CESM1-BGC
            34.	CESM1-CAM5

          
    2. CMIP6 : cmip6_ref1890_1950_tr_35m.nc, cmip6_ref1920_1970_tr.nc
          > > 35 models used, Ref period 1920-1970 37 are there convert to 35 inside the script
          > Regridded to 2° latitude by 2° longitude
          > period used in the paper: 1891:2020 and 1891:2100
            1.	CAS.FGOALS-g3
            2.	CAS.FGOALS-f3-L
            3.	NUIST.NESM3
            4.	MRI.MRI-ESM2-0
            5.	MIROC.MIROC-ES2L
            6.	MIROC.MIROC6
            7.	UA.MCM-UA-1-0
            8.	CCCma.CanESM5
            9.	BCC.BCC-CSM2-MR
            10.	THU.CIESM
            11.	NCAR.CESM2-WACCM
            12.	NIMS-KMA.KACE-1-0-G
            13.	INM.INM-CM4-8
            14.	INM.INM-CM5-0
            15.	AWI.AWI-CM-1-1-MR
            16.	MPI-M.MPI-ESM1-2-LR
            17.	AS-RCEC.TaiESM1
            18.	CMCC.CMCC-CM2-SR5
            19.	CCCR-IITM.IITM-ESM
            20.	CNRM-CERFACS.CNRM-CM6-1
            21.	CNRM-CERFACS.CNRM-ESM2-1
            22.	IPSL.IPSL-CM6A-LR
            23.	CNRM-CERFACS.CNRM-CM6-1-HR
            24.	NCC.NorESM2-LM
            25.	NCC.NorESM2-MM
            26.	EC-Earth-Consortium.EC-Earth3
            27.	EC-Earth-Consortium.EC-Earth3-Veg
            28.	CSIRO-ARCCSS.ACCESS-CM2
            29.	CSIRO.ACCESS-ESM1-5
            30.	NOAA-GFDL.GFDL-ESM4
            31.	MOHC.UKESM1-0-LL
            32.	MOHC.HadGEM3-GC31-MM
            33.	MOHC.HadGEM3-GC31-LL
            34.	FIO-QLNM.FIO-ESM-2-0
            35.	MPI-M.MPI-ESM1-2-HR

 
