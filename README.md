# cuyacourts_api
An API that provides read access to Cuyahoga County's criminal court docket scraped by https://github.com/nmolivo/case_scrape.


Objectives: education on topics of architecture, security, CI/CD, and the Flask framework. 

***

For any questions regarding the legality of sharing this data, please see the following resources
-  [South Carolina State Conference of the NAACP v. Kohn et. al](https://unicourt.com/case/pc-db5-south-carolina-state-conference-of-the-naacp-v-kohn-et-al-1168729) Where the ACLU represented the NAACP and asserted that South Carolina’s blanket ban on court data scraping violates the First Amendment by “restricting access to, and use of, public information, and prohibiting recording public information in ways that enable subsequent speech and advocacy.” [Read More here.](https://unicourt.com/blog/naacp-v-kohn/)
- The Marshall Project, a non-profit organization scrapes the same data as this project, with the objective to support journalism. Presented at Data Days Cleveland 2022. [Read More here.](https://www.themarshallproject.org/2022/01/07/why-we-re-investigating-the-cuyahoga-county-court-system)

***

Welcome to my first flask app. It's really early in development but here are the desired features.

- Endpoints for each table scraped
- Gallery page
- Secure read-only access 
- User authentication/authorization

Inspired by: 
- [RNAcentral](https://rnacentral.org/help/public-database)
- [CaseLaw](https://case.law/)

Following these tutorials:
- [Flask and DB Connections](https://flask.palletsprojects.com/en/0.12.x/tutorial/dbcon/)
- [More Flask and DB Connections](https://www.geeksforgeeks.org/connect-flask-to-a-database-with-flask-sqlalchemy/)
- [Flask and Swagger]()
