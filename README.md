# Azure IoT - Getting Started with Sphere
Azure Sphere is a secured, high-level application platform with built-in communication and security features for internet-connected devices. It comprises an Azure Sphere microcontroller unit (MCU), tools and an SDK for developing applications, and the Azure Sphere Security Service, through which applications can securely connect to the cloud and web.

If you were looking for Raspberry Pi, go [here](https://github.com/jasonerrett/AzureIoT_HelloRpi)

## Using Github
- [Download Github Desktop](https://desktop.github.com/)
- Click on the green **'Clone or download'** button, and copy the url.  *Note: if you download the ZIP file, you will miss out on any notifications of updates to the project.  But, if you don't want the additional software on your machine, this option is will work fine.*
- Open Github Desktop, click File -> Clone Repository -> Url tab -> Paste the url into the box -> specify the local folder to clone into -> hit **'Clone'**
- If you'd like more information... [Github Tutorial](https://lab.github.com/githubtraining/paths/first-day-on-github)

## Tools
These are not all required.  I will show some of them in the video, but if you have tools you prefer that work just fine, by all means use what you like.  All of these are freely available.
- [Azure Device Explorer](https://github.com/Azure/azure-iot-sdk-csharp/releases/download/2019-1-4/SetupDeviceExplorer.msi) (Helpful if using IoT Hub)
- Visual Studio 2019 Enterprise, Professional, or (free) [Community Edition](https://visualstudio.microsoft.com/vs/community/) 16.04 or later; or Visual Studio 2017 version 15.9 or later. To install Visual Studio, select the edition to install and then run the installer. You can install any workloads, or none.

## Getting Started with Azure Sphere
- Hardware Overview
    - GPIO pins are your gateway to interacting with the "real" world.  This site, [MT3620 Dev Board User Guide](https://docs.microsoft.com/en-us/azure-sphere/hardware/mt3620-user-guide), has a good explanation of the hardware layout and pins
    - Azure Docs guide for [Using GPIOs on Azure Sphere](https://docs.microsoft.com/en-us/azure-sphere/app-development/gpio)
- Common starter dev/test Peripheral
    - [Grove Starter Kit](https://www.seeedstudio.com/Grove-Starter-Kit-for-Azure-Sphere-MT3620-Development-Kit.html)
    - [Grove Shield Library on GitHub](https://github.com/Seeed-Studio/MT3620_Grove_Shield)
- Setup
    - [Getting Started with Azure Sphere](https://docs.microsoft.com/en-us/azure-sphere/)
    - High-level Steps:
        1. Install Drivers
        2. Install the Azure Sphere SDK
        3. Update the Azure Sphere OS
        4. Set up an account for Azure Sphere
        5. Claim your device in the Azure Sphere tenant
        6. Go through Quickstarts

## Connecting the Sphere Devkit to Azure IoT Central
- [Set up Azure IoT Central to work with Azure Sphere](https://docs.microsoft.com/en-us/azure-sphere/app-development/setup-iot-central)
- [Run the sample with an IoT Central](https://github.com/Azure/azure-sphere-samples/blob/master/Samples/AzureIoT/IoTCentral.md)

## Connecting the Sphere Devkit to Azure IoT Hub
- [Run the sample with an IoT Hub](https://github.com/Azure/azure-sphere-samples/blob/master/Samples/AzureIoT/IoTHub.md)

## Azure Services Common in IoT Architectures
- [Example Architecture Diagram](images/AzureIoTArchitecture.png
)
- Device Registration / Ingestion
    - [IoT Hub](https://docs.microsoft.com/en-us/azure/iot-hub/about-iot-hub)
    - [IoT Central](https://docs.microsoft.com/en-us/azure/iot-central/overview-iot-central) *Note: also has visualization, analytics, etc.*
    - [Device Provisioning Service](https://docs.microsoft.com/en-us/azure/iot-dps/about-iot-dps)
    - [Event Hubs](https://docs.microsoft.com/en-us/azure/event-hubs/event-hubs-about)
- Storage
    - [Azure Storage](https://docs.microsoft.com/en-us/azure/storage/common/storage-introduction)
    - [Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/introduction)
- Analytics
    - [Stream Analytics](https://docs.microsoft.com/en-us/azure/stream-analytics/stream-analytics-introduction)
    - [Time Series Insights](https://docs.microsoft.com/en-us/azure/time-series-insights/time-series-insights-update-overview)
    - [Server-less Functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview)
- Integration & Visualization
    - [Logic Apps](https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-overview)
    - [Power BI](https://docs.microsoft.com/en-us/power-bi/power-bi-overview)
- Disconnected Scenarios (Very cool stuff)
    - [IoT Edge](https://docs.microsoft.com/en-us/azure/iot-edge/about-iot-edge)
    - [Container Registry](https://docs.microsoft.com/en-us/azure/container-registry/container-registry-intro)
- Artification Intelligence
    - [Cognitive Services](https://docs.microsoft.com/en-us/azure/cognitive-services/)
- 3rd-Party and Open source
    - [SendGrid](https://docs.microsoft.com/en-us/azure/sendgrid-dotnet-how-to-send-email)
    - [Kafka](https://docs.microsoft.com/en-us/azure/hdinsight/kafka/apache-kafka-introduction)
    - [Spark](https://docs.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-overview)
    - [Storm](https://docs.microsoft.com/en-us/azure/hdinsight/storm/apache-storm-overview)
    - [Notebooks](https://docs.microsoft.com/en-us/azure/notebooks/azure-notebooks-overview)
    - Bring-your-Own on [Virtual Machines](https://azure.microsoft.com/en-us/services/virtual-machines/)

## Azure Solution Accelerators
- [IoT Solution Accelerators](https://azure.microsoft.com/en-us/features/iot-accelerators/)
    - Remote Monitoring
    - Device Simulation
    - Connected Factory
    - Predictive Maintenance

## Free Supplemental Learning Materials
- [Microsoft Learn](https://docs.microsoft.com/en-us/learn/)
- [IoT School](https://iotschool.microsoft.com/)
- [AI School](https://aischool.microsoft.com/)
- [IoT & AI Workshop](https://github.com/kenhausman/ADSWorkshop)
- [Microsoft Professional Certification Programs](https://www.edx.org/course/?type=Professional%20Certificate&school=Microsoft%3A%20Microsoft) *Note: free if just learning, but there is a fee to receive certification upon completion*
- [Other edX Courses](https://www.edx.org/course?search_query=Azure)

## Other Useful Stuff
- [Anomaly Detection in Azure Stream Analytics](https://docs.microsoft.com/en-us/azure/stream-analytics/stream-analytics-machine-learning-anomaly-detection)
- [Custom Vision at the Edge Walkthrough](https://docs.microsoft.com/en-us/azure/iot-edge/tutorial-deploy-custom-vision)
- [Container Support in Azure Cognitive Services](https://docs.microsoft.com/en-us/azure/cognitive-services/cognitive-services-container-support)
- [Using the MXChip IoT DevKit](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-arduino-iot-devkit-az3166-door-monitor)
- [Azure IoT Security](https://azure.microsoft.com/en-us/overview/iot/security/)
- [Azure Security Center for IoT](https://docs.microsoft.com/en-us/azure/asc-for-iot/overview)
- [IoT Security Architecture](https://docs.microsoft.com/en-us/azure/iot-fundamentals/iot-security-architecture)
- [IoT Security Best Practices](https://docs.microsoft.com/en-us/azure/iot-fundamentals/iot-security-best-practices)
- [Secure Deployment of IoT](https://docs.microsoft.com/en-us/azure/iot-fundamentals/iot-security-deployment)



