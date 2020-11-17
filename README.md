# Make a Mobile Version

## Instructions

This web page uses Bootstrap, but not very well.

Your challenge is to make the page tablet/phone friendly:

1. When the viewport is large width or wider, all column widths should stay the same as they are now.
2. When the viewport is any more narrow than that, all columns should be full-width (12 out of 12 grid units)

### If You Have Time

1. See if you can turn the 2 columns in the second row in to Bootstrap cards: https://getbootstrap.com/docs/4.0/components/card/
2. See if you can use Bootstrap to create a form to collect email addresses.  You just need to create the UI - the form doesn't need to actually submit anything: https://getbootstrap.com/docs/4.0/components/forms/

CARD EXAMPLE FROM SOURCE ABOVE
<div class="card" style="width: 18rem;">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="card-link">Card link</a>
    <a href="#" class="card-link">Another link</a>
  </div>
</div>

FORM EXAMPLE FROM COURSE ABOVE
<form>
  <div class="form-group">
    <label for="exampleInputEmail1">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
    <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
  </div>
  <div class="form-group">
    <label for="exampleInputPassword1">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
  </div>
  <div class="form-check">
    <input type="checkbox" class="form-check-input" id="exampleCheck1">
    <label class="form-check-label" for="exampleCheck1">Check me out</label>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>