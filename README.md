# remmina-rdp-bulk-session-creator<br />
Python Script to create remmina session files based on an excel spreadsheet<br />
update the excel sheet based on the given values, and move the created files to where remmina is storing your sessions<br />
by default, remmina stores session files in ~/.local/share/remmina<br />
install openpyxl if it's not installed on your device<br />
pip install openpyxl<br /><br />


For the password hash, just create one manually, and copy paste it from the session file into the excel (it's actually created using 3DES and a random key)
