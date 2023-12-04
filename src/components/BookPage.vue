<template>
    <div class="container-fluid">
      <div class="row">
        <!-- Left Side Navbar -->
        <div class="col-md-5">
          <Navbar />
        </div>
  
        <!-- Right Side Content (Will Slide) -->
        <div class="col-md-7">
          <div class="content-wrapper ">

            <div class="row social-icons ">
              <a href="#" class="fa fa-facebook"></a>
              <a href="#" class="fa fa-twitter"></a>
              <a href="#" class="fa fa-instagram"></a>
              <a href="#" class="fa fa-youtube"></a>

            </div>
            <div class="fore-text mt-5">
              <ForeText />
            </div>
            
 
          <ArrowComponent />
          <div id="book" class="mt-5">
          <DescriptionDetail  title="About the Book📝" description ="Unlock the Secrets to Lasting Love! In a world filled with fast-paced change and modern challenges, navigating the path to a successful and fulfilling marriage can seem like a daunting task. But fear not, because ‘Perspectives on Today’s Marriage' is here to help you conquer the maze of relationships with wisdom and grace.
            This insightful and engaging book is tailored for today's young adults, offering a fresh perspective on the timeless institution of marriage. Packed with practical advice, real-life stories, and expert insights, Perspectives on Today’s Marriage' explores the dynamics of modern relationships, communication in the digital age, and the keys to building a strong and resilient partnership."
            
          conclusion="Perspectives on modern marriages by Cletus E. Matoma"

          />
        </div>
          <br>
          <br><br><br><br>  <br><br><br><br><br>
          <div id ="interview">
          <DescriptionDetail  title="Zimbabwe Broadcasting Network Interview 📹" description ="Watch ZBC interview as C.E Matoma gives insights on perspectives on modern marriages"
          conclusion="" />
          </div>
          <VideoItem />




          <br>
          <br><br><br><br>  <br><br><br><br><br>



          <div id="order">
            <DescriptionDetail id="order" title="How to buy this book 📗" description ="
          To buy the book contact us via +263772702645/+263773589924/ or email us at cletusmatoma@gmail.com
          You may also order the book on Amazon, to order click arrow at bottom left of the web page 👇🏾"
          conclusion="  "
          />




          </div>
          <br>
          <br><br><br><br>  <br><br><br><br><br>  

          <DescriptionDetail id="author" title="About Author 💡" description ="
          Cletus Eliakim Matoma lives at plot number 30 ,
          Nteto Park Farm, in Mt Darwin ,with his wife Alert.
          He is an expert in animal health, an evangelist and a father of three sons"
          conclusion=""
          />
          <br>
          <br><br><br><br>  <br><br><br><br><br>

          <DescriptionDetail id="talk" title="Get in touch with us📞" description ="
          To book a talk or any arrangements reach us here  +263772702645/+263773589924/ or email us at cletusmatoma@gmail.com
          "
          conclusion=" "
          />
          <br>
          <br><br><br><br>  <br><br><br><br><br>


        </div>


        </div>        
      </div>
    </div>
  </template>
  
  <script>
  import Navbar from "./NavBar.vue";
  import ArrowComponent from "./ArrowComponent.vue";
  import 'bootstrap/dist/css/bootstrap.css';
  import DescriptionDetail from "./DescriptionDetail.vue";
  import VideoItem from "./VideoItem.vue";
  import ForeText from "./ForeText.vue"


  export default {
    name: 'BookPage',
    props: {},
    components: {
    Navbar,
    ArrowComponent,
    DescriptionDetail,
    VideoItem,
    ForeText

},
  };
  </script>
  
  <style scoped>
  /* Adjust styling as needed */
  @media (min-width: 901px) {
  .social-icons {
    display: none; /* Hide the social icons for screens wider than 900px */
  }
}




  @media (max-width: 900px) {
  .col-md-5 {
    display: none;
  }
}

  
  body {
    margin: 0;
  }
 
  
  .container-fluid {
    height: 100vh;
    width: 100vw;
   
  }
  
  .row {
    height: 100%;
    /* background: linear-gradient(to right, white, #f0f9ff); */
  }
  
  .col-md-5 {
    /* background-color: #f8f9fa;  */
    padding: 0;
  }
  
  .col-md-7 {
    padding: 0;

    /* background: linear-gradient(to bottom, white, #f0f9ff); */
  }
  
  .content-wrapper {
    height: 100%;
    background-position: center; /* Center the background image */
    background-size: cover; /* Cover the entire container */
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
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
  