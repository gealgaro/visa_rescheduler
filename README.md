# visa_rescheduler
US VISA (ais.usvisa-info.com) appointment re-scheduler - Vancouver, CA adaptation

## Changes introduced
- Asks for confirmation of the scheduled date before starting the script, to avoid re-scheduling wrongly
- Kept support for spanish and added english language based on the country code
- Updated with a new cooldown time value based on experience after testing the script. Changed from 30 minutes to 5 hours
- Added support for multi applicant accounts
- Code improvements/adaptations

## Prerequisites
- Having a US VISA appointment scheduled already
- Google Chrome installed (to be controlled by the script)
- Python v3 installed (for running the script)
- API token from Pushover and/or a Sendgrid (for notifications)

## Initial Setup
- Create a `config.ini` file with all the details required
- Install the required python packages: `pip3 install -r requirements.txt`

## Executing the script
- Simply run `python3 visa.py`
- That's it!

## Acknowledgement
Thanks to @yaojialyu for creating the initial script and to @cejaramillof for adapting it to Colombia!
