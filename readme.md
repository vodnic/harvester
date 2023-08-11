DeFi Harvester
==============

An idea to create a project to help me manage my DeFi positions. Currently I am
using Google Spreadsheets, but its getting cumbersome to insert manually data
and maintain the dictionaries, as well as to conduct proper analysis on these
data.

My current vision to use create a BE with DB, to hold man model all the data, with dedicated FE to visualize it all. I'd like to keep the data in DB in an easy to export format, so that if necessary, I could go back to the spreadsheets with what I've got. 

Technology wise, I think using Java in BE would make it easier for me to model domain objects as well as technically implement them. Whereas TypeScript for FE will provide me with vast options of ready to use components. I am still unsure about BE architecture, i.e. should I keep it monolith, or microservices. I see advantage for both even with such (presumably) small project. I think I'll start with monolith with clear distinction between modules. When something will grow too much, I'll just swap Java' interface to REST API.

