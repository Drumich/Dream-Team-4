https://github.com/Drumich/EDIBO/tree/master/angulartest/stuff/src/app




http://termini.lza.lv/






[Angular stuff](https://material.angular.io/components/categories)    
[Angular File Structuring Guide](https://angular.io/guide/file-structure)  
[Angular guide](https://code.tutsplus.com/tutorials/beginners-guide-to-angular-4-components--cms-29674)    
[GoJS digrams and graphs](https://gojs.net/latest/index.html)   
[QuizBucket](http://quizbucket.org/)   

```
dotnet new webapi -o MyWebApi
------------------------
in Startup.cs comment out this line "// app.UseHttpsRedirection();"
in launchSettings.json delete this "https://localhost:5001;"
--------------------------
dotnet watch run    
http://127.0.0.1:5000/weatherforecast       
curl http://127.0.0.1:5000/weatherforecast |json_pp   
--------------------------------
need to stop server every time u update a library or some shit...  (for example - ng add @angular/material  (angular material typography styles = yes ,browser animations = yes)  )   

```

[can i use?](https://caniuse.com/)    
[HTML event attributes SCRIPTS!!!](https://www.w3schools.com/tags/ref_eventattributes.asp)      
hybridapps    
[polyfills](https://en.wikipedia.org/wiki/Polyfill_(programming)) 
[w3c validator](https://validator.w3.org/)    
[Academind](https://www.youtube.com/c/Academind/videos)   
[ci/cd](https://en.wikipedia.org/wiki/CI/CD)    
[Vue.js](https://en.wikipedia.org/wiki/Vue.js)    
[free API](https://any-api.com/)    
[colors in CSS and stuff](https://developer.mozilla.org/en-US/docs/Web/HTML/Applying_color)   
var/const/closure/let   in js   
```
export NVM_DIR="$HOME/.nvm" && (
 git clone https://github.com/nvm-sh/nvm.git "$NVM_DIR"
 cd "$NVM_DIR"
 git checkout `git describe --abbrev=0 --tags --match "v[0-9]*" $(git rev-list --tags --max-count=1)`
) && \. "$NVM_DIR/nvm.sh"

//
nvm i 12
//
```


  
  

```
npm i -g @angular/cli   
ng new  
cd to the created directory   
ng add @angular/material   
cd to the created directory   
code . &    
ng serve    

```


[Solid/OOP vladilin](https://www.youtube.com/channel/UCg8ss4xW9jASrqWGP30jXiw)    

rockstar language (check on google or youtube)    

single page applications(uses js)   

ecmascript  = js    





QA - quality assurance (testētāji)  
manual test(front end)    
unitest - testē pats savu kodu)        



dev = programmētājs   
  


serverless (cloud - aws , google , azure)   

gang of four design pattern  
 
gartner hype cycle     
design pattern - bubble sort   

MVC  
(M)odel (data) ==> (C)ontroller(code) ==> (V)iew(visual)   

[WEBSTORM allegedly best IDE 5$ a month](https://www.jetbrains.com/webstorm/)  

[xnf git](https://github.com/xnf/edibo-angular)   

[plot js](https://plotly.com/javascript/)  

[run stuff from github directly](https://stackoverflow.com/questions/6551446/can-i-run-html-files-directly-from-github-instead-of-just-viewing-their-source)  



```
in app.module.ts copy this code>>> 
import {MatIconModule} from '@angular/material/icon'; 

and MatIconModule goes in imports: [
like this     >>>         MatIconModule,
                          something
                          ]
```




kiss = keep it simple  
yagni = you aint gonna need it  
dry = dont repeat yourself  

[ci/cd](https://en.wikipedia.org/wiki/CI/CD)  

```
ng g m currency , ng g c currency , ng g s currency
```



```
import { CurrencyModule } from './currency/currency.module'; (from ./currency/.... means that you can find this on src/app/currency!!!)
add to imports CurrencyModule
```
