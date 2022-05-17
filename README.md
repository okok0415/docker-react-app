docker run -it -p 3000:3000 -v /user/src/app/node_modules -v ${pwd}:/usr/src/app okok0415/docker-react-app


1.  "start": "$(npm bin)/react-scripts start", package-lock.json 지우고 다시 npm install 
2.  ENV CHOKIDAR_USEPOLLING=true 이후 재 빌드