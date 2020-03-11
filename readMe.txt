1. We can use flow-text for p tag to use responsive font size
  <p class="flow-text">This is flow text </p>

2. Materialize breakpoints:

  small     medium        large
  600px>   600-992px        992<

3. We can use hide-on-{} to specifiy the screens to hide elements

  hide-on-small-only
  hide-on-med-only
  hide-on-large-only
  hide-on-med-and-down
  hide-on-med-and-up

4. We can use color in Materialize
(check the color page in materialize)
    <h1 class="blue darken-4">Hey Game desiners</h1>
    <h2 class="orange lighten-4">h2 Title</h2>
    <h3 class="purple darken-3 white-text">h3 Title</h3>
    <h4 class="teal darken-2 yellow-text text-lighten-3">h4 Title</h4>

5. you can use these classes to align the text
  .center-align
  .left-align
  .right-align
  .truncate (This only shows one line)

for vertical alignment:
  <div class="container grey lighten-2 box valign-wrapper">
    <h5>Vertical alignment</h5>
  </div>
valign-wrapper makes the element flex

6. You can use these classes for buttons
  .btn 
  .btn-{small,large}
  .btn-floating pulse
  waves-effect waves-light

7. using icons in materialize

  <i class="material-icons red-text">error</i>

8. cols in materialize in default take the space as their
length of their content but we can conrol this:
    <div class="row">
      <div class="col s12 m6 l4">content</div>
      <div class="col s12 m6 l4">content</div>
      <div class="col s12 m6 l4">content</div>
      <div class="col s12 m6 l4">content</div>
    </div>

9. We can give shadow to elements:

    .z-depth-{1 to 5}

10. You can make mobile and desktop menu really easy in materialize

  <nav class="nav-wraper indigo">
    <div class="container">
      <a href="#" class="brand-logo">Site Title</a>
      <a href="#" class="sidenav-trigger" data-target="mobile-links">
        <i class="material-icons">menu</i>
      </a>
      <ul class="right hide-on-med-and-down">
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">Login</a></li>
      </ul>
    </div>
  </nav>

  <ul class="sidenav" id="mobile-links">
    <li><a href="#">Home</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
  </ul>

  <script>
    $(document).ready(function(){
      $(".sidenav").sidenav();
    })
  </script>

11. You can add badge to your nav bar:
  <li><span class="badge white-text pink new">5</span></li>

12. You can use cards just like bootstrap:
    <div class="card">
      <div class="card-image"> ... </div>
      <div class="card-content"> 
        <div class="card-title"></div>
        ... 
      </div>    
      <div class="card-action"> ... </div>   /// It is like footer 
    </div>
  
13. Check Collection file for styling the collections

14. We can have modals in Materialize very easily:
  usign .modal 
        .modal-content
        .modal-footer
        .modal-trigger
  and don't forget to use jquery

15. .section class gives a little margin at the top

16. .offset-l1 class gives the column offset for large screens

17. we can use pull-l4 or push-l4 classes

18. We can have parallax very easily in materialize:
      and we have to initialize it in jquery
  <div class="parallax-container">
    <div class="parallax">
      <img src="img/street.jpg" alt="" class="responsive-img">
    </div>
  </div>

19. We can have tabs very easily in materialize:
using .tabs .tab:

  <ul class="tabs">
    <li class="tab col s6">
      <a href="#photography" class="indigo-text text-darken-4">
        Photagraphy
      </a>
    </li>
    <li class="tab col s6">
      <a href="#editing" class="indigo-text text-darken-4">
        Editing
      </a>
    </li>
  </ul>
  <div class="col s12" id="photography"></div>
  <div class="col s12" id="editing"></div>
  
20. Forms in materialize is very nice (check every element of forms)

21. We have footer-page class and inside it footer-copyright class

22. To use font awesome icons
<i class="fab fa-instagram"></i>

23. To use tooltips we use class of tooltipped and data-toolti=""
and initialize it in jquery

24. Scrollspy means when you click on certain link take you to the certain
part of the page (It is possible just by using id and a tag) but we want
to scroll to that part

just use scrollspy for different part and initialize in jquery