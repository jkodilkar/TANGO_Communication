# TANGO_Communication
Tango Device-Server and Client Communication testing and issues

This project consist of following files : 

(1) TangoDS_Comm.pdf : Testing Details and Test report on Tango Device-server and Client communication issues.

(2) TestDevice.tar.gz : Tango Device Server for the communication testing : 
  - gunzip, and untar 
  - Refer to README.server
  - Makefile : for compiling and running the server
  - TangoLib : JTango Library
  - ./TestDevice/org : Tango Device server code
  - ./TestDevice/TestDevice.xmi -- pogo file

(3) tango_client.tar.gz : Tango Client for the communication testing
  - README.CLIENT : About compiling and running the Tango Client.
  - TangoEventClient.java : Tango code with Timeout setting, comment these in case of testing for default timeout.
  - 26aug2025 : Testing Client log-files for case-1 to case 4 and images
