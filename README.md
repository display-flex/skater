# Skater

Skater is a Simple static file server.
It comes with a commandline tool to upload files from your local folders and a webinterface to manage files directly on the server.

![Alt text](/screenshot.png?raw=true "Webinterface")

### Installation
Skater is simple to use:
```
git clone https://github.com/NeumannTom/skater
cd skater
npm install
./server.js <public folder>
```

### Create a user
With the admin tool you can easily create users
```
chmod +x admin
./admin user-add --username YOURUSERNAME --password YOURPASSWORD
```

## File management

The admin interface is available under the `/_admin` location or you can upload files using the commandline tool.


## Disclaimer

Skater is a fork from surfer. A file management tool for Cloudron (System to manage cloud apps on a Linux server). The fork was created to use skater without Cloudron on a Linux system.

Surfer: https://git.cloudron.io/cloudron/surfer

Thanks to @nebulade <3 
