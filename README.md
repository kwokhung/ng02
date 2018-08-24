ng new ng02
ng serve
ng serve --port=4201
ng build
ng build --prod
ng test
ng e2e
ng help

1. Init Repo (VSCode)

2. Create Repo (GitHub REST API)
-> curl -u 'kwokhung' https://api.github.com/user/repos -d '{"name":"ng02"}'

3. Remote Add Origin
-> git remote add origin https://github.com/kwokhung/ng02

4. Push Origin Master
-> git push -u origin master

npm install --save @capacitor/core @capacitor/cli
npx cap init
npx cap init ng02 com.mblinus.test
npx cap add android
npx cap open android
