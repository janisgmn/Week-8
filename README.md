//HTTPS
const https = reqire("https");

const weather_homepage = https.get("https://weather.com/", (req,res) => {
	console.log("received weather response");
});

console.log("began weather request");

const gt_homepage = https.get("https://translate.google.com/", (req,res) => {
	console.log("recieved gt response");
});

console.log("began gt request");


const file_system = require("file_system");

file_system.readfile("./RESDME.md", (err,body) => {
	sonsole.log("completed reading file", body);
});

console.log("began reading file")

exports = https; 
