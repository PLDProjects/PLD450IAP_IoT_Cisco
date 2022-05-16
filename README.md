# PLD450IAP_IoT_Cisco

The project is to use IoT technologies to track information on a website. Initially the idea was to use RFID tags but after considerable research I settled on BLE tags for increased range and lower cost. The project deliverables will be an automatic pet door installed and triggered by BLE tags on dog collars or manually via web interface. The door triggers will be logged in a database with distance information made available via web interface. There will be far more potential with the platform setup for adding more devices such as cameras, microphones, audio output from triggers and more. 

Hardware 
i.	Raspberry PI 3 mini computer to act as server.
ii.	Universal power retractable radio antenna to power door.
iii.	4 channel 5V relay module to build H bridge motor controller.
iv.	Breadboard kit and wires.
v.	Micro roller arm limit switches.
vi.	Pet door with security panel to act as automatic door.
vii.	Tile mate Bluetooth tags and silicone protectors.
b.	Software
viii.	Latest Raspian OS for Pi.
ix.	Node-Red software for logic and controls. (Several packages for needed nodes)
x.	InfluxdB for database.
xi.	Grafana Data Visualization software. 
xii.	NGINX web server.
xiii.	Remote.it account and software for remote access.
