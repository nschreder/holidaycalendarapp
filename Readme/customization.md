# Customization
You have several options available to customize the holiday calendar Power App. To start with the customization process, you must open the app in edit mode using [PowerApps Studio](https://make.powerapps.com):

![PowerApps Studio](/Readme/Customization/Customization%201.jpg)

**Information**: After customizing the Power App, you must [republish](#Republishing-the-app) your app again.

## I want to customize the content of the holiday calendar
If you want to customize the holiday calendar and import your content, you can start with downloading and editing the [template](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2Fnschreder%2Fholidaycalendarapp%2Fmain%2FHolidayCalendarService%2FTemplate%2FTemplate.xlsx&wdOrigin=BROWSELINK) in Microsoft Excel. After adjusting it you can use the [customize the app tutorial](#Customize-the-app) to import the changes.

![Excel](/Readme/Customization/Template%201.jpg)

| Field | Description |
|---|---|
| title | The title for the entry. |
| publishDate | The day for the entry. It only can be opend during/after the day. |
| primaryLink | The content shown after opening the entry (URL). |
| categories | The advent calendar can show different types of content. The types "Image", "Video", and "Link" will open the content in the specific player/reader, and "Link" will redirect the user directly to the source by opening a new browser tab. |

**Information:** Excel is formatting links differently as PowerApps is processing it. To ensure a working solution, make sure that you only include text values instead of links.

## I want to change the introduction text on the left side
To change the introduction text, you must click on "lblInfo" in the tree view on the left side of the Power Apps Studio. In the properties editor, you can change the text in the "Text" field.

![PowerApps Studio](/Readme/Customization/Customization%202.jpg)

## I want to change the logo or background image
To change the logo, you must click on "imgLogo" in the tree view on the left side of the Power Apps Studio. In the properties editor, you can change the image in the "Image" field by uploading a new image and selecting it.

![Power Apps Studio](/Readme/Customization/Customization%203.jpg)

To change the background image, you must click on "Home Screen" (and "Entry Screen") in the tree view on the left side of the Power Apps Studio. In the properties editor, you can change the background image in the "Background image" field by uploading a new image and selecting it.

![Power Apps Studio](/Readme/Customization/Customization%204.jpg)

## I want to change the content of the holiday calendar
1. Open the data section on the left side and remove the existing "Content" data source by clicking on "..." and then "Remove":

![Power Apps Studio](/Readme/Customization/Customization%205.jpg)

2. Add your customized content by clicking on "Add data" and searching for/selecting the "Import from Excel" data source:

![Power Apps Studio](/Readme/Customization/Customization%206.jpg)

3. Select your customized Excel spreadsheet and click on "Content" in the "Choose a table" panel. Click on "Connect" to import the Excel file:

![Power Apps Studio](/Readme/Customization/Customization%207.jpg)

## I want to change the Power App icon, name, description, or background color (during startup)
You can change the icon in the app described [here](https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/set-name-tile).

## Republishing the app
In the main menu click on "Publish":

![Power Apps Studio](/Readme/Customization/Customization%208.jpg)
