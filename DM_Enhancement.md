* __DM-79__  
    Please add another option to the DM grid view called "View All Selected." This needs to appear in the import and export logs.
    Choosing this option will incorporate all selected items in one grid view, so the user doesn't have to drill into each component to see the selected items.
    Since each component has different columns exposed, please explore the best way to fit all the data in one view so it looks appropriate.   
    
  >  DM grid view ==> "View All Selected"     **Grid View OR Menu Bar ?**  
Import & Export logs **?**  
Proper Columns  
#### Alternative:  Highlight the selected components
* __DM-82__  
    The Data Manager tool includes all configuration, but it would be nice to have the ability to mass-delete/inactivate configuration from the tool, as well. Currently, this is either a manual process or one that requires scripting, but if the capability was productized, it would empower the users and increase overall productivity among an organization.

    1. Add Delete capabilities in an Export Job
    2. Ensure there are ample warnings that a Delete is about to occur, and are you sure you want to continue with the permanent deletion
    3. There needs to be an option to create an export file of all the configuration data prior to delete. in case the user needs to restore. 
    4. *Note- the user must Delete in the source and target environment separately, in the Export Job.   
        
  > **Individual Deleting tool OR just DM's Enhancement ?**   
  Delete Action  ==> **Physical or Logical ?**  
  **Restore Plan**  
        
* __DM-114__  
    The current design on this is complex and hard to understand. Please re-design so this feature is easy to use and intuitive.
    Attaching screen shots of the current design, as well as some other areas of the system that do something similar, for inspiration.  
>  Mapping Re-design  ==>  show the specific data which is doing the mapping

* __DM-78__  
    Any data manager export file will contain a version number of the current version.   
    Data Manager will be enhanced to import an export file created from a previous version. Any new fields on the tables will be left to default values, or will not be populated by the job.   
    The import job will recognize a previous version, and provide a warning to the user: “Warning, you are attempting to import a file created by an earlier version of Data Manager. Do you want to continue?”   
    Provide the ability to export a data manager file in the format of older versions.  
>  **Version Flexibility**   
Export Different Version's Data  
Import Previous Version's Data
    
* __DM-80__  
    After starting a job, it only displays "Running" or "Complete." Please add a progress bar or something similar that can indicate to a user approximately how much time it will take.
    So, when the user clicks Start, a progress bar should show (please remove Running), then the Job Status should automatically go to "Complete" when it's done.  
>  Job Status ==> Progress Bar  
    
* __DM-125__  
    There are ways in which to customize a component's grid, like hiding columns, sorting columns, and grouping data.  
    However, there's no way to re-order columns. Also, there should be the ability to save the settings so the grid remains the same way upon next login. And of course, a re-set option is needed, too.  
>  Customize grid view & Save  
A initial Design & can do Re-set
