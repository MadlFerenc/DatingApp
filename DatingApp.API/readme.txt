Node.js - JAvaScript runtime

[Route("api/[controller]")] --> attribute based rooting
dotnet watch run - autocompile after changing the code
in a class prop 2xTAB generate code
CTRL + . --> code gen recommandation eg. generateing contructor

DataContext added as a service in Startup.cs --> service.AddDbContext(...

dotnet tool install --global dotnet-ef

migration (code first)
dotnet-ef migrations add InitialCreate
	needed: nuget package install: Microsoft.EntityFrameworkCore.Design
Done. To undo this action, use 'ef migrations remove'

dotnet-ef database update --> datingapp.db created

inject datacontract
----------------------------------------
Angular  (without analytics: ng analytics off)


npm install -g @angular/cli
ng new DatingApp-SPA
cd DatingApp-SPA
ng serve --> starts the angular application

decorator: add angular features to a component
main.ts responsible for bootstrapping
app.component.ts provides data 
app.component.html is the view for the data
index.html is now a single page app
webpack compiles code into javascript, injects codes
typescript --> javascript --> injected into index.html

visual code extensions for typescripts
- angula snippets (John Papa)
- angular files (Alexander Ivanichev)
- angular language service
- Auto rename tag
- Bracket Pair Colorizer 2
- Debugger for Chrome
- Material Icon Theme
- Prettier - Code formatter
- TSLint Microsoft
- angular2-switcher (switch filetypes with alt-o)

changes:
app.module.ts
- import { HttpClientModule }

src/app right-click - generate component: value -->
value.component.ts 
- OnInit interface - right place for injection, subscribe of observable necessary
- change getValue()

run http://localhost:4200/ --> error: .... blocked by CORS policy (port 5000 <--> port 4200 )
--> send addition header in order the client can trust the server

*ngFor - * is a structional directives modifies the DOM

Bootstrap: the most popular CSS-framework

we don't want to install jQuery into our application, not recommanded, use angular component
(is another big javascript library)

npm install bootstrap font-awesome
importing bootstrap-stylesheet into the global src/styles.cs

git-scm.com --> download git
delete .git directory in C:\Feri\ELearn\Agnular+NetCore\DatingApp-SPA
cd C:\Feri\ELearn\Agnular+NetCore
git init







