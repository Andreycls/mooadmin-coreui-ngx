# Mooadmin-coreui-ngx
# Views


## Form View

```html
<moo-vform model="Models.Student">
    <moo-field name="Email" edit-widget="bootstrap.email" help="We'll never share your email with anyone else." />
    <moo-field name="Password" edit-widget="bootstrap.password" />
    <moo-field name="Check1" edit-widget="bootstrap.checkbox" />

    <button type="submit" class="btn btn-primary">Submit</button>
</moo-vform>
```

Render Result

```html
<form>
  <div class="form-group">
    <label for="Email">Email address</label>
    <input type="email" class="form-control" id="Email" aria-describedby="Email-emailHelp" placeholder="Enter email">
    <small id="Email-emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
  </div>
  <div class="form-group">
    <label for="Password">Password</label>
    <input type="password" class="form-control" id="Password" placeholder="Password">
  </div>
  <div class="form-check">
    <input type="checkbox" class="form-check-input" id="Check1">
    <label class="form-check-label" for="Check1">Check me out</label>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>
```


## Field Components

#### Textbox : Text | Numeric | Autocomplete

#### Combobox : Dropdown

#### Checkbox

#### Radio

### Validation

### Properties

### Methods

### Events


## List View

```html
<moo-vlist model="Models.Student">
  <moo-item-template>
    <div class="card" style="width: 18rem;">
      <img class="card-img-top" src="{{model.ImageUrl}}" alt="Card image cap"/>
        <div class="card-body">
          <h5 class="card-title">{{model.FullName}}</h5>
          <p class="card-text">{{model.Description}}</p>
        </div>
    </div>
  </moo-item-template>
</moo-vlist>
```

Render Result

```html


```

### Pagination

> https://ng-bootstrap.github.io/#/components/pagination/api

### Sorting

### Filter

### Properties

### Methods

### Events


## Table View

```html
<moo-vtable model="Models.Student">
    <moo-column name="Email"  />
    <moo-column name="FirstName" />
    <moo-column name="LastName" />
</moo-vtable>
```

### Pagination

> https://ng-bootstrap.github.io/#/components/pagination/api

### Sorting

### Filter

### Properties

### Methods

### Events



## Chart View

> http://www.chartjs.org/docs/latest/

### Properties

### Methods

### Events


## Report View

Pivot Table

### Properties

### Methods

### Events


## Layout

### Grid
