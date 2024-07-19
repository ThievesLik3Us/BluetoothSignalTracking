# SigMon - Bluetooth Signal Monitoring for Device Location Tracking

Bluetooth signal tracking tool that uses the signal strength to determine a devices GPS location.

This project uses the signal strength from 3 seperate raspberry bluetooth devices and performs trilateration to determine external bluetooth devices GPS locations.

The goal was to demonstrate that you can track a device's location in areas where GPS does not work well such as tracking indoors. It uses a rough distance measurement from each of the 3 devices to come up with a likely device location. The output of the system is device's locations tracked over time plotted onto a google maps web interface so you can see things such as crowd traffic in a restaurant or patterns of traffic through a busy area. This is also a private and anonymous way to track people and crowds without receiving personal information from them.

This project was a senior design project and won't be maintained.

