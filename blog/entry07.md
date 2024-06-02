# Entry 7
##### 5/30/24

### Content

When I started working the actual freedom project, I had faced many challenges and was very lazy to do some things on it. My challenges were the formatting, sizing, and positioning. My takeaways doing the project were to resize and reposition the bootstrap card and carousel. After I finished the project, in class, my classmates and I were presenting our projects. My challenges were going up in front of the class and presenting. I'm a very shy person when it comes to going in front of a whole crowd of people. It was also how I was speaking; I was stammering and very nervously laughing while I was sharing. My takeaways during the in-class presentation were that everyone got to see what my project is, and they've learned about Chemistry. My peers were asking me questions about my project, and told them what it was. My takeaways from my Expo Elevator Pitch were that people who saw my project were interested and learned about Chemistry if they've never heard of it.

### Sources

[Notes (See Unit 4: Freedom Project and scroll until you see Elevator Pitch)](https://docs.google.com/document/d/1icQfpV5FxfnhODN3vSfDY5Hj67FRzxyDr_KfMHsnf-U/edit?pli=1#heading=h.6o1f62qg6jz9)

[My in-class presentation](https://docs.google.com/presentation/d/1sRNbAjOSi28nGCysF9LI3-UKwhzUebYGTsW0i4C6cBs/edit#slide=id.p)

### Engineering Design Process

At this time when I was finishing the final parts my Freedom Project, I was at the point where I was sharing my results with many different people around the school. My plans for the next stage are to be more fluent with what I'm talking about and to be less shy. I can introduce myself by saying my name first before going over the product, and end with a "Thank You".

### Skills

For this freedom project, the skills I used were collaboration, communication, debugging, how to google, growth mindset, attention to detail, consideration, and creativity.

Using consideration, creativity, and attention to detail, I first considered the freedom project was gonna be see by other poeple. I payed attention to what I was doing and how I was organizing the codes and CSS. I was experiencing a lot of issues with the outputs of the codes and CSS. They were coming out huge and mispositioned, and I had to make many revisions, which I also had issues with. So using collaboration, I asked my peers, teacher, and on slack for assistance. Using debugging, I was able to find the mistakes in my CSS, and finally got the right help to fix them. I googled my issues too, and got help from the results I was given.

### Professionalism

When doing this freedom project, I learned how to create my own website using bootstrap.

**Navbar**

```HTML
<nav class="navbar bg-body-tertiary">
  <div class="container-fluid">
    <span class="navbar-brand mb-0 h1">Navbar</span>
  </div>
</nav>
```

**Card**

```HTML
<div class="card" style="width: 18rem;">
  <img src="..." class="card-img-top" alt="...">
  <div class="card-body">
    <p class="card-text">Card</p>
  </div>
</div>
```

**Accordion**

```HTML
<div class="accordion" id="accordionExample">
  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
        Accordion Item #1
      </button>
    </h2>
    <div id="collapseOne" class="accordion-collapse collapse show" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the first item's accordion body.</strong> It is shown by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
        Accordion Item #2
      </button>
    </h2>
    <div id="collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
```

**Carousel**

```HTML
<div id="carouselExample" class="carousel slide">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="..." class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="..." class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="..." class="d-block w-100" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
```
