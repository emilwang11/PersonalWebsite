<template>
  <b-container fluid class="px-0 my-5  ">



    <b-container fluid class="home px-0">
        <b-row class="my-4">
           <b-col
            sm="11"
            offset-sm="1"
            md="3"
            offset-md="1"
            class="mb-4 pl-0"
          >
            <b-img
              fluid
              src="/img/about.jpeg"
              class="w-100 my-4 py-4 background-image"
            ></b-img>
          </b-col>
          <b-col
            sm=12
            md=8
          >
            <div>
                <h2 class="align-center"> About </h2>
            </div>
            <p class ="about-content w-75">
             I'm a third year Systems Design Engineering student at the University of Waterloo. With a curiosity to understand how and why technology is built and love for problem solving, I've previously worked as a product manager at Transparent Kitchen and software engineer at Transparent Kitchen and TD Labs.
             </p>
             <p class ="about-content w-75 my-4">
              Community involvement has always been very important to me whether through clubs on campus or volunteering in the community.
              I've spent the last two years organizing Hack the North, bringing together 3000+ students from around the world to build and create together.
              </p>
              <p class ="about-content w-75 my-4">

            </p>
            <p class ="about-content w-75 my-4"> Learn more about my experience on my <a class= "resume-link" href="/img/resume.pdf" target="_blank"> resume.</a></p>

            <br>
            <h4> Some random facts about me: </h4>
               <ul  class ="about-content w-75 my-4">
                <li>I run a hand drawn card shop<a class= "resume-link" href="https://www.etsy.com/ca/shop/PapercraneCardsShop" target="_blank"> (shameless plug here) 💌 </a> </li>
                <li>Running during sunset is my favourite part of the day 🌅 </li>
                <li>I finish books faster than TV shows 📗 </li>
              </ul>


          </b-col>
        </b-row>
      </b-container>
  </b-container>
</template>

<style lang="scss">
.about-content{
  color: #3B3333;
  font-size: 1.1em;
  margin: auto;
  text-align: left;
}

  .quote{
  width: auto;
  height: 20%;
}
@media (max-width: 575.98px) {
  .quote{
  width: 90%;
  height: auto;
}
}

.background-image {
  background-size: cover;
  width: 80% !important;
  height: auto !important;
  background-position: center;
  border-radius: 10%;

}

.resume-link:hover{
color: rgb(187, 116, 98);
text-decoration: none;
}

.resume-link{
color: rgb(221, 148, 130);
text-decoration: none;
}

</style>
