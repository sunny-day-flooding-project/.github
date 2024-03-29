# Welcome to the Sunny Day Flooding Project (SDFP)

Publication describing the Sunny Day Flooding Sensors (SuDS): [**Gold et al., (2023)**](https://doi.org/10.1029/2022WR032392)

Here are our main repos sorted by purpose:

**Tutorials**
- [**tutorials-v1**](https://github.com/sunny-day-flooding-project/tutorials_v1) - a list of step-by-step instructions to build and deploy the SDFP loggers and cameras as described in [**Gold et al., (2023)**](https://doi.org/10.1029/2022WR032392) (AC powered and wifi).
- [**tutorials-v2**](https://github.com/sunny-day-flooding-project/tutorials_v2) - a list of step-by-step instructions to build and deploy version 2 of the SDFP loggers and cameras (solar powered and cellular).

**APIs**
- [**sdfp-api**](https://github.com/sunny-day-flooding-project/sdfp-api) - an API that handles data I/O from SDFP loggers. Made with [FastAPI](https://github.com/tiangolo/fastapi).
- [**sdfp-photo-api**](https://github.com/sunny-day-flooding-project/sdfp-photo-api) - an API that handles photo I/O from SDFP flood cams. Made with [FastAPI](https://github.com/tiangolo/fastapi).

**Logger/Gateway code**
- [**SunnyD_CommsHub**](https://github.com/sunny-day-flooding-project/SunnyD_CommsHub) - code that runs on our deployed Raspberry Pis to communicate with loggers and transmit data to our cloud database.
- [**OpenLog_Artemis**](https://github.com/sunny-day-flooding-project/OpenLog_Artemis) - fork of [OpenLog_Artemis](https://github.com/sparkfun/OpenLog_Artemis) that runs on our pressure loggers.

**Data viz and processing**
- [**SunnyD-Flooding**](https://github.com/sunny-day-flooding-project/SunnyD-Flooding) - web app for visualizing real-time data and pictures from SDFP loggers and cameras. Made with [R Shiny](https://github.com/rstudio/shiny).
- [**sdfp-processing**](https://github.com/sunny-day-flooding-project/sdfp-processing) - code for processing raw data from SDFP sensors and converting it to water depth.
- [**sdfp-drift**](https://github.com/sunny-day-flooding-project/sdfp-drift) - code for removing drift from water depths from SDFP sensors.

Significant changes in sensor functionality since publication:
- updated drift correction algorithm for outlier elimination (May 4, 2023)
