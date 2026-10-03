JEFFREY is a WiFi-controlled six-wheeled surveillance rover built on NASA's
Rocker-Bogie suspension system. The rover is designed to navigate rough, uneven, and
obstacle-laden terrain that conventional wheeled robots fail on. The mechanical chassis is
constructed from PVC pipes and ACP sheet, employing a passive differential Rocker-Bogie
linkage that keeps all six wheels in constant contact with the ground without any springs or
active actuators. The electronics system comprises an Arduino WiFi board as the main
controller, three L298N dual H-bridge motor drivers, six 12V DC geared motors operating via
skid-steer drive, and an ESP32-CAM module for live video streaming. Control commands are
sent wirelessly from a smartphone or laptop browser over WiFi, providing real-time operator
feedback. The prototype was successfully tested on paved concrete, tiled surfaces, and platform
steps, achieving chassis tilt variance as low as ±0.07°, body stability of 0.050σ, and successful
obstacle clearance. This report documents the design, fabrication, circuit implementation,
testing results, and future enhancements planned for the system.
