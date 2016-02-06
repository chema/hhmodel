# hhmodel
A household wealth/income model that uses best available data sources like US Census Bureau PUMA.

Data Sources
============

The ACS Public Use Microdata Sample files (PUMS) are a sample of the actual responses to the American Community Survey and include most population and housing characteristics. These files provide users with the flexibility to prepare customized tabulations and can be used for detailed research and analysis. Files have been edited to protect the confidentiality of all individuals and of all individual households. The smallest geographic unit that is identified within the PUMS is the Public Use Microdata Area (PUMA).

For complete PUMS documentation, visit the ACS PUMS documentation page.

All files below are provided in comma separated value (CSV) format. The 2010-2014 ACS 5-year PUMS are also available in SAS format.

[Source for 2010-2014 ACS 5-year Public Use Microdata Samples (PUMS)](http://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?pid=ACS_pums_csv_2010_2014&prodType=document)

Columns:

RT,SERIALNO,SPORDER,PUMA00,PUMA10,ST,ADJINC,PWGTP,AGEP,CIT,CITWP05,CITWP12,COW,DDRS,DEAR,DEYE,DOUT,DPHY,DRAT,DRATX,DREM,ENG,FER,GCL,GCM,GCR,HINS1,HINS2,HINS3,HINS4,HINS5,HINS6,HINS7,INTP,JWMNP,JWRIP,JWTR,LANX,MAR,MARHD,MARHM,MARHT,MARHW,MARHYP05,MARHYP12,MIG,MIL,MLPA,MLPB,MLPCD,MLPE,MLPFG,MLPH,MLPI,MLPJ,MLPK,NWAB,NWAV,NWLA,NWLK,NWRE,OIP,PAP,RELP,RETP,SCH,SCHG,SCHL,SEMP,SEX,SSIP,SSP,WAGP,WKHP,WKL,WKW,WRK,YOEP05,YOEP12,ANC,ANC1P05,ANC1P12,ANC2P05,ANC2P12,DECADE,DIS,DRIVESP,ESP,ESR,FOD1P,FOD2P,HICOV,HISP,INDP,JWAP,JWDP,LANP05,LANP12,MIGPUMA00,MIGPUMA10,MIGSP05,MIGSP12,MSP,NAICSP,NATIVITY,NOP,OC,OCCP10,OCCP12,PAOC,PERNP,PINCP,POBP05,POBP12,POVPIP,POWPUMA00,POWPUMA10,POWSP05,POWSP12,PRIVCOV,PUBCOV,QTRBIR,RAC1P,RAC2P05,RAC2P12,RAC3P05,RAC3P12,RACAIAN,RACASN,RACBLK,RACNHPI,RACNUM,RACSOR,RACWHT,RC,SCIENGP,SCIENGRLP,SFN,SFR,SOCP10,SOCP12,VPS,WAOB,FAGEP,FANCP,FCITP,FCITWP,FCOWP,FDDRSP,FDEARP,FDEYEP,FDOUTP,FDPHYP,FDRATP,FDRATXP,FDREMP,FENGP,FESRP,FFERP,FFODP,FGCLP,FGCMP,FGCRP,FHINS1P,FHINS2P,FHINS3C,FHINS3P,FHINS4C,FHINS4P,FHINS5C,FHINS5P,FHINS6P,FHINS7P,FHISP,FINDP,FINTP,FJWDP,FJWMNP,FJWRIP,FJWTRP,FLANP,FLANXP,FMARHDP,FMARHMP,FMARHTP,FMARHWP,FMARHYP,FMARP,FMIGP,FMIGSP,FMILPP,FMILSP,FOCCP,FOIP,FPAP,FPOBP,FPOWSP,FRACP,FRELP,FRETP,FSCHGP,FSCHLP,FSCHP,FSEMP,FSEXP,FSSIP,FSSP,FWAGP,FWKHP,FWKLP,FWKWP,FWRKP,FYOEP,PWGTP1,PWGTP2,PWGTP3,PWGTP4,PWGTP5,PWGTP6,PWGTP7,PWGTP8,PWGTP9,PWGTP10,PWGTP11,PWGTP12,PWGTP13,PWGTP14,PWGTP15,PWGTP16,PWGTP17,PWGTP18,PWGTP19,PWGTP20,PWGTP21,PWGTP22,PWGTP23,PWGTP24,PWGTP25,PWGTP26,PWGTP27,PWGTP28,PWGTP29,PWGTP30,PWGTP31,PWGTP32,PWGTP33,PWGTP34,PWGTP35,PWGTP36,PWGTP37,PWGTP38,PWGTP39,PWGTP40,PWGTP41,PWGTP42,PWGTP43,PWGTP44,PWGTP45,PWGTP46,PWGTP47,PWGTP48,PWGTP49,PWGTP50,PWGTP51,PWGTP52,PWGTP53,PWGTP54,PWGTP55,PWGTP56,PWGTP57,PWGTP58,PWGTP59,PWGTP60,PWGTP61,PWGTP62,PWGTP63,PWGTP64,PWGTP65,PWGTP66,PWGTP67,PWGTP68,PWGTP69,PWGTP70,PWGTP71,PWGTP72,PWGTP73,PWGTP74,PWGTP75,PWGTP76,PWGTP77,PWGTP78,PWGTP79,PWGTP80

[Dictionary](http://www2.census.gov/programs-surveys/acs/tech_docs/pums/data_dict/PUMS_Data_Dictionary_2010-2014.txt)
[Converting to CSV to JSON using jq](http://infiniteundo.com/post/99336704013/convert-csv-to-json-with-jq)
[PUMS Technical Documentation](https://www.census.gov/programs-surveys/acs/technical-documentation/pums/documentation.html)


Other Links
===========

[Detailed Tables on Distribution of Wealth and Debt](http://www.census.gov/people/wealth/data/disttables.html)
[Public Use Microdata Areas (PUMAs)](https://www.census.gov/geo/reference/puma.html)
[2010 Census Public Use Microdata Area (PUMA) Reference Maps - California](http://www.census.gov/geo/maps-data/maps/2010puma/st06_ca.html)
[Maps and Geographic Data](http://www.census.gov/geo/maps-data/maps/2010puma/st06_ca.html)

