# typescript-npm-starter
Starter for TypeScript with npm


## Quick Start

```bash
# You can change app name
APP_NAME="myapp"
git clone https://github.com/nwtgck/typescript-npm-starter.git $APP_NAME
cd $APP_NAME
rm -rf .git
sed -i '' "s/typescript-npm-starter/${APP_NAME}/" package.json
sed -i '' "s/Starter for TypeScript with npm/${APP_NAME}/" package.json
echo -e "# $APP_NAME" > README.md
sed -i ''  "s/2020/$(date -u "+%Y")/" LICENSE
npm i # to install and overwrite "name" in package-lock.json
```
