# Data_Monitor

# Monitor a data file for any updates by polling it for download, at some time increment, and comparing it with the last downloaded version that was saved. If there is an update (i.e., a change in the newest downloaded file) then save another file with the differences only, create a visualization from it, and send an email with the new visualization as an attachment. In addition, send an sms message notification of the email. If there isn't an update then those redundant downloads are deleted and the polling continues. All the visualizations are date/time stamped and saved to disk as are their source files - for later analysis.
