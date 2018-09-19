Scyther is an open source automated tool that demonstrates the security of the protocols used on the Internet and open networks. 

You can download Scyther and get more information here.
https://www.cs.ox.ac.uk/people/cas.cremers/scyther/

# Protocol-Verification
we verify 2 protocols using Scyther.

### pw.spdl
: Scyther code for verification of communication protocol between smart phone and web server.

role P: smart phone

role W: web server

+ PW: the user’s password
+ ID: the user’s ID
+ PhoneData: data transmitted from the smartphone to the web server
+ ServerData: data trans-mitted from the web server to the smartphone
+ kir: a symmetric key exchanged using the station-to-station protocol. 

### pb.spdl
: Scyther code for verification of connection and communication protocol between smart phone and smart band.

role P: smart phone

role B: smart band

+ PhoneInfo: the smartphone identification information
+ PhoneData: data transmitted from the smartphone to the smart band
+ BandData: data transmitted from the smart band to the smartphone
+ kir: the exchanged symmetric key.
