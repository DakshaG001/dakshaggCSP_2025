---
layout: page
title: About 
permalink: /about/
---

<style>
h1 {
  font-size: 40px !important;
}
h2 {
  font-size: 40px !important;
}
h3 {
  font-size: 40px !important;
}
h4 {
  font-size: 30px !important;
}
h5 {
  font-size: 30px !important;
}
p {
  margin-top: 50px;
  margin-bottom: 100px;
  margin-right: 150px;
  margin-left: 30px;
  font-size: 13px;
}
</style>

<h3>A lil about me</h3>

<div> 
        <ul>
            <li>I'm Daksha Gowda.</li> 
         </ul>
         <img src="../images/notebooks/Screenshot 2024-08-07 150835.png" alt="Image" width="25%" style="float: right; margin-right: 200px; margin-top: -25px">
         <p style="font-size: 16px;">Pic of my dog on the right -></p>
        
</div>


<h1>Where have I lived?</h1>

<div> 
    <ul>
        <li>I've lived in only two states, California and Washington.</li>
        <li>I lived in Washington for about 4 years, and have spent the last 12 years in California.</li>
    </ul>
</div>


<style>
   
</style>

<script>
    
    var container = document.getElementById("grid_container");

    
    var living_in_the_world = {
        {"flag": "Flag_of_California", "time_lived": "California - 12 years and counting"},
       {"flag": "Flag_of_Washington", "time_lived": "Washington - 4 years"},
    }; 
    
   
    for (var row of living_in_the_world) {
      
    }
</script>

<style>
    .grid-container {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
        gap: 10px;
    }
    .grid-item {
        text-align: center;
    }
    .grid-item img {
        width: 100%;
        height: 100px; 
        object-fit: contain;
    }
    .grid-item p {
        margin: 5px 0; 
</style>

<div class="grid-container" id="grid_container">
</div>

<script>
   
    var container = document.getElementById("grid_container"); 

    
    var http_source = "https://upload.wikimedia.org/wikipedia/commons/";
    var living_in_the_world = [
        {"flag": "0/01/Flag_of_California.svg", "description": "California - 12 years and counting"},
         {"flag": "5/54/Flag_of_Washington.svg",  "description": "Washington - 4 years"},
    ]; 

   
    for (const location of living_in_the_world) {
      
        var gridItem = document.createElement("div");
        gridItem.className = "grid-item";
        
        var img = document.createElement("img");
        img.src = http_source + location.flag; 
        img.alt = location.flag + " Flag"; 

      
        var description = document.createElement("p");
        description.textContent = location.description; 

       
        var greeting = document.createElement("p");
        greeting.textContent = location.greeting;  
       
        gridItem.appendChild(img);
        gridItem.appendChild(description);
        gridItem.appendChild(greeting);

     
        container.appendChild(gridItem);
    }
</script>

<h2>Why did I choose this course?</h2>

<div> 
    <ul>
        <li>I chose this course to develop skills that will definitely help me in the future, coding. </li>
        <li>I also chose this course because its an AP course and to really just challenge myself.</li>
    </ul>
</div>

<h4>My life in a hopefully understandable nutshell</h4>

<div> 
    <ul>
        <li>Spent the first 4 years of my life living in Everett, Washington </li>
        <li>Around 5yrs I moved to a place near chula vista where I stayed for a year or two</li>
        <li>Then I moved to Chula Vista where i stayed there till 2018</li>
        <li>During that time I went to two schools, The main public one, and a private school (I think was called Bonita Christian)</li>
        <li>During the end of 4th grade, or in 2018, I moved to 4s Ranch where I currently live</li>
        <li> I went to SRES there and OVMS, and now my third year as a junior in HS</li>
        <li>Fun fact: I skipped a grade in elementry school, which I kinda wish I didn't bc I'm usually the youngest in my class but idrc</li>
    </ul>
</div>

<h5>Thanks for reading if u did</h5>

<div>
    
    <p style="font-size: 40px;">SIUUUUUUUUUUUUUUUUUUUUUU</p>
   <img src="../images/notebooks/raf,360x360,075,t,fafafa_ca443f4786,u10_processed.jpg">
</div>




