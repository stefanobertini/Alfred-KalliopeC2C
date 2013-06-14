Alfred-KalliopeC2C
==================

An Alfred plugin to dial numbers on a Kalliope PBX


Setup the plugin using those parameters:


SERVER=The http prefix url for your calliope<br>
USERNAME=Your phone's username<br>
PASSWORD=Your phone's password MD5 encoded<br>
TIMEOUT=The connection timeout in seconds<br>
STRIPCHARS=A regular expression array of bad characters to strip from phone numbers

Example<br>
SERVER=http://192.168.43.104<br>
USERNAME=20<br>
PASSWORD=165c3277d601bc93aa053489b12f90cd<br>
TIMEOUT=5<br>
STRIPCHARS=("+39" "[ -]") <br>
(Removes the Italian country code prefix, spaces and - chars)