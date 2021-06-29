# Add Routing in Angular
# Step 1: insatll routing using this command 
**"ng generate module app-routing --flat --module=app"**
          with this command *src/app/app-routing.module.ts* (generated).
# Step 2: in app.module.ts import these files
## import{ RouterModule} from '@angular/router';
 ## import { AppRoutingModule } from './app-routing.module';   
### @NgModule({ imports: [AppRoutingModule],
 ### exports: [RouterModule],)}
 # Step 3: in app-routing.module.ts
 ## import { RouterModule, Routes } from '@angular/router';
 ### @NgModule({ imports: [CommonModule,RouterModule.forRoot(routes)])}
