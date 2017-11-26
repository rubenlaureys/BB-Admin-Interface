# BB-Admin-Interface

Navigate into your MagicMirror's modules folder and run:

git clone https://github.com/rubenlaureys/BB-Admin-Interface.git

Install the dependencies:

cd BB-Admin-Interface && npm install --only=production

Add the module to you config.js:

    {
    	"module": "BB-Admin-Interface"
    },
    
Whitelist the devices you want to access the mirror's settings from. If you want to whitelist all devices on your local network add:
   
   ipWhitelist: [""127.0.0.1", "::ffff:127.0.0.1", "::1", 192.168.X.1/24 , ::ffff:192.168.X.1/24"], 

Make sure you replace X with the correct number! you can find it by running ifconfig in your mirror.
