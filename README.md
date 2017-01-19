# psa2funda
##17. Going to Production
###3 Linting with TSLint
```
npm install tslint --save-dev
```
if not installed globally
```
node_modules/.bin/tslint --init
```
if not
```
tslint --init
```


###4 Tuning Your rxJS Requests
create rxjs-extension.ts
```
import 'rxjs/add/observable/of';
import 'rxjs/add/observable/throw';
import 'rxjs/add/observable/catch';
import 'rxjs/add/observable/do';
import 'rxjs/add/observable/map';
import 'rxjs/add/observable/filter';
```
