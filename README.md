# Calendar Utility

This is a repo that contains a working example of how to convert a CSV of assignments, deadlines, and comments to an ics file programmatically.
The best place to start is the notebook](https://github.com/firasm/calendar_utility/blob/master/Calendar.ipynb) which relies on the [ics](https://icspy.readthedocs.io/en/stable/) package.

## Requirements

- [ics](https://icspy.readthedocs.io/en/stable/) python package
- [pandas](https://pandas.pydata.org)

## What it does

Start with a [csv of dates and deadlines](https://github.com/firasm/calendar_utility/blob/master/template_dates.csv):

<img src = "https://github.com/firasm/calendar_utility/blob/master/images/csv.png" width=400px>

And end up with [an ics file](https://github.com/firasm/calendar_utility/blob/master/template.ics):

<img src = "https://github.com/firasm/calendar_utility/blob/master/images/calendar.png" width=600px>

## Usage

None yet...

## To-do list

- add default alarms
- Make it so that this calendar is subscribable 
- Link it to jupyterbook md/csv table and run it via a GH action
- turn this into a package?
