to create new ng5 project
ng new NAME --style=scss --routing

to create new component
ng g c NAME
shortcuts (g - generate, c - component)

Interpolation and prop binding
value="{{ something}}" equals to [value]="something"

usually we want to add FormsModule to app.component, because we want to use ngFor or something like this

To set two-ways data-binding we use [(ngModel)] -> ex. <input type="text" class="txt" name="item" placeholder="Life goal.." [(ngModule)]="goalText" />


To use animations we need to say ->
npm install @angular/animations@latest --save

By adding import { ActivateRoute } from '@angular/router' -> we give us access to route parameters. Then we need to add an instance in constructor. (check about component)

service files are generally used to make http calls or sharing data between components.

Best way to use data across different components is use rjx -> import { BehaviorSubject } from 'rxjs/BehaviorSubject'
