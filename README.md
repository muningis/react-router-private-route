# React Router Private Route

## Example
```
<Router>
  <div>
    <PrivateRoute path="/" auth={Math.random() > Math.random()} redirect={"/login"} component={loadable(() => import("./pages/home"))} />
    <Route exact path="/login" component={loadable(() => import("./pages/login"))} />
  </div>
</Router>
```

## Readme is heavily W.I.P. ...