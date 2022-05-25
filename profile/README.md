# Welcome to the Sunny Day Flooding Project (SDFP)

Here are our main repos sorted by purpose:

**Tutorials**
- [**tutorials**](https://github.com/sunny-day-flooding-project/tutorials) - a list of step-by-step instructions to build and deploy SDFP loggers and cameras.

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
