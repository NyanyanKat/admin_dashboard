Install app:
npm create refine-app@latest client
npm install apexcharts react-apexcharts

To get Google client id:
Go to console.cloud.google.com
create new project => select project => navigation menu => api & services => Oauth consent screen
=> choose external => enter app name => fill in project name and email => click next to summary
Go to credentials => create credentials => select OAuth client ID => choose web application =>
Authorized Javascript origin: http://localhost:3000 and http://localhost
Redirect url: same as above
Copy client ID
