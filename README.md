# Pruth Bay mooring data

Data from the temperature string mooring deployed near Pruth Bay by Calvert Island<br>

Hakai Catalogue: https://catalogue.hakai.org/dataset/ca-cioos_66ad87d2-bb96-4515-a907-6367ca6c0a2b

## References
- [Processed median daily temperatures / since December, 2017](https://hecate.hakai.org/sn/p/viewsndata.pl?dataTable=1daySamples&measurements=PruthMooring.WaterTemp_0m_Med,PruthMooring.WaterTemp_2m_Med,PruthMooring.WaterTemp_5m_Med,PruthMooring.WaterTemp_7_5m_Med,PruthMooring.WaterTemp_10m_Med,PruthMooring.WaterTemp_15m_Med,PruthMooring.WaterTemp_20m_Med,PruthMooring.WaterTemp_25m_Med,PruthMooring.WaterTemp_30m_Med,PruthMooring.WaterTemp_40m_Med,PruthMooring.WaterTemp_50m_Med,PruthMooring.WaterTemp_60m_Med)
- [Processed median daily temperatures / last year](https://hecate.hakai.org/sn/p/viewsndata.pl?dataTable=1daySamples&measurements=PruthMooring.WaterTemp_0m_Med,PruthMooring.WaterTemp_2m_Med,PruthMooring.WaterTemp_5m_Med,PruthMooring.WaterTemp_7_5m_Med,PruthMooring.WaterTemp_10m_Med,PruthMooring.WaterTemp_15m_Med,PruthMooring.WaterTemp_20m_Med,PruthMooring.WaterTemp_25m_Med,PruthMooring.WaterTemp_30m_Med,PruthMooring.WaterTemp_40m_Med,PruthMooring.WaterTemp_50m_Med,PruthMooring.WaterTemp_60m_Med&dateRange=last52weeks)
- [Processed median hourly temperatures / last year](https://hecate.hakai.org/sn/p/viewsndata.pl?dataTable=1hourSamples&measurements=PruthMooring.WaterTemp_0m_Med,PruthMooring.WaterTemp_2m_Med,PruthMooring.WaterTemp_5m_Med,PruthMooring.WaterTemp_7_5m_Med,PruthMooring.WaterTemp_10m_Med,PruthMooring.WaterTemp_15m_Med,PruthMooring.WaterTemp_20m_Med,PruthMooring.WaterTemp_25m_Med,PruthMooring.WaterTemp_30m_Med,PruthMooring.WaterTemp_40m_Med,PruthMooring.WaterTemp_50m_Med,PruthMooring.WaterTemp_60m_Med&dateRange=last52weeks)
- [Raw median hourly temperatures / last year](https://hecate.hakai.org/sn/p/viewsndata.pl?dataTable=1hourSamples&measurements=PruthMooring.WaterTemp_0m_Med,PruthMooring.WaterTemp_2m_Med,PruthMooring.WaterTemp_5m_Med,PruthMooring.WaterTemp_7_5m_Med,PruthMooring.WaterTemp_10m_Med,PruthMooring.WaterTemp_15m_Med,PruthMooring.WaterTemp_20m_Med,PruthMooring.WaterTemp_25m_Med,PruthMooring.WaterTemp_30m_Med,PruthMooring.WaterTemp_40m_Med,PruthMooring.WaterTemp_50m_Med,PruthMooring.WaterTemp_60m_Med&dateRange=last52weeks&original)
- [Google Drive folder](https://drive.google.com/drive/u/3/folders/0B0dKeVgv0CCCam9ZaXhLaTQxVU0)
## Data flow
Roughly speaking, here are the steps required to retrieve data and get it online
- Download new measurements from the sensors
- Using the sensor related software, export the measurements to a CSV file
- Commit both the raw (hobo) and exported (csv) file to the repository.  There are separate folders for raw and processed data, although you can store them both in the same folders if that works better
- All new measurements recorded in the last few weeks should be visible online within a couple of hours.  If you think something may not be working correctly, contact Ray
- All new measurements recorded in the last year should be visible by the next day.  If you think something may not be working correctly, contact Ray
- All new measurements should be visible in the next few days.  This really only applies if you are adding measurements recorded more than a year ago, so should not happen very often, if ever

## Data Release 
For any changes to the data repository main branch, a series of tests are applied. If all tests are sucessfully completed. The main branch is then merge automatically to the release branch. 
