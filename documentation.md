## Documentation 

### Creating a new project
1. Click Duplicate for Sage Template - Make a Copy Only

### Getting Started with your project
2. Under Grids -> jsonLd Import/Export Config Grids you will see SAGE CONFIG TEMPALTE
3. To change name of the project go to three dots at upper right ... and click settings. Change Title to relevant project name. 
4. Change name of a space by going to Taxonomies -> Spaces Definitions
5. Create a new space by clicking "All Spaces" or the current Space name at the upper left and click "+Add"
6. To add multiple spaces at a time click "Add More", otherwise jsut "Add & Close"
7. Click the top right 3 dots ... and click Plugins.
8. Under JSON-LD Importer click Open.
9. For the name of the import by default it says the date and time for example "Import - 6/12/2024, 10:16:36 PM". This is useful for restoring backups so I recommend to not change.
10. For Schema Url you can put a link to the jsonld file such as the raw data in github.
11. Or you can select Click to Upload and select the .jsonld file saved to your local computer.
12. Under "In Space" select the correct space. This is important to make sure you are uploading the data model to the correct space!
13. For Import type, if this is your first time importing click "Dynamic". In the future, if you re-import the data model, you will want to click "Merge" (This is especially important to avoid the dynamic import so you don't get duplicate nodes)
14. Under Import Profile click SAGE CONFIG TEMPLATE.  This is the template that is used to convert to the jsonld format that is compatibile with schematic. 
15. When you click next you will see a preview of the Import which shows the transformations from the SAGE CONFIG TEMPALTE. You should not need to make any changes and click the upper green left box "Proceed".
16. A "Task Details" menu will appear which lists "Initializing", "Parsing the file", Generating the schema", and "Creating nodes and relations". If all goes well the status will be "Success"
17. Refresh the page and click Types -> Types Grid. You will see all your types in your space.
18. If you don't see the types -> double check that you are in the correct Space by going to the upper left and clicking the drop down menu to select the space.

### Sharing your project
19. Sharing settings are configured on a 'project by project basis'. To add contributors, select the upper right 3 dots ... and click Contributors. Next to Add contributor, type in the user's email. Select the role you want the user to have (Admin, Viewer, Editor, Exporter) and click the green button Add.
    ### Working with the model 

20. 



### Common Errors 

Not having the "label" column filled out will result in the schema convert function not working


### Tips
