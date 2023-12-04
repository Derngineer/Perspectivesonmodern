<template>
    <div class="container d-flex flex-column align-items-center">

      <img id="book-image" src="/books-3mockups.png" />
      <h2 id="book-description">
        <strong>' The great mystery unveiled! '</strong>
      </h2>
  
      <div id ='book' class="side-nav d-flex flex-column align-items-center">
        <div class="first-item m-3">
          <a class="btn btn-outline-danger btn-lg rounded-0" id='nav-link' href="/" >BOOK</a>
        </div>
       
        <div class="third-item m-3">
          <a class="btn btn-outline-warning btn-lg rounded-0" id='nav-link' href="#interview" >INTERVIEW</a>
        </div>
        <div class="first-item m-3">
          <a class="btn btn-outline-info btn-lg rounded-0" id='nav-link' href="#order" >BUY NOW</a>
        </div>
        <div class="third-item m-3">
          <a class="btn btn-outline-warning btn-lg rounded-0" id='nav-link' href="#author">WRITER</a>
        </div>
        <div class="third-item m-3">
          <a class="btn btn-outline-secondary btn-lg rounded-0" id='nav-link' href="#talk">CONTACT US</a>
        </div>
      </div>
  
      <div class="container-fluid text-center">
        <div class="bottom-footer">
           &copy; Perspectives on modern marriages 2023
        </div>
      </div>


    <div class="row">
      <a href="#" class="fa fa-facebook"></a>
      <a href="#" class="fa fa-twitter"></a>
      <a href="#" class="fa fa-instagram"></a>
      <a href="#" class="fa fa-youtube"></a>

    </div>
  
    </div>
  </template>
  
  
  <script>
  export default {
    name:'NavBar'
    
  };
  </script>

  <style scoped>
  /* Adjust styling as needed */
@import url(https://fonts.googleapis.com/css?family=Poiret+One|Lobster|Anton|Shadows+Into+Light|Open+Sans|Roboto|Orbitron|Oswald|Raleway|Montserrat|Roboto+Slab|Indie+Flower|Fjalla+One|Bree+Serif|Pacifico|Abril+Fatface);
.container {
/* background: linear-gradient(to bottom, white, #f0f9ff); */
/* box-shadow: 0 4px 8px rgba(0, 0, 0, 0.4); */
/* border-right: 1px solid rgb(169, 169, 169); */
position: fixed;
color: black;
margin: 0;
width: 50%; 
/* this needs to be changed */
height: 100%;
.side-nav {
    /* padding-left: 200px; */
    font-family: Poiret one;
    font-size: 18px;
    justify-content: center;
    align-items: center;
}

#book-image {
    margin-top: 0px;
    height: 300px;
    width: 400px;
}

#nav-link {
    width: 150px;
    font-size: 18px !important;


}
#book-description {
    font-family: Great Vibes;
    text-align: center;
    font-size: 40px;
}
.container-fluid {
  /* min-height: 100vh;  */
  width: 100%;
  flex-direction: column;
}
.bottom-footer {
    margin-bottom: 5px;
    font-family: Poiret one;
    /* background-color: black; */
    color: rgb(49, 49, 49);
    text-align: center;
}
}

.fa {
  padding: 20px;
  font-size: 30px;
  width: 100px;
  text-align: center;
  text-decoration: none;
  margin: 5px 2px;
}

.fa:hover {
    opacity: 0.7;
}

.fa-facebook {
  background: #3B5998;
  color: white;
}

.fa-twitter {
  background: #55ACEE;
  color: white;
}
.fa-linkedin {
  background: #007bb5;
  color: white;
}

.fa-youtube {
  background: #bb0000;
  color: white;
}

.fa-instagram {
  background: #125688;
  color: white;
}



  </style>
  