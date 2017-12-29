# wblotevogel.clamav
ansible role for clam antivirus

installs clamav with one config file. and a script which infoirms when there is a virus detected. You can change the script and let clamav do all kind of stuff when a virus is detected.

# Bonus
if you run the playbook in tests tests/av-check-status.yml it shows on screen if your virus scanner is up to date from the selected hosts. which is great for the auditors. they always want to seen if you anti virus is up to date.
