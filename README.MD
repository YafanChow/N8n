<h1>N8N Football Bot project</h1>
In this project I made a football score bot for Discord, when playing football live the scores of the football are automatically sent in the Discord chat.<br>

<h2>Setup Server</h2>
<b>This are instructions to setup and run the server:</b>
<ul>
<li>Install n8n globally use npm: npm install n8n -g</li>
<li>Press "o" to open in Browser</li>
<li>Import the file: N8N Football Bot Project</li>
<li>Click on MySQL to enter your MySQL account details </li>
<li>Then go into your mysql database and enter the following code in the query to create the database:

create table Football
(
startDate text null,
teamA json null,
teamB json null,
score json null,
id char(255) not null
primary key,
keyEventswww json null,
status char(255) null
);

</li>
<li>Get the discord webhook in your discord channel, return to the website, click discord, and enter the discord webhook you obtained. </li>
</ul>
<b>Then click execute workflow and it will automatically start sending the team's scores to discord.</b>
