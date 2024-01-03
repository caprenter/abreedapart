---
layout: default
title: Home
content-description: "A Breed Apart Tattoo Studio, Bingley, West Yorkshire, Established in 2010, Specialising in Black and grey realism."
open-today-message: "Bookings now available for February to March. email; abreedapart1@gmail.com"
---  

<div class="main-image" markdown="1">
  ![A Breed Apart](assets/images/main_image.jpg){:class="img-responsive"}
</div>


<div class="main">
  <div class="container">
  
   {% if page.open-today-message %}
    <div class="open-today">
      <p>{{ 'now' | date: "%a %-d %B %Y" }}</p>
      <p>{{ page.open-today-message }}</p>
    </div>
    {% endif %}

    <section class="row">
      <section class="col">
        
        <p class="motto">2 Market Street, Bingley, BD16 2HP (<a href="https://goo.gl/maps/Z9bwGwjgDTJQgJ5M6">map</a>)</p>
        <p class="motto">
          Local Health Authority Registered<br>
          Class S Vacuum Autoclave Sterilisation
        </p>
        
        <p class="motto" markdown="1">Tattoo Enquiries:<br>
        <i class="far fa-envelope"></i> [{{site.email}}](mailto:{{site.email}})<br>
        <i class="fas fa-phone"></i> 01274 568415</p>
        
      </section>
    </section>


    
    
  </div>
</div>
