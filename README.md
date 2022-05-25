# RevatureTimeSheet
### Automation for Revature Time Sheet submission
    Uses Object Repository
    Uses secured Login information to log into the Revature pay site
        login info stored in Orchestrator credential asset
    Navigates to Revature time sheet
    Checks if there is a Holiday from supplied list
        enters 8 hours Monday thru Friday if there is no Holiday
        enters 0 hours for the day if it is a Holiday
    Clicks the "...I certify..." check box
    Displays message box advising user to verify hours
    Submits the time sheet
    Sends submit verification via SMS & Email
    Logs out
    Closes the tab & browser

## Future Improvements
    Store Holiday list in Orchestrator