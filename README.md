# destilifes
CMS built on Node.js with a noSQL backend.

Primary focus will be a framework for the display and management of the web applications of Joseph Montgomery and Steven Rose. 

Secondary focus will include the ability to manage other content including images, videos, and audio.

DESCRIPTION:

Site will be a minimal responsive layout meant to display content with many variables. Goal is to create something that will manage various web applications and store appropriate data for each application. 

Each site branched off of this build will begin with a home page. The home page will contain a blog or text page containing the manifesto or statement or musings of the artist. This page should be able to handle in-line images as well. 

CONTENT AND MENUS
Content will be stored in "flat-files." An administrator will be able to activate each flat-file drawer using queries. Queries will be based primarily on, but not limited to, taxonomy. Objects can be individually eliminated and arranged from queries.

The user will design the menu view based on the query results and number of queries they intend to use. 

Example 1. The following describes a project site for the early stages of destilifes.com where each PROJECT is a different web application: HOME | PROJECT 1 | PROJECT 2 | PROJECT 3| PROJECT 4 | CONTACT

Example 2. The following describes the menu of a project site in the mature stages of destillifes.com where, along with PROJECTs, the authors wish to have other content queries (drawers) represented: 
HOME | PROJECTS : Project1 Project2 Project 3  | SCHEMATICS : Project1_Drawings Project2_Sitemap | CONTACT

CONTENT FIELDS
Text-Body: Date, Author, Image
Project: Project Title, ProjectBrief (description of project approx. 100 words), assets (see Images, Audio, Video, Web application)
Web application: ProjectBrief, description <taxonomy: title, date>, AJAXed inline application
Images: Project Title (parent), ProjectBrief (parent), description <taxonomy: title, date, medium, dimensions>, Image, Thumb (optional)
Audio: Project Title (parent), ProjectBrief (parent), description <taxonomy: title, date, medium, dimensions>, Embedded content
Video: Project Title (parent), ProjectBrief (parent), description <taxonomy: title, date, medium, dimensions>, Embedded content





