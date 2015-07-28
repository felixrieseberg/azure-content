<properties
	pageTitle="How to use the Azure Storage Explorer with Microsoft Azure Storage"
	description="Learn how to use the Azure Storage Explorer to upload, download and preview blobs"
	services="storage"
	documentationCenter=""
	authors="feriese"
	manager="mandr"
	editor=""/>

<tags
	ms.service="storage"
	ms.workload="storage"
	ms.tgt_pltfrm="na"
	ms.devlang="na"
	ms.topic="article"
	ms.date="07/28/2015"
	ms.author="feriese"/>

# Getting Started with the Azure Storage Explorer for Blob Storage

## Overview

The Azure Storage Explorer is an open source, cross-platform blob storage explorer, enabling you to easily work with blob assets and containers from any platform. Create and delete containers, upload, download, and delete whole virtualized folders and files, or preview media assets.

![Azure Storage Explorer Screenshots](Image1)

## Download and install Azure Storage Explorer

1. Download the [latest version of Azure Storage Explorer](http://www.storageexplorer.com/#releases), or the [latest preview version](http://www.storageexplorer.com/#devbuilds).
2. Run the installation. For Mac OS X, download the DMG and put the app into your Applications folder. On Windows, either download an unzip the standalone version; or download and execute the MSI installer. On Linux, download the ZIP and move the application and its supporting files to your desired location.

## Connect to a Blob Storage Account

If you have not yet added a Storage Account, the application will automatically switch to the 'Add Storage Account' screen. To find the correct storage account name and storage key for your account, open the Azure Management Portal and select 'Storage'. Navigate to a storage account and click the 'Manage Access Keys' button in the lower menu bar to display both the correct storage account name and key.

![Management Portal (Classic): Getting Access Keys](Image2)

If you are using the new Azure Management Portal, navigate to your storage account and click on the 'key' icon in the white actions bar.

![Management Portal: Getting Access Keys](Image3)

## Managing Blob Assets

The left menu is filled with the containers in your storage account. You can create a new container by clicking on the 'plus' icon in the upper actions bar - and delete the current container by clicking on the 'minus' icon.

Individual blob assets for the current container will be displayed in the main table on the right. Note that Azure Storage Explorer uses virtualized folders, meaning that blobs with names beginning with **myFolder/** will be shown as a virtualized folder named **myFolder**. To upload blobs, simply click on the 'upload' icon in the upper actions bar. To download blobs, mark them by clicking the checkbox on the left of a blob and click the 'download' icon in the upper actions bar. To preview a multimedia blob asset, just click on it - a preview will be displayed in the lower left.

![Azure Storage Explorer Screenshot](Image4)

[Image1]: ./media/storage-ase/Screenshots.png
[Image2]: ./media/storage-ase/Get_Access_Keys1.png
[Image3]: ./media/storage-ase/Get_Access_Keys2.png
[Image4]: ./media/storage-ase/Screenshot.png

### Azure Storage documentation:

- [Introduction to Azure Storage](storage-introduction.md)
- [Store files in Blob storage](storage-dotnet-how-to-use-blobs.md)

### Azure Storage Explorer

- [Website](http://www.storageexplorer.com)
- [Source Code on GitHub](http://github.com/azure-storage/xplat)
- [Contributing Guide](https://github.com/azure-storage/xplat/blob/master/CONTRIBUTING.md)
