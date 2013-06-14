Alfred-KalliopeC2C
==================

An Alfred plugin to dial numbers on a Kalliope PBX


Setup the plugin using those parameters:

SERVER=The http prefix url for your calliope
USERNAME=Your phone's username
PASSWORD=Your phone's password MD5 encoded
TIMEOUT=The connection timeout in seconds
STRIPCHARS=A regular expression array of bad characters to strip from phone numbers

Example
SERVER=http://192.168.43.104
USERNAME=20
PASSWORD=165c3277d601bc93aa053489b12f90cd
TIMEOUT=5
STRIPCHARS=("+39" "[ -]")  # Removes the Italian country code prefix, spaces and - chars