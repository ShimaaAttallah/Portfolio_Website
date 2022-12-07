# Portfolio_Website
Freelance React Project 


####Backend

## cd Backend_Sanity
1- npm install -g @sanity/cli
2- npx @sanity/cli init
3- entre ((google))
4- Project name: Portfolio
5- entre ((Select project template Clean project with no predefined schemas))

## To run Backend_Sanity (run Sanity Studio)
npx @sanity/cli start   ----- http://localhost:3333

Other helpful commands
npx @sanity/cli docs - to open the documentation in a browser
npx @sanity/cli manage - to open the project settings in a browser
npx @sanity/cli help - to explore the CLI manual



####Frontend
cd ..
## cd frontend_portfolio
1- npm install @sanity/client @sanity/image-url framer-motion node-sass react-icons
2- npm install react-tooltip

####Deployment
1- Make sure you stop the backend server
2- cd frontend_portfolio
3- npm run build
4- Open(https://app.netlify.com/sites/saiedattallah-portfolio/settings/domain)
5- (frontend_portfolio..build..Reveal in File Explore.. then(drop it in website))

####6---- when you Finish deploy

7- cd ..
8- cd Backend_Sanity
9- npx sanity manage "to open automatic" (https://www.sanity.io/manage/personal/project/hqanrzb6)
10-  chooze (API Section) (https://www.sanity.io/manage/personal/project/hqanrzb6/api)
11- Copy URL (the website deployment)
12- +Add CORS origin -- (origin add url in)+(chooze the checkbox) -- then (save)
13- then reload (the URL website deployment)
-----------------------------------------------------------------------------------
https://www.sanity.io/
https://create-react-app.dev/docs/deployment/
#edf2f8