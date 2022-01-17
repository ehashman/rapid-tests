## Home COVID-19 rapid antigen tests approved in the US

Rapid antigen tests (RATs) for COVID-19 have been in [very short supply](https://www.propublica.org/article/heres-why-rapid-covid-tests-are-so-expensive-and-hard-to-find) in the United States.

I have been frustrated that RATs are so expensive in the US, especially given their accuracy. Every time a colleague recommended a test for purchase, the accuracy was significantly lower than these [JoysBio tests](https://web.archive.org/web/20211130131927/https://en.joysbio.com/covid-19-antigen-rapid-test-kit/) I was able to obtain in 2021. However, such tests aren't currently available in the US under an emergency use authorization (EUA) from the FDA.

I wanted to compare the accuracy of the various home [rapid antigen tests available under EUA](https://web.archive.org/web/20220116142233/https://www.fda.gov/medical-devices/coronavirus-disease-2019-covid-19-emergency-use-authorizations-medical-devices/in-vitro-diagnostics-euas-antigen-diagnostic-tests-sars-cov-2), so I filtered by "Home Test" on the FDA website and pulled the data from each test's Instructions For Use (IFU) sheet.

### EUA home test data

Data fetched on Mon. Jan. 17, 2022. [(Download it as a CSV)](files/RAT_data.csv)

Name | Manufacturer | Sensitivity (PPA) | Low PPA[^1] | High PPA[^1] | Specificity (NPA) | Low NPA[^1] | High NPA[^1] | Total Samples | Type
-- | -- | -- | -- | -- | -- | -- | -- | -- | --
[BinaxNOW COVID-19 Antigen Self-Test] | Abbott | 84.6 | 76.8 | 90.6 | 98.5 | 96.6 | 99.5 | 460 | Nasal swab
[CareStart COVID-19 Antigen Home Test] | Access Bio | 87 | 70 | 95 | 98 | 93 | 99 | 153 | Nasal swab
[Flowflex COVID-19 Antigen Home Test] | ACON | 93 | 81 | 99 | 100 | 97 | 100 | 172 | Nasal swab
[BD Veritor At-Home COVID-19 Test] | Becton Dickinson | 84.6 | 70.3 | 92.8 | 99.8 | 99 | 100 | 597 | Nasal swab
[Celltrion DiaTrust COVID-19 Ag Home-Test] | Celltrion | 86.7 | 73.8 | 93.7 | 99.8 | 98.7 | 100 | 492 | Nasal swab
[Ellume COVID-19 Home Test] | Ellume | 95 | 82 | 99 | 97 | 93 | 99 | 198 | Nasal swab
[iHealth COVID-19 Antigen Rapid Test] | iHealth Labs | 94.3 | 81.4 | 98.4 | 98.1 | 93.3 | 99.5 | 139 | Nasal swab
[SCoV-2 Ag Detect Rapid Self-Test] | InBios | 85.71 | 70.62 | 93.74 | 100 | 98.3 | 100 | 257 | Nasal swab
[InteliSwab COVID-19 Rapid Test] | OraSure | 84 | 71 | 92 | 98 | 93 | 99 | 146 | Nasal swab
[QuickVue At-Home OTC COVID-19 Test] | Quidel | 83.5 | 74.9 | 89.6 | 99.2 | 97.2 | 99.8 | 350 | Nasal swab
[COVID-19 At-Home Test] | SD Biosensor | 95.3 | 84.5 | 98.7 | 100 | 95.7 | 100 | 128 | Nasal swab
[CLINITEST Rapid COVID-19 Antigen Self-Test] | Siemens | 86.5 | 79.6 | 91.3 | 99.3 | 95.9 | 100 | 268 | Nasal swab

[^1]: Based on a 95% confidence interval.

[BinaxNOW COVID-19 Antigen Self-Test]: files/EUA-abbott-bNOWHome-ifu.pdf
[CareStart COVID-19 Antigen Home Test]: files/EUA-accessbio-Aghome-ifu.pdf
[Flowflex COVID-19 Antigen Home Test]: files/EUA-ACONlab-flowflexAg-ifu.pdf
[BD Veritor At-Home COVID-19 Test]: files/EUA-BD-VeritorhomeAg-ifu.pdf
[Celltrion DiaTrust COVID-19 Ag Home-Test]: files/EUA-Celltrion-AgHomeTest-ifu.pdf
[Ellume COVID-19 Home Test]: files/EUA-Ellume-HomeAg-ifu.pdf
[iHealth COVID-19 Antigen Rapid Test]: files/EUA-iHealth-RapidTestAg-ifu.pdf
[SCoV-2 Ag Detect Rapid Self-Test]: files/EUA-InBios-DetectAgOTC-ifu.pdf
[InteliSwab COVID-19 Rapid Test]: files/EUA-Orasure-InteliswabOTC-ifu.pdf
[QuickVue At-Home OTC COVID-19 Test]: files/EUA-QuickVue-OTC-ifu_0.pdf
[COVID-19 At-Home Test]: files/EUA-SDBio-AtHome-ifu.pdf
[CLINITEST Rapid COVID-19 Antigen Self-Test]: files/EUA-Siemens-CliniTestAg-ifu.pdf


