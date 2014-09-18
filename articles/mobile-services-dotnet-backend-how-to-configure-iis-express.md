<properties pageTitle="Configure IIS Express for local testing of Mobile Service" metaKeywords="Azure Mobile Services, .NET Backend, IIS Express" description="Learn how to configure IIS Express to allow connections to a local mobile service project for testing." authors="glenga" title="Configure the local web server to allow connections to a local mobile service" />

<tags ms.service="mobile-services" ms.workload="mobile" ms.tgt_pltfrm="mobile-multiple" ms.devlang="Mobile-Multiple" ms.topic="article" ms.date="01/01/1900" ms.author="glenga" />

# Configure the local web server to allow connections to a local mobile service 

Azure Mobile Services enables you create your mobile service in Visual Studio using one of the supported .NET languages and then publish it to Azure. One of the major benefits of using a .NET backend for your mobile service is the ability to run, test, and debug the mobile service on your local computer or virtual machine before publishing it to Azure. 

To be able to test a mobile service locally with clients running on an emulator, virtual machine or on a separate workstation, you have to configure the local Web server and host computer to allow connections to the workstation's IP address and port. This topic shows you how to configure IIS Express to enable connections to your locally hosted mobile service. 

[WACOM.INCLUDE [mobile-services-how-to-configure-iis-express](../includes/mobile-services-how-to-configure-iis-express.md)] 
