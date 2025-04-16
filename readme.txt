Project: Vincent Inn 3D Virtual Tour
Developer: KGMediaWorks

- Contains scenes: Overview, Junior Suite, Lobby, Cafe, etc.
- Custom music and sidebar navigation included

To view the tour locally:
1. Unzip the folder.
2. Open a terminal in this folder.
3. Run: python3 -m http.server 8000
4. Open browser: http://localhost:8000

To Host the Tour on a Website:
1. Upload all files and folders from the project to your web server, maintaining the folder structure. 
2. Includes: index.html, tour.xml, tour.js, panos/, skin/, plugins/, etc.
3. Access the tour by visiting the URL where it’s hosted, such as: https://yourdomain.com/virtualtour/index.html
(If your server is configured to serve index.html as the default file, simply visiting: https://yourdomain.com/virtualtour/ will also work.)

!! Do not modify or rename tour.js or tour.xml. These files are essential for decrypting and rendering the virtual tour.