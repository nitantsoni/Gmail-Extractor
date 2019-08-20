# Gmail-Extractor
Extract URLs from a specified Label in Gmail and dump to a Google sheet

Modified from source - https://helgeklein.com/blog/2015/02/extracting-all-email-addresses-from-a-gmail-label/

#How to use

 - Click here - https://docs.google.com/spreadsheets/d/1hzS0w6H8LXNCoBpoFx9cqDgJ4skG_bImM3TxYBy-wH0/copy - to get a copy of the Google Sheet

 - Fill in the Value for "Label to search:" 

 - Click on the "Get Links" Menu Item & "Extract URLs" to kick it off!

The script will pick up the first match of the regex (Line 41) from each email and output that to the sheet.

#Notes

 - It is highly unlikely that the script will work for you on the first go. The Regex match on Line 41 will need some tweaking to match the format of your URLs/Emails being parsed.
 - Test the "GetURLs" function via the Script Editor to troubleshoot further.
 - Use the commented out "Logger.log" to view the matches, in the Logs
