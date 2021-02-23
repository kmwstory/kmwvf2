# vf2

vue&firebase 2

<<<<<<< HEAD
# install

## firebase use

```bash
$ firebase login # If you are not logged in
$ firebase use --add
? Which project do you want to add? xxx-site
? What alias do you want to use for this project? (e.g. staging) default

Created alias default for xxx-site.
Now using alias default (xxx-site)
=======
### Compiles and hot-reloads for development
```
npm run serve
```
```bash
$ firebase functions:config:set admin.email=xx@abc.com admin.db_url=https://xxx-site.firebaseio.com
$ firebase functions:config:set admin.email=xx@abc.com admin.db_url=https://xxx-site.firebaseio.com admin.region=asia-northeast1 admin.bucket_url=memi-vf2.appspot.com
```
### Compiles and minifies for production
```
npm run build
>>>>>>> 7b22680fc0e450467a2c90f04ef70f63764c0764
```

## functions

### key download

functions/key.json download from console service account key

### setting

```bash
$ firebase functions:config:set admin.email=xx@abc.com admin.db_url=https://xxx-site.firebaseio.com admin.region=asia-northeast1 admin.bucket_url=memi-vf2.appspot.com
```

## hosting

### Dependecies install

Dependencies installation

```bash
$ yarn # front-end install
$ cd functions && yarn # back-end install
$ cd ..
```

### firebaseConfig file make

make file on root

**./firebaseConfig.js**  
```javascript
export default {
  apiKey: "AIzaSyCMJGWDiuiV91DQOqscCXiVTf2iVNHQXXX",
  authDomain: "xxx-site.firebaseapp.com",
  databaseURL: "https://xxx-site.firebaseio.com",
  projectId: "xxx-site",
  storageBucket: "xxx-site.appspot.com",
  messagingSenderId: "654047601333",
  appId: "1:654047601222:web:8fcdc5ea4091ec77064111",
  measurementId: "G-Z05F3DT444"
}
```
