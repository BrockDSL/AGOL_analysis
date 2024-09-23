![image](https://github.com/user-attachments/assets/c4db24f0-6608-4e7c-b957-baf555618400)


### Section 1: Signing in  

If you are an organization affiliate (i.e. a member of the Brock University community) follow these steps:  

1. Go to [arcgis.com](https://arcgis.com)    
2. Click **Sign in** 
3. Click **Your ArcGIS Organization's URL**  
4. Complete the URL by entering the text **brock**  

   ![Brock organization](https://github.com/user-attachments/assets/f0e4734a-af23-4c53-8dbe-480d79e5048e)


6. Click **Continue**
7. Click **BROCK UNIVERSITY**    
8. This action should direct you to the Brock University authentication page. Enter your Brock credentials and click **Sign in**.  

   ![AGOL homepage](https://github.com/user-attachments/assets/278a64c5-8e09-43a8-98f3-ba8f89c476fb)


---

### Section 2: The Interface  

1. From the menus at the top, click **Map**. This action opens the default map viewer and should look like this:  

   ![map interface](https://github.com/user-attachments/assets/f3a9bb80-913c-41be-82b5-f91160245f9d)
   
**NOTE: If the default viewer does not look like the above screenshot, you may have to click 'Open in new map viewer' at the top right.**

The New Map Viewer is composed of a dark toolbar on the left and a light toolbar on the right. Depending on the tool you have selected, various panels will appear.  

2. At the bottom of each toolbar there is a 'collapse/expand' button ![collapse expand](https://github.com/user-attachments/assets/5fc20556-3a72-4524-a3aa-c82e499db7e3)Click these buttons to collapse or expand the menus.  
3. Click the 'hide/show interface' button ![hide show interface](https://github.com/user-attachments/assets/862521a0-112f-4819-996c-408b8b6a9f26)
 (bottom right of the map view) to hide/show all menus and panels at once.  
4. To search for a location, click the magnifying glass ![search tool](https://github.com/user-attachments/assets/916f116a-04ba-46f1-8695-50bc431fcee6) from the lower right options. Type in a place or address and make a selection from the results. The map zooms to the location.  
5. Use the mouse scroll wheel or the zoom tools to pan and zoom on the map.
6. The map viewer provides ready-made basemaps to choose from. Click the basemap button ![basemap](https://github.com/user-attachments/assets/19cfb864-e626-4c41-a079-f1f9feea030f)
 on the left and explore the options. Before continuing, select the *Light Gray Canvas* option.  
7. At the top of the Basemap listing options, click **Current basemap >**  

   ![image](https://github.com/user-attachments/assets/e7752855-1d40-46d4-864e-608bc8301d7c)

8. Click the eyeball icon to turn off the *Light Gray Reference* layer. This action turns off the placename labels.

![image](https://user-images.githubusercontent.com/45638590/167662115-387d0255-a598-4264-9da9-7823f56d6636.png) 
    
9. To save your map, click the **Save > Save as** button ![save](https://github.com/user-attachments/assets/f92f9236-bf20-4853-a5a3-cff3c71e8dca)

10. Enter a unique map name that does not include special characters. 
11. Click save. All of your work is saved in the cloud, making it accessible from any device with internet connection.  

---

### Section 3: Finding Data

1. Open a new tab in Chrome and search for "Niagara Open Data". The result is a portal for open data as it relates to the Niagara Region.
2. Search the portal using the term "Licensed Child Care"
3. Click the title for *Licensed Child Care Centres*
4. Click the title for the *ArcGIS GeoService* entry

![image showing ArcGIS GeoService entry](https://github.com/user-attachments/assets/0a532876-ec7a-46c0-a2e1-9211f97f6b34)

5. Right-click the URL and select **copy link address**
---
![image](https://github.com/user-attachments/assets/905c1842-a258-4080-9093-b4e01d37b34b)

---

### Section 4: Adding a GeoService to ArcGIS Online

1. Go back to the tab for ArcGIS Online
2. Click **Map** to open the Map viewer (if necessary).
3. Click ![image](https://github.com/user-attachments/assets/ea29e4da-56ef-48ed-96ac-8f7260473987) > **Add layer from URL**
4. Use **Ctrl-V** to paste the URL from the clipboard
5. Click **Add to map**
6. The Licensed Child Care facilities will be displayed as points on the map using a circular point symbol and random colour.

![image](https://github.com/user-attachments/assets/9f7d1ad5-6658-4680-a952-d289675242f2)

### Section 5: Applying Filters

The default view shows Licensed Child Care Facilities for the entire region. Using the attached attributes, we can filter the data to only show records that meet certain criteria.

1. With the newly added layer selected (you will know it is selected by the blue vertical bar to the left of the layer name in the Contents listing), click the Filter tool from the options on the right.
2. Click + Add New
3. Create the "Condition" statement: Municipality is St. Catharines
4. Click Save.
5. The map now reflects data for just the city of St. Catharines.

### Section 6: Find by Attributes

Alternately, the data can be queried by using various "Select" tools such as *Find by attributes and location*

1. Click Analysis Tools ![image](https://github.com/user-attachments/assets/d81e3294-6afd-408b-bbd8-78e0f09a3a8c)

2. Click Tools.
3. Search using keyword "Find".
4. Select *Find by attributes and location* ![image](https://github.com/user-attachments/assets/29e351fd-a8bb-4e17-9660-5a8f5962e275)

5. Build a new query. The Query builder opens.
6. Select the layer you want to build the query on (i.e. Licensed Child Care Centres)
7. Select "Attribute Expression" and click Next.
8. Enter the query statement **NBH_ID=ST8** (this tells the software to isolate only the St. Catharines neighbourhood with I.D. "ST8")

![image](https://github.com/user-attachments/assets/d0968341-d059-442e-9ea8-3c9467d7cbf7)

9. Click Add.
10. Provide an output name.
11. Estimate credits to see the 'cost' of this tool. Then click **Run**.
12. A new feature layer is created reflecting only licensed child care centres in neighbourhood 8.
13. Turn off (click the eyeball icon beside the layer) the original child care data layer.
14. Use the zoom tools or mouse scroll wheel to zoom to the neighbourhood. It should look like this:

![image](https://github.com/user-attachments/assets/fd7a8f46-f516-414c-afd7-fdd5aa8b20dd)


### Section 7: Style by Category

1. Select the query output layer from the previous section.
2. Click Styles. ![image](https://github.com/user-attachments/assets/1b45d1b0-dfe0-43fc-896a-46cc5fa62842)

3. Click + Field to add each field associated with an age group.

![image](https://github.com/user-attachments/assets/4433888b-9c85-44c7-ad5d-01c9c3393039)

![image](https://github.com/user-attachments/assets/71813786-e212-4570-b895-20acaeab6d68)

4. Click Add.
5. Scroll down (if necessary) and click **Charts and Size"" ![image](https://github.com/user-attachments/assets/6b2b4032-2bd2-4297-8aea-60c18c023a7e)
6. Click Style Options > Colour
7. Here, you can select a different colour ramp and adjust the shape:
8. Under the Shape slider, shift the option to the middle so the symbol looks more like a donut.
9. ![image](https://github.com/user-attachments/assets/5f3c227e-ed40-42dc-bfc9-15fe7a8f28f0)

![symbol image](https://github.com/user-attachments/assets/62216650-32df-4414-83ea-43929fa21935)


10. Click Done, done and done. The symbol now represents the total number of spaces (size) and the break down of those spaces by age (colour).
11. To view the legend, click ![legend image](https://github.com/user-attachments/assets/7f5b54d5-029d-42ab-8317-54c96bd53a2b)

![symbols and legend image](https://github.com/user-attachments/assets/4ca436e6-f6f9-489e-96ad-b17c8630d5c2)

### Section 8: Drive Analysis

1. Click the Analyis tools. (You may have to click the little back arrow to exit the active tool)
2. Search by keyword **Drive**
3. Select *Generate travel areas*
4. The input layer is the layer representing Neighbourhood 8.
5. Cut-offs > 2, click **+ Add** (this represents a 2 minute drive time)
6. Enter a name for the Result layer
7. Estimate credits and click **Run**. The process may take a minute to complete. The result will look like this:

![image](https://github.com/user-attachments/assets/23332841-7ec3-4ecc-bb95-06832c3b655e)

### Section 9: Enrichment

Using the newly created polygons, we will use the enrichment tool to calculate socio-demographic statistics for the study area. These data are calculated from various sources including Statistics Canada and Environics Analytics. 

1. Click the little back arrow to exit the current analysis tool.
2. Search by keyword, "enrich".
3. Select **Enrich Layer**
4. For Input Features, select the drive analysis output layer.
5. Under Enrichment data, click **+ Variable**. Here you need to make sure that Canada is selected as the country and then you can search by keyword to find the variables of interest. For the sake of this tutorial, select **Households > 2023 Children at Home: Under 5** and select **Income > 2023 Household Median income (current year$)**
6. Click **Select**.
7. Enter a name for the output layer.
8. Estimate credits and click **Run**.
9. A new layer is added to the contents list ![image](https://github.com/user-attachments/assets/4463d42b-b117-4743-933c-9e8513c04517)
10. Click a feature on the map to see the pop-up with the added data attached.

![image](https://github.com/user-attachments/assets/5c1be69e-d65a-4eb3-a738-24bbda649994)

11. With the enriched layer selected from the Contents listing on the left, click Styles from the right.
12. Add + field > Children at home
13. The result tells us where the higher populations live with children at home under the age of 5.

![image](https://github.com/user-attachments/assets/20798c4d-d3cd-4d62-b490-f6aa4c1146ef)

### Section 10: Make it "POP"!

This section is optional but your map will thank you for paying a bit of attention to the stylization of layers and basemaps.

1. Click Basemap ![image](https://github.com/user-attachments/assets/407d78ce-629f-4939-ba92-203dec741831)
 and selct **Dark Gray Canvas**
2. Select the point layer representing child care centres and drag it up in the Contents listing.
3. Click Effects and toggle on **Drop Shadow**
4. Select the enriched layer and click **Properties** > Blending > Contrast > Overlay














<!--- Please use reference style images so that it is easier to update pictures later --->

[imglogo]: INSERT LOGO FILENAME HERE

