to create new ng5 project
ng new NAME --style=scss --routing

to create new component
ng g c NAME
shortcuts (g - generate, c - component)

Interpolation and prop binding
value="{{ something}}" equals to [value]="something"

usually we want to add FormsModule to app.component, because we want to use ngFor or something like this

To set two-ways data-binding we use [(ngModel)] -> ex. <input type="text" class="txt" name="item" placeholder="Life goal.." [(ngModule)]="goalText" />
