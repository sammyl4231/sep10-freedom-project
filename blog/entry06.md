# Entry 6
##### 5/1/24

### How I made my MVP

My MVP was made of my chosen topic of Chemistry. I made my own custom chemistry website called [Chemistry Crocodile](https://github.com/sammyl4231/sep10-freedom-project/blob/main/index.html), where he tells you parts A and B of what I researched about Chemistry. I used 2-3 BootStrap components to organize the details. It took me a lot of thinking to figure out how to arrange everything. It came out a little misorganized, but at least I got all the must-haves for this assignment.

### Challenges and Takeaways

I faced many challenges when I was doing this assignment. They were using the most organized components and organizing them in the right spots along with the details. I also struggled with using the fonts, they wouldn't work properly when i put them into the [style.css](https://github.com/sammyl4231/sep10-freedom-project/blob/main/style.css). A bigger challenge I faced doing this was uploading the preview onto the google classroom assignment. Whenever I typed in the example link from the assignment, using my GitHub username, it would always bring me to my portfolio.

### The Bootstrap components I used:

Navbar

```HTML

<nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dropdown
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" aria-disabled="true">Disabled</a>
        </li>
      </ul>
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>

```

Card

```HTML

<div class="card" style="width: 18rem;">
  <img src="..." class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>

```

Sub Navbar

```HTML

<!-- As a heading -->
<nav class="navbar bg-body-tertiary">
  <div class="container-fluid">
    <span class="navbar-brand mb-0 h1">Start exploring!</span>
  </div>
</nav>

```

Accordion

```HTML
<div class="accordion" id="accordionExample">
  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
        What is Chemistry?
      </button>
    </h2>
    <div id="collapseOne" class="accordion-collapse collapse show" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>Chemistry Crocodile: What's Chemistry you ask? Great question! Allow me to explain!</strong> Chemistry is the study of chemicals. It is used everyday in our lives for certain utilities and needs. Chemistry is found in machines, substances, elements, etc. There are calculations of measurement, atoms, ions, etc, and identifications of elements. The Periodic Table is an important prop of Chemistry, chemists use them for experiments and tests to see if they change color, feel hot, or interact in many different ways. Chemists use a hotplate to heat samples of substances to see if they change color or react in a certain way.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
        Chemistry over the years
      </button>
    </h2>
    <div id="collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>Chemistry Crocodile: Chemistry has been around for centuries. Let me explain to you what has happened during that time.</strong> Chemistry has been around from the 16th-17th centuries. Over the centuries, many builders have constructed many devices that are being used throughout history and today. These machines have supplied us with our needs and have really changed things throughout history. Scroll down to view some Chemistry machinery that has been around during these centuries.
      </div>
    </div>
  </div>



  <div class="accordion" id="accordionExample">
    <div class="accordion-item">
      <h2 class="accordion-header">
        <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
          Compressor
        </button>
      </h2>
      <div id="collapseOne" class="accordion-collapse collapse show" data-bs-parent="#accordionExample">
        <div class="accordion-body">
          <strong></strong> A compressor is a tool powered by chemistry. Compressors are a mechanical device used to increase the pressure of gas. Compressors increase the pressure of gas by reducing its volume. They force atmospheric air under pressure to create potential energy, and then convert it to kinetic energy. That's when the compressed air is released, and pressure builds up.
        </div>
      </div>
    </div>
    <div class="accordion-item">
      <h2 class="accordion-header">
        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
          Absorption Tower
        </button>
      </h2>
      <div id="collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
        <div class="accordion-body">
          <strong> An absorption tower is a large tank for absorbing gases. It allows gaseous phases pass into a liquid phase. Aditionally, chemists use an adsorption column. An adsorption column is when particles stick to a solid substance’s surface without going through it, it stays there with intermolecular forces. Adsorptions are concentrations in fluid phase and solid adsorbent change overtime and their position in the fixed bed, as adsorption proceeds.
        </div>
      </div>
    </div>
    <div class="accordion-item">
      <h2 class="accordion-header">
        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
          Agitated Vessels
        </button>
      </h2>
      <div id="collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
        <div class="accordion-body">
          <strong> Agitated vessels exchange heat and are mostly used in lots of chemical and biochemical process industries. The mass transfer for the most part involves dispersed gases absorbing into and often reacting with an ongoing liquid phase. The agitator is driven by an electric motor, rotating the impellers within the vessel. It facilitates mixing and blending.
        </div>
      </div>
    </div>
    <div class="accordion-item">
      <h2 class="accordion-header">
        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
          Centrifuge
        </button>
      </h2>
      <div id="collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
        <div class="accordion-body">
          <strong> Centrifuges apply a sustained centrifugal force - due to rotation. Centrifuges are used to separate liquids/fluids and gases, depending on their density. They rotate at rapid speeds, which separte substances using the power of centripetal force. The applied force can even several hundred to thousand times of Earth's gravity!
        </div>
      </div>
    </div>

```

### Engineering Design Process

My problems were trying to create a fourth accordion or carousel item. The problem(s) I defined was carousel at first, but it didn't work out as I expected. Another issue I defined was uploading the preview. I also couldn't submit the right github link to the preview. I tried asking on slack to resolve my problem, but I didn't get the right assistance and I was still confused. So I didin't really find an answer. So the most promising solution that was best for me was to just submit the psychic-lamp link of the preview, even though its server stops working after a short amount of time. My next step starting the upcoming Monday, 5/6/24, my classmates and I will be evaluating on each others' custom websites. We'll give each other feedback and go over the basics of our websites.

### Skills

Some skills I used doing this project were debugging, problem decomposition, collaboration, growth mindset, consideration, attention to detail, and time management. Debugging; I was trying to make a fourth carousel/accordion item, but kept messing up, it wouldn't work as I expected. Attention to detail; As always, I never want to make any mistakes when coding. I have made a few errors doing this with the organizing the code(s) so they come out the way I expect them to in the preview. Consideration; I'm aware that my project would be seen by other people. I was worried that if I didn't code properly, it'd look messy and unreadable, and people wouldn't want to use it.
