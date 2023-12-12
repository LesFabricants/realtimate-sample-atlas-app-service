# Sample Atlas App

> This is a demo of an atlas app converted and using `realtimate`


## To Create this Repo the following steps were used

- Create a default atlas appservice folder: `appservices apps init -n sample`
- Install typescript and init the project
- Install realtimate

Now you can use the build and run command:

- Build: `npx realtimate build --souce src/ --destination .` this will build a js for each typescript file in src
- Run:  `npx realtimate run` this will emulate atlas app services in your local environement. You can use the `--uri` to specify a mongodb uri to use (or use the `.env` file)
- Watch:  `npx realtimate watch -M` this will build and run the app